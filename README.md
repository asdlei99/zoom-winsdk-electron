# Zoom Electron SDK on Windows

<div align="center">
<img src="https://s3.amazonaws.com/user-content.stoplight.io/8987/1541013063688" width="400px" max-height="400px" style="margin:auto;"/>
</div>

## Latest SDK Notifications
1. Our brand new [Zoom Developer Community Forum](https://devforum.zoom.us/) is now online!!! Check it out! We are here to help! :D

## Full Documentation && Community Support
You can find the full Zoom Electron SDK documentation and the community support forum here:
<div align="center">
   <a target="_blank" href="https://marketplace.zoom.us/docs/sdk/hybrid-frameworks/electron" style="text-decoration:none">
   <img src="https://s3-us-west-1.amazonaws.com/sdk.zoom.us/Doc-button.png" width="350px" max-height="350px" style="margin:1vh 1vw;"/>
   </a>
   <a target="_blank" href="https://devforum.zoom.us/c/desktop-sdk" style="text-decoration:none">
   <img src="https://s3-us-west-1.amazonaws.com/sdk.zoom.us/Forum-button.png" width="350px" max-height="350px" style="margin:1vh 1vw;"/>
   </a>
</div>

## Disclaimer

**Please be aware that all hard-coded variables and constants shown in the documentation and in the demo, such as Zoom Token, Zoom Access, Token, etc., are ONLY FOR DEMO AND TESTING PURPOSES. We STRONGLY DISCOURAGE the way of HARDCODING any Zoom Credentials (username, password, API Keys & secrets, SDK keys & secrets, etc.) or any Personal Identifiable Information (PII) inside your application. WE DON’T MAKE ANY COMMITMENTS ABOUT ANY LOSS CAUSED BY HARD-CODING CREDENTIALS OR SENSITIVE INFORMATION INSIDE YOUR APP WHEN DEVELOPING WITH OUR SDK**.

## Getting Started

The following instructions will get you a copy of the project up and running on your local machine for development and testing purposes.
* For detailed instructions, please refer to our documentation website: [https://marketplace.zoom.us/docs/sdk/hybrid-frameworks/electron](https://marketplace.zoom.us/docs/sdk/hybrid-frameworks/electron);
* If you need support or assistance, please visit our [Zoom Developer Community Forum](https://devforum.zoom.us/);

### Prerequisites

Before you try out our SDK, you would need the following to get started:

* **A Zoom Account**: If you do not have one, you can sign up at [https://zoom.us/signup](https://zoom.us/signup).
  * Once you have your Zoom Account, sign up for a 60-days free trial at [https://marketplace.zoom.us/](https://marketplace.zoom.us/)
* **A device with Windows OS**:
  * OS: Windows XP or later. Currently Windows 10 UWP is not supported.


### Installing

Clone or download a copy of our SDK files from GitHub. After you unzipped the file, you should have the following folders:

```
.
├── CHANGELOG.md
├── LICENSE.md
├── README.md
├── Zoom\ Win\ SDK\ Native\ Addon\ for\ Electron.docx
├── Zoom\ Win\ SDK\ Native\ Addon\ for\ Electron.md
└── zoom_electron
    ├── [demo] <-- demo app is inside
    ├── how\ to\ use.txt
    └── lib
```
Please refer to the following steps to install and compile:

1. Download the latest SDK from: https://github.com/zoom/zoom-winsdk-electron
2. Install python 2.7.* and setuptools
 * **Python 2.7.15**: https://www.python.org/downloads/release/python-2715/
 * Install pip: https://pip.pypa.io/en/stable/installing/
    * *curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py*
    * *python get-pip.py*
 * Install setuptools (Normally it comes with python 2.7 installation, if not, please install it manually)
    * *pip install setuptools*
3. Install **Node.js v8.12.0**(After installation, please restart your computer): https://nodejs.org/download/release/v8.12.0/node-v8.12.0-x86.msi
4. Install **Electron v2.0.7**: *npm install -g --arch=ia32 --save-dev electron@2.0.7*
5. Install Visual Studio:
  * https://visualstudio.microsoft.com/
6. Download Zoom Windows SDK: https://github.com/zoom/zoom-sdk-windows
7. Unzip and copy the files in **\zoom-sdk-windows-master\bin**, and paste them into **\zoom-sdk-electron\lib\windows\bin**
8. Run “cmd” and navigate to “zoom-sdk-electron\demo”
9. Run *“npm set npm_config_arch=ia32”*
10. Run *“electron .”* to run the demo app. You should see the demo app pops up.


## Documentation

Please visit [[https://marketplace.zoom.us/docs/sdk/hybrid-frameworks/electron](https://marketplace.zoom.us/docs/sdk/hybrid-frameworks/electron)] for details of each features and functions.

## Versioning

For the versions available, see the [tags on this repository](https://github.com/zoom/zoom-winsdk-electron/tags).

## Change log

Please refer to our [CHANGELOG](https://github.com/zoom/zoom-winsdk-electron/blob/master/CHANGELOG.md) for all changes.

## Frequently Asked Questions (FAQ)

* :one: `Error: Module version mismatch. Expected 50, got 57.at Error (native)`:
  * Our Electron SDK requires **Node.js version 8.12.0 and electron version 2.0.7** and if you have higher version, you will get this error message. Using **Node.js 8.12.0 and electron 2.0.7** will resolve this problem.
* Not finding what you want? We are here to help! Please visit our [Zoom Developer Community Forum](https://devforum.zoom.us/) for further assistance.

## Support

For any issues regarding our SDK, please visit our new Community Support Forum at https://devforum.zoom.us/.

## License

Use of this software is subject to important terms and conditions as set forth in the License file

Please refer to [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* :star: If you like our SDK, please give us a "Star". Your support is what keeps us moving forward and delivering happiness to you! Thanks a million! :smiley:
* If you need any support or assistance, we are here to help you: [Zoom Developer Community Forum](https://devforum.zoom.us/);

---
Copyright ©2019 Zoom Video Communications, Inc. All rights reserved.
