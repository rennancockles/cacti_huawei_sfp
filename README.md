# cacti_huawei_templates

Cacti templates to create graphs for huawei devices

&nbsp;

## Files
HUAWEI INTERFACE CURRENT => graph template for the current in each interface in mA

HUAWEI INTERFACE VOLTAGE => graph template for the voltage in each interface in volts

HUAWEI INTERFACE TEMPERATURE => graph template for the temperature in each interface in ºC

HUAWEI INTERFACE POWER (RX/TX) => graph template for the rx and tx power of the SFP in each interface

HUAWEI SFP => template for the current, voltage, temperature and SFP power in the same graph

&nbsp;

HUAWEI => data query template to get huawei data to create all graphs

&nbsp;

## Usage

Move the huawei.xml file to <cacti_path>/resource/snmp_queries/

Open cacti

Import the desired graph templates

In data queries menu, create a new data query using the path of the huawei.xml and 'Get SNMP Data (Indexed)' as data input method

Add the imported graph templates to the data query created

After saved, the graphs are ready to use
