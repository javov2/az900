# Choose the best Azure IoT service for your application

- Devices can send all data through message to a specific endpoint provided by Azure.
- Devices can receive firmware updates directly from Azure Iot Services.

## Azure IoT Hub

- Acts as central message hub providing bidirectional communication between devices and your IoT application.
- Can connect virtually any device to IoT Hub
- Supports multiple messaging patterns:  device-to-cloud telemetry, file upload from devices, and request-reply methods to control your devices from the cloud
- IoT allows for _command and control_ of your devices.
- IoT Hub monitoring maintain health of your solution by tracking events such as device creation, device failures, and device connections.

## Azure IoT Central

- Builds on top of Azure IoT Hub
- Adds a visual interface to helps management of solution
- Can update firmware pushing updates to devices
- Provide template for different scenarios across various industries.
- Can customize themes, templates, reports and alerts you want to see
- Can _command and control_ devices directly from UI
- Provides device templates: don't need server side code, but device still need be programmed to match the template chosen.

## Azure Sphere

- Security is major concern
- Azure Sphere has built-in communication and security features for internet-connected devices.
  
Azure Sphere comes in three parts:

- First part: Devices are specified design by Azure Sphere, example: Seeed Azure Sphere MT3620 Development Kit MCU
- Second part: customized Linux OS that handle communication 
- Third part: Azure Sphere Security Service (AS3), this validates and authenticate the device, once this is validated Azure deploys any OS or approved customer-developed software in the device.

Once 3 steps are done, device can interact with other IoT services.

## **Analyze the decision criteria**

- Is it critical to ensure that the device is not compromised?
  - Azure Sphere
- Do I need a dashboard for reporting and management?
  - If you want a pre-built customizable user interface: IoT Central
  - Your programmers can still create a customized set of management tools and reports by using the IoT Hub RESTful API.