# Internet-of-Things-Qwik-Start

<b>Internet of Things(IoT)</b>: A collective term for the physical objects that are connected to the internet and can exchange data without user involvement.

<b>Device</b>: A "Thing" in the Internet of Things- a processing unit that is capable of connecting to the internet and exchangign data with the cloud. Devices are often called "smart devices" or "connected devices". They communicate two types of data: "Telemetry and state".

<b>Telemetry</b>: All event data(for example, measurements about the environment) sent from devices to the cloud. Telemetry data sent from a device to the cloud is called "device telemetry event" data. You can use <i>Google Cloud Big Data Solution</i> to analyze telemetry data.

<b>Device State</b>: An arbitrary, user defined blob of data that describes the current status of the device. Device state data can be structured or unstructred, and flows only in the device-to-cloud direction.

<b>Device configuration</b>: An arbitrary, user-defined blob of data used to control or change a device's state. Configuration data can be structured or unstructured, and flows only in the cloud-to-device direction.

<b>Device Registry</b>: A container of devices with shared properties. You "register" a device with a service(like Cloud IoT Core) so that you can manage it(see the next item in this list).

<b>Device Manager</b>: The service you use to moniter device health and activity, update device configurations, and manage credentials and authentication.

<b>MQTT</b>: An industry- standard IoT protocol(Message Queue Telemetry Transport). MQTT is a publish/subscribe(pub/sub) messaging protocol.

<b>Components</b>: The main components of Cloud IoT Core are the device manager amd the protocol bridges:
<ul>
  <li>A <b>Device Manager</b> for registering devices with the service, so you can then monitor and configure them.</li>
  <li> Two <b>protocol bridges</b>(MQTT and HTTP) that devices can use to connect to Google Cloud.</li>
</ul>
