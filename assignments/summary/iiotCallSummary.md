# IOT Call Summary

The transition from industry 3.0 to industry 4.0 was stated and briefed about in the call. The key points are mentioned in this summary.

## Industrial Revolution

![IOT](extras/1_4WLN2QtpoBfqg7KgY6tzKg.jpeg)

- **Industry 1.0**- Mechanization & Steam Power
- **Industry 2.0**- Electrical Energy & Assembly Line
- **Industry 3.0**- Automation & Computer Electronics
- **Industry 4.0**- Cyber Physical Systems & IOT


## Industry 3.0


![IOT](extras/image7.gif)

> In Industry 3.0, we automate processes using logic processors and information technology. These processes often operate largely without human interference, 
but there is still a human aspect behind it. Data is stored in databases andrepresented in excels.

### Architecture

![IOT](extras/Capture.PNG)

> Sensors installed at various points in the Factory send data to PLC's which collect all the data and send it to SCADA and ERP systems for storing the data. Usually
this data is stored in Excels andCSV's and rearely get plotted as real-timegraphs or charts.

### Communication Protocols

![IOT](extras/Capture1.PNG)

- **Modbus**- Modbus is a data communications protocol originally published by Modicon  in 1979 for use with its programmable logic controllers (PLCs). 

 - **Profinet**- Profinet  is an industry technical standard for data communication over Industrial Ethernet, designed for collecting data from, and controlling equipment in industrial systems.

 - **CANopen**- CANopen is a communication protocol and device profile specification for embedded systems used in automation.

 - **EtherCAT**- EtherCAT is an Ethernet-based fieldbus system, invented by Beckhoff Automation. The protocol is standardized in IEC 61158 and is suitable for both hard and soft real-time computing requirements in automation technology.

## Industry 4.0

![ITO](extras/unnamed.gif)

> Industry 4.0 refers to a new phase in the Industrial Revolution that focuses heavily on interconnectivity, automation, machine learning, and real-time data. Industry 4.0, also sometimes referred to as IIoT or smart manufacturing, marries physical production and operations with smart digital technology, machine learning,
and big data to create a more holistic and better connected ecosystem for companies

###  Architecture

![IOT](extras/Capture2.PNG)

> Industry 4.0 or the fourth industrial revolution refers to the trend of integrating cyber physical systems into manufacturing. Outfitting manufacturing units with an array of sensors/end effectors provides the ability to build a virtual model of the unit.

###  Communication Protocols

![IOT](extras/Capture3.PNG)


- **MQTT**- MQTT is the standard messaging and data exchange protocol for the Internet of Things (IoT). The MQTT protocol provides a scalable and cost-efficient way to connect devices over the Internet

- **AMQP**- The Advanced Message Queuing Protocol (AMQP) is an open standard for passing business messages between applications or organizations.

- **OPC UA**- OPC UA (short for Open Platform Communications United Architecture) is a data exchange standard for industrial communication (machine-to-machine or PC-to-machine communication).

- **CoAp**- Constrained Application Protocol (CoAP) is a specialized web transfer protocol for use with constrained nodes and constrained networks in the Internet of Things. CoAP is designed to enable simple, constrained devices to join the IoT even through constrained networks with low bandwidth and low availability.

- **Websockets**- WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection.

- **Http**- The Hypertext Transfer Protocol is an application protocol for distributed, collaborative, hypermedia information systems.

- **RESTtful API**- A RESTful API is an application program interface (API) that uses HTTP requests to GET, PUT, POST and DELETE data.


## Transition from Industry 3.0 to 4.0

- ### Problems with Transition

    - **Cost**- Industry 3.0 devices are very Expensive asa factory owner I dont want to switch toIndustry 4.0 devices because they areExpensive.

    - **Downtime**- Changing Hardware means a big factorydowntime, I dont want to shut down myfactory to upgrade devices.

    - **Reliability**- I dont want to invest in devices which areunproven and unreliable.


- ### Solution

*Get data from Industry 3.0 devices/meters/sensors withoutcchanges to the original device and then send the data to the Cloudusing Industry 4.0 devices*

- ### Convert Industry 3.0 protocols toIndustry 4.0 protocols

![IOT](extras/Capture4.PNG)

- ### Challenges in Transition

    - Expensive Hardware

    - Lack of Documentaion

    - Properitary PLC protocols
    
- ## How to Convert?

*Special Libraries are available to convert data from industry 3.0 devices to industry 4.0*

