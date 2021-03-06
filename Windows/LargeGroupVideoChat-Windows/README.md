# Large Group Video Chat

*其他语言版本： [简体中文](README.zh.md)*

The  Windows Sample App is an open-source demo that will help you get large group video chat integrated directly into your windows applications using the Agora Video SDK.

With this sample app, you can:

- Join / leave channel
- Set role as broadcaster or audience
- Mute / unmute audio
- Change camera
- Setup resolution, frame rate and bit rate
- 17 people including local user.

This demo is written in **C++**

A tutorial demo can be found here: [Agora-Windows-Tutorial-1to1](https://github.com/AgoraIO/Basic-Video-Call/tree/master/One-to-One-Video/Agora-Windows-Tutorial-1to1)

## Developer Environment Requirements
* VC++ 2013(or higher)
* Windows 7(or higher)

## Running the sample program
First, create a developer account at [Agora.io](https://dashboard.agora.io/signin/), and obtain an App ID. define the APP_ID with your App ID.

    #define APP_ID _T("Your App ID")

If you don't want to modify the code part, you can create an AppId.ini file under Debug/Release. Modify the appId value to the App ID you just applied.

    [AppID]
    AppID=xxxxxxxxxxxxxxxxxxx

Next, download the **Agora Video SDK** from [Agora.io SDK](https://www.agora.io/en/download/). Unzip the downloaded SDK package and copy the **sdk** to the project folder(the old one may be over written).

Finally, Open OpenLive.sln with your VC++ 2013(or higher) and build all solution and run.

**Note：**

  1. After the program is compiled, if the program "xxx\xxx\xxx\Debug\Language\English.dll" cannot be started when running the program, 
      please select the OpenLive project in the Solution Explorer and right click. In the pop-up menu bar, select "Set as startup project" to solve. Then run the program again.
  2. You may encounter crash when running this demo under debug mode. Please run this demo under release mode.

## Contact us

- For potential issues, you may take a look at our [FAQ](https://docs.agora.io/en/faq) first
- Dive into [Agora SDK Samples](https://github.com/AgoraIO) to see more tutorials
- Would like to see how Agora SDK is used in more complicated real use case? Take a look at [Agora Use Case](https://github.com/AgoraIO-usecase)
- Repositories managed by developer communities can be found at [Agora Community](https://github.com/AgoraIO-Community)
- You can find full API document at [Document Center](https://docs.agora.io/en/)
- If you encounter problems during integration, you can ask question in [Developer Forum](hhttps://stackoverflow.com/questions/tagged/agora.io)
- You can file bugs about this sample at [issue](https://github.com/AgoraIO/Advanced-Video/issues)

 
## License

The MIT License (MIT).
