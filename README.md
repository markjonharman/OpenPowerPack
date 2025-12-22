# OpenPowerPack
Open Source hardware and software for 2S-4S Battery Controller

When working on powering a mobile embedded open source project I realized there seemed to be a gap in the available open source hardware out there for making a USB-C power pack/power bank. Most projects focus on a smaller single LiPo or are focused on the substatially larger homewall type applications. Instead, this PCBA allows you to make a 2S-4S battery pack with fast charging and very high output power capabilities that can be easily be embedded in a design. The original vision was for supporting Raspberry Pi5 based systems but that is not where it has to end.

The philosphy has been simple: leverage USB-C PD for input charging (and output on some versions) and provide maximum flexbility while trying to maintain costs as best as possible.

The PCB will be designed such that it should be possible for PCBway, JLCPCB and others to fabricate it. Assembly for most people is also best handled by someone like PCBway or JLCPCB unless you are very experienced working with hot air tools.

Always remember it'll only ever be as good as the batteries you put in it! While many applications may be able to use the cheapest batteries, if you intend on pushing the output hard you need to ensure you use high quality batteries otherwise you may not get what you are looking for.

# Model Currently in Development

**OPP-100-5-NPD**

USB-C PD 100W Charging

2S-4S Pack Topology (Parallel Depth tbd)

5V-24V Regulated Output Voltage

5A Output Current Limit (connector limited)

100W Output Power Limit

USB-C Output Connector (Non-PD)

# Future Models for Development

**OPP-100-10-TJ**

USB-C PD 100W Charging

2S-4S Pack Topology (Parallel Depth tbd)

5V-24V Regulated Output Voltage

10A Output Current Limit

100W Output Power Limit

TJ0211 Output Connector

**OPP-100-5-PD**

USB-C PD 100W Charging

2S-4S Pack Topology (Parallel Depth tbd)

5A Output Current Limit

100W Output Power Limit

USB-C PD 100W Output

**OPP-240-24-TJ**

USB-C PD 240W Charging

2S-4S Pack Topology (Parallel Depth tbd)

5V-24V Regulated Output Voltage

24A Output Current Limit (tbd)

240W Output Power Limit

TJ0451 Output Connector

**OPP-240-5-PD**

USB-C PD 240W Charging

2S-4S Pack Topology (Parallel Depth tbd)

5V-24V Regulated Output Voltage

5A Output Current Limit

240W Output Power Limit

USB-C PD 240W Output
