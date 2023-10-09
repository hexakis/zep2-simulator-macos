# zep2-simulator-macos

## What is this guide and what is ZEP2?
This guide is an step by step guide to installing ZEP2 which is a CPU simulator
made exclusively for Windows operating systems. Z

ZEP2 is used extensively across multiple universities and colleges in The Netherlands
to introduce students to Assembly Language and the basics of the inner workings of CPU's


## Pre-Requisites
You should have the following tools installed to begin running ZEP2 on MacOS:

* [WineHQ](https://www.winehq.org/) [Compatibility Layer "emulator"]
* [Winetricks](https://github.com/Winetricks/winetricks) [Work Arounds Common Problems Wine]
* [Wineskin](https://github.com/Gcenx/WineskinServer) [Wine Wrapper]


## WineHQ
> I myself have an 2023 Macbook Air with the Apple M2 chip
using WineHQ by iteself to run ZEP2 does not work for me probably because of the
Apple M2 CPU Architecture so you should always first try the following before moving on to see if it works:

Open your terminal in the folder where the ZEP2 exe file is located and run:  
`wine64 <filename>.exe`

If this opens up ZEP2 without any issues, congratulations! Your done.  
Does this not open up ZEP2 without issues? Continue following the guide

## Wineskin 
Wineskin allows you to create bundled Wine prefixes and run Windows programs like any other macOS apps.

<p align="left" width="100%">
  First you should install the following Engine by pressing the "+" <br>
  <img width="33%" alt="Screenshot 2023-10-06 at 22 54 19" src="https://github.com/hexakis/zep2-simulator-macos/assets/38819097/ab02140a-8d1b-485f-96d5-ce9d025c3ff3">
</p>

<p align="left" width="100%">
  After installing this engine continue by hitting "Create New Blank Wrapper" <br>
  <img width="33%"  alt="Screenshot 2023-10-06 at 22 55 21" src="https://github.com/hexakis/zep2-simulator-macos/assets/38819097/39166830-e273-4426-94f4-8284f2ca390d">
</p>

<p align="left" width="100%">
  Rename this to whatever you want but I will call it ZEP2 <br>
  <img width="33%" alt="Screenshot 2023-10-06 at 22 55 26" src="https://github.com/hexakis/zep2-simulator-macos/assets/38819097/e230c441-c533-4d79-bb4b-28f4e0ad9b32">
</p>

Now press on the newly made ZEP2 application
<img width="1710" alt="Screenshot 2023-10-09 at 10 14 17" src="https://github.com/hexakis/zep2-simulator-macos/assets/38819097/86bacc2c-7f92-4e24-8ee6-aee390b1d241">


<p align="left" width="100%">
  Press "Install Software" <br>
  <img width="33%" alt="Screenshot 2023-10-06 at 22 57 06" src="https://github.com/hexakis/zep2-simulator-macos/assets/38819097/85f3947f-4c05-44a3-878f-ac59a4592e2e">
</p>

<p align="left" width="100%">
  Here you should click on "Copy a Folder Inside" <br>
  <img width="33%" alt="Screenshot 2023-10-06 at 22 57 31" src="https://github.com/hexakis/zep2-simulator-macos/assets/38819097/dfbe9eb8-bfc5-4ef3-a32e-e41a8e58e13e">
</p>

<p align="left" width="100%">
  Then select the folder containg the ZEP2.exe <br>
  <img width="33%"  alt="Screenshot 2023-10-06 at 22 58 38" src="https://github.com/hexakis/zep2-simulator-macos/assets/38819097/00bd743f-f152-42ae-bfcf-3fec66d1c984">
</p>

<p align="left" width="100%">
  <img wwidth="33%"  alt="Screenshot 2023-10-06 at 22 58 48" src="https://github.com/hexakis/zep2-simulator-macos/assets/38819097/c166388c-b7d8-4de2-ac9d-f343f50218b8"> <br>
  Now in the Application Finder you can open ZEP2 by double clicking the new ZEP2 Application
</p>

<p align="left" width="100%">
  <img width="33%" alt="Screenshot 2023-10-06 at 22 56 58" src="https://github.com/hexakis/zep2-simulator-macos/assets/38819097/a8e50306-5533-4c77-8a52-cbdffdba0f0b"> <br>
  You should see the following screen
</p>
<img width="1822" style="float: left;"  alt="Screenshot 2023-10-06 at 22 59 14" src="https://github.com/hexakis/zep2-simulator-macos/assets/38819097/7e339ec2-741b-4c36-81aa-e6b9596999f9">
<img width="1822" style="float: left;"  alt="Screenshot 2023-10-06 at 22 59 25" src="https://github.com/hexakis/zep2-simulator-macos/assets/38819097/83371013-fa3a-4da9-9f71-63b883202019">
