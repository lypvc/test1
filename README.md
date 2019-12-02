# Interoperating with Docker on Windows IoT Core and Windows IoT Enterprise
This sample is designed to work with Windows containers on Windows IoT Core and Windows IoT Enterprise.

The sample consists of the following projects:

* SimpleServer - a .Net Standard 2.0 project that implements the SimpleServer class, which is shared by BackgroundServer and ConsoleServer.
* SharedData -  a .Net Standard 2.0 project that implements shared data definition classes.
* ContainerApp - a .Net Core 2.0 project that implements a WebSocket client that runs inside a Windows container.
* ConsoleServer - a .Net Core 2.0 project that implements a WebSocket server in a console application.
* BackgroundServer - a Windows IoT Core Background Application that implements a sample WebSocket server.

For detailed instructions on how to use the sample on Windows IoT Core or Windows IoT Enterprise please select one of the following links:

*	[Windows IoT Core](./WindowsIotCore.md)
*	[Windows IoT Enterprise](./WindowsIotEnterprise.md)
