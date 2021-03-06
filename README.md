# Kitchen Sink

Kitchen Sink is a developer friendly sample implementation of Spark client SDK and showcases all SDK features.

## Table of Contents
- [Setup](#setup)
- [Install](#install)
- [Usage](#usage)
- [License](#license)

## Setup
This application is built with **Vistual Studio 2015** and requires:
- .NET Framework 4.5.2 or higher version
- Win8 or Win10

1. Open KitchenSink.sln, build KitchenSink-WPF project. The project will download "Cisco.Spark.WindowsSDK" NuGet package at first time of building.
2. The build output path is at \binary\...
3. Run KitchenSink.exe.

## Install
1. You can get the installer of this application. [Get the current release](https://github.com/ciscospark/spark-windows-sdk-example/releases)
2. setup.exe is the installer program, you can run it and install it by construction.


## Usage
Below is the features of this demo.
1. Login and Logout:
This feature demonstrate [OAuth](https://oauth.net/) and [JSON Web Token](https://jwt.io/) authenticate method.
2. Video and audio setup:
This feature demonstrate preview camera and select audio/video IO device such as microphone, speaker, camera and so on.
3. Initiate call:
This feature demonstrate call out by one on one call and room call.
4. Waiting call:
This feature demonstrate incoming call.

## License

&copy; 2016-2017 Cisco Systems, Inc. and/or its affiliates. All Rights Reserved.

See [LICENSE](https://github.com/ciscospark/spark-windows-sdk-example/blob/master/LICENSE) for details.
