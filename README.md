# Flutter samples

[![Build Status](https://github.com/flutter/samples/workflows/Main%20Branch%20CI/badge.svg)](https://github.com/flutter/samples/actions?workflow=Main%20Branch%20CI)

A collection of open source samples that illustrate best practices for
[Flutter].

## Contributing

We appreciate fixes and necessary improvements to existing samples. **But in most cases, we're not currently adding new samples to this repository** while we rethink sample code in the new LLM world.

Please read the [contributor's guide] if you have contributions.

Googler's, you can freely add samples to the [flutter/demos] repository.

## Index

### Quickstarts

* [`asset_transformation`] - 演示如何转换图像的颜色比例和格式。
* [`background_isolate_channels`] - 演示如何使用长期的 isolates。
* [`code_sharing`] - 演示如何使用 [`package:shelf`] 在 Flutter 客户端和 Dart 服务器之间共享业务逻辑。
* [`context_menus`] - 此示例显示了如何创建和自定义跨平台上下文菜单，例如移动设备上的文本选择工具栏或桌面上的右键单击菜单。
* [`desktop_photo_search`] - 演示 Material 和 FluentUI 设计系统中的桌面功能。
* [`dynamic_theme`] - 一个开发人员示例，演示如何根据 Gemini API 的输出调用设备上的 Flutter API。
* [`form_app`] - 演示不同类型表单和最佳实践的示例。
* [`game_template`] - （注意：已弃用！）Flutter 中的入门游戏，具有移动（iOS 和 Android）游戏的所有花哨功能。
* [`gemini_tasks`] - 一个用 Flutter 编写的开发人员示例，演示如何使用 Gemini API 以自然语言与待办事项列表交互。
* [`google_maps`] - 演示 Flutter 插件的谷歌地图。
* [`infinite_list`] - 一个 Flutter 示例应用程序，显示了“无限列表”用户体验模式的实现。
* [`isolate_example`] - 一个示例应用程序，演示使用 [isolates] 时的最佳实践。
* [`navigation_and_routing`] - 一个示例，显示如何使用 [go_router] API 来处理常见的导航场景。
* [`place_tracker`] - 一个使用 [google_maps_flutter plugin] 插件的示例位置跟踪应用程序。
* [`platform_design`] - 此示例项目展示了一个 Flutter 应用程序，该应用程序在遵守 Android 和 iOS 上的不同设计模式的同时，最大限度地提高了应用程序代码的重用率。
* [`provider_counter`] - Flutter 应用程序的启动程序，但使用 [package:provider] 来管理状态。
* [`provider_shopper`] - 一个 Flutter 示例应用程序，显示了使用 [package:provider] 的状态管理方法。
* [`simple_shader`] - 一个简单的 Flutter 片段着色器 [Flutter fragment shaders] 示例项目。
* [`simplistic_calculator`] - 一个计算器，用于演示桌面 Flutter 应用程序的简单启动。
* [`simplistic_editor`] - 此示例文本编辑器展示了如何使用 [TextEditingDeltas] 和 DeltaTextInputClient 来扩展和收缩文本的样式范围。
* [`testing_app`] - 一个示例应用程序，显示 Flutter 中不同类型的测试。
* [`web_embedding`] - 此目录包含如何在 web 应用程序中嵌入 Flutter 的示例（无iframe）。
  * [`element_embedding_demo`] - 修改 flutter 应用程序的 index.html，使其在自定义 hostElement 中启动。这是最基本的嵌入示例。
  * [`ng-flutter`] - 一个简单的 Angular 应用程序（和组件），复制了上述示例，但采用 Angular 风格。

### Native platform samples

* [`add-to-app`] - 示例集合，演示如何将 Flutter 视图嵌入到本地应用程序中。
  * [`fullscreen`] — 将 Flutter 的全屏实例嵌入到现有的 iOS 或 Android 应用程序中。
  * [`prebuilt_module`] — 嵌入 Flutter 的全屏实例作为预构建库，可以加载到现有的 iOS 或 Android 应用程序中。
  * [`plugin`] — 将使用插件的全屏 Flutter 实例嵌入到现有的 iOS 或 Android 应用程序中。
  * [`books`] — 模拟将 Flutter 嵌入现有 Android 应用程序的真实用例，并演示使用 [Pigeon] 在 Flutter 和宿主应用程序之间进行通信。
  * [`multiple_flutters`] — 展示如何使用 Flutter 引擎组 API 以低内存成本将 Flutter 的多个实例嵌入到现有应用程序中。
  * [`android_view`] — 展示如何在 Android 的视图级别将 Flutter 插件集成到应用程序模块中。
* [`android_splash_screen`] - 展示如何为 Android 应用添加启动画面。✅
* [`ios_app_clip`]
* [`platform_channels`] - 一个示例应用程序，演示如何在 Flutter 中使用 MethodChannel、EventChannel、BasicMessageChannel 和 MessageCodec。
* [`platform_view_swift`] - 一个 Flutter 示例应用程序，将原生 iOS UIViewController 与全屏 Flutter 视图相结合。

### Demo galleries

* [`animations`] - 展示 Flutter 的动画功能。✅
* [`material_3_demo`] - 展示 Flutter 材质库中的 [Material 3] 功能。✅

### Demo apps

* [`compass_app`] - 一个实现 MVVM 架构的示例应用程序。
* [`deeplink_store_example`] - 一个实现 go_router 深度链接的演示应用程序。
* [`veggie_seasons`] - 一个演示应用程序。

## Flutter sample code

Samples are **correct and concise code** that developers 
can **quickly understand** and **easily reuse** with minimal side effects. 
Samples teach developers how to be successful using Flutter and Dart. 
They are maintained on an ongoing basis 
to reflect changing APIs and best practices.

### Types of samples

There are two types of sample code in this repository:

* **Quickstarts** 快速入门提供了扩展的起点。他们回答了这样一个问题：“实现此功能所需的最小代码量是多少？”
* **Demo apps** 演示应用程序旨在构建和运行。他们演示产品，而不是如何编写代码。

A majority of samples in this repository are quickstarts.

## Usage

Every sample in this repo is fully runnable. To run an example, 
use `flutter run` inside that example's directory. 
See the [getting started guide] to install the `flutter` tool.

> [!IMPORTANT]  
> If you want to run an add-to-app sample, there are additional requirements.
> We suggest reading the [add-to-app documentation].

## Interested in contributing?

See the [contributor's guide]!

## Questions or issues?

If you have a general question about one of these samples or how to adapt its
techniques for one of your own apps, try one of these resources:

* [The FlutterDev Discord]
* [The Flutter Community forum]

If you run into a bug in one of the samples, please file an issue in the
[`flutter/samples` issue tracker].


[`asset_transformation`]: ./asset_transformation
[`background_isolate_channels`]: ./background_isolate_channels
[`code_sharing`]: ./code_sharing
[`context_menus`]: ./context_menus
[`desktop_photo_search`]: ./desktop_photo_search
[`dynamic_theme`]: ./dynamic_theme
[`form_app`]: ./form_app
[`game_template`]: ./game_template
[`gemini_tasks`]: ./gemini_tasks
[`google_maps`]: ./google_maps
[`infinite_list`]: ./infinite_list
[`isolate_example`]: ./isolate_example
[`navigation_and_routing`]: ./navigation_and_routing
[`place_tracker`]: ./place_tracker
[`platform_design`]: ./platform_design
[`provider_counter`]: ./provider_counter
[`provider_shopper`]: ./provider_shopper
[`simple_shader`]: ./simple_shader
[`simplistic_calculator`]: ./simplistic_calculator
[`simplistic_editor`]: ./simplistic_editor
[`testing_app`]: ./testing_app
[`web_embedding`]: ./web_embedding
[`element_embedding_demo`]: ./web_embedding/element_embedding_demo
[`ng-flutter`]: ./web_embedding/ng-flutter
[`add-to-app`]: ./add_to_app
[`fullscreen`]: ./add_to_app/fullscreen
[`prebuilt_module`]: ./add_to_app/prebuilt_module
[`plugin`]: ./add_to_app/plugin
[`books`]: ./add_to_app/books
[`multiple_flutters`]: ./add_to_app/multiple_flutters
[`android_view`]: ./add_to_app/android_view
[`android_splash_screen`]: ./android_splash_screen
[`ios_app_clip`]: ./ios_app_clip
[`platform_channels`]: ./platform_channels
[`platform_view_swift`]: ./platform_view_swift
[`animations`]: ./animations
[`material_3_demo`]: ./material_3_demo
[`compass_app`]: ./compass_app
[`deeplink_store_example`]: ./deeplink_store_example
[`veggie_seasons`]: ./veggieseasons

[Flutter]: https://flutter.dev
[getting started guide]: https://docs.flutter.dev/get-started/install
[add-to-app documentation]: https://docs.flutter.dev/add-to-app
[isolates]: https://api.dart.dev/dart-isolate/Isolate-class.html
[Material 3]: https://m3.material.io
[go_router]: https://pub.dev/packages/go_router
[google_maps_flutter plugin]: https://github.com/flutter/plugins/tree/master/packages/google_maps_flutter
[package:provider]: https://pub.dev/packages/provider
[Flutter fragment shaders]: https://docs.flutter.dev/development/ui/advanced/shaders
[TextEditingDeltas]: https://api.flutter.dev/flutter/services/TextEditingDelta-class.html
[Pigeon]: https://pub.dev/packages/pigeon
[`package:shelf`]: https://pub.dev/packages/shelf
[svn]: https://subversion.apache.org/
[partial clone]: https://github.blog/2020-12-21-get-up-to-speed-with-partial-clone-and-shallow-clone/
[contributor's guide]: CONTRIBUTING.md
[The FlutterDev Discord]: https://discord.gg/rflutterdev
[The Flutter Community forum]: https://forum.itsallwidgets.com/latest
[`flutter/samples` issue tracker]: https://github.com/flutter/samples/issues
[flutter/demos]: https://github.com/flutter/demos
