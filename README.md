
# (免费)数据分析打点平台

**GameAnalytics** is a leading analytics and data management platform designed to help game developers monitor and optimize the performance of their games. We provide a powerful set of tools, including real-time monitoring, custom dashboards, flexible event types, IAP and ad revenue tracking, A/B testing, and a suite of data processing tools – giving you complete control of your data and helping you turn it into insights.

**GameAnalytics** 是一个领先的分析和数据管理平台，旨在帮助游戏开发者监控和优化其游戏的性能。我们提供一套强大的工具，包括实时监控、自定义仪表板、灵活的事件类型、IAP 和广告收入跟踪、A/B 测试以及一套数据处理工具，让您完全控制数据并帮助您将其转化为见解

该库主要服务于 `https://github.com/AlianBlank/GameFrameX` 作为子库使用。


# 使用方式(三种方式)
1. 直接在 `manifest.json` 文件中添加以下内容
   ```json
      {"com.gameanalytics.gameanalytics": "https://github.com/AlianBlank/com.gameanalytics.gameanalytics.git"}
    ```
2. 在Unity 的`Packages Manager` 中使用`Git URL` 的方式添加库,地址为：https://github.com/AlianBlank/com.gameanalytics.gameanalytics.git

3. 直接下载仓库放置到Unity 项目的`Packages` 目录下。会自动加载识别

# 改动功能

1. 增加 `Packages` 的支持
2. 增加 `link.xml` 的支持

# 使用文档

https://docs.gameanalytics.com/integrations/sdk/unity


# 以下为原始内容

------------------------------------------------------
GameAnalytics Unity SDK
------------------------------------------------------

Thank you for downloading the GameAnalytics Unity SDK.

Visit our website at:
http://www.gameanalytics.com/

Review the Unity SDK documentation at:
https://gameanalytics.com/docs/unity-sdk

------------------------------------------------------
GETTING STARTED
------------------------------------------------------

A GameAnalytics menu has been added under Window in
the menu bar.

Create a GameAnalytics Settings resource by going to:
Window > GameAnalytics > Select Settings

The Settings resource allows you to create an account,
studio and game, login to get your game key and secret
key, and setup Custom Dimensions, Resource Types, and
other advanced settings. When the Settings resource is
selected you can also check what version of the SDK you
are currently using.

------------------------------------------------------
iOS
------------------------------------------------------

Xcode must be configured to work with GameAnalytics.

For more information about the build process go here:
https://gameanalytics.com/docs/unity-sdk#ios-build

------------------------------------------------------
Android
------------------------------------------------------

Unity 5 can build the SDK for the Android platform without
any modification.

https://gameanalytics.com/docs/unity-sdk#android-build

------------------------------------------------------

To use the SDK on Unity 4.6.x+ please
download the compatible SDK here:

http://download.gameanalytics.com/unity/GA_SDK_UNITY_4.unitypackage

------------------------------------------------------

Have fun using GameAnalytics!

The GameAnalytics Team
