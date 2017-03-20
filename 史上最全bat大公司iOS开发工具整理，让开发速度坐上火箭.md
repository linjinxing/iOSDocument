史上最全bat大公司iOS开发工具整理，让开发速度坐上火箭

iOS essential tools to skyrocket your development. one command to install.



## 代码自动生成

- [**Xcode Snippets**](https://github.com/mattt/Xcode-Snippets)：这视乎是最明显的一个，但却可以减少大量开发时间。创建起来像[drag-and-drop](http://nshipster.com/xcode-snippets/)那么简单，这里有很多优秀的示例（[XcodeCodeSnippets](https://github.com/brennanMKE/XcodeCodeSnippets)、[CodeSnippets](https://github.com/jaydee3/CodeSnippets) ）。

- [XcodeBoost](https://github.com/fortinmike/XcodeBoost) 是一款可以让开发者轻而易举地检查和修改Objective-C代码的插件。XcodeBoost能够自动进行一些繁琐的操作，比如方法的定义与声明、添加基于命令行的代码处理（剪切/复制/粘贴/重复/删除行）、持续高亮等。

- [**快速Add #import**](https://github.com/markohlebar/Peckham) 不用自己写import，当引用一个类时，就会自动import头文件

- OMColorSense

  一个简洁的可视化颜色插件。在你编辑颜色的RGB值的时候，会在代码上方出现一个小的色块，显示对应的颜色。点击色块还会弹出一个颜色编辑器，在编辑器中得到的色值会自动填入colorWithRed:green:blue:alpha:方法中，贴心！

- [**Auto-Importer-for-Xcode**](https://github.com/citrusbyte/Auto-Importer-for-Xcode) 不用自己写import，当引用一个类时，就会自动import头文件

- [SCXcodeSwitchExpander](https://github.com/stefanceriu/SCXcodeSwitchExpander) 是一个可以帮你展开 switch 语句的插件，还会自动帮你插入 case 语句。

- [KSImageNamed-Xcode](https://github.com/ksuther/KSImageNamed-Xcode) 提供了图片名称自动补全功能的插件。

  [![Screenshot](https://camo.githubusercontent.com/c354bf04524df86daeabe7a6d2b9926fac790f85/68747470733a2f2f7261772e6769746875622e636f6d2f6b7375746865722f4b53496d6167654e616d65642d58636f64652f6d61737465722f73637265656e73686f742e676966)](https://camo.githubusercontent.com/c354bf04524df86daeabe7a6d2b9926fac790f85/68747470733a2f2f7261772e6769746875622e636f6d2f6b7375746865722f4b53496d6167654e616d65642d58636f64652f6d61737465722f73637265656e73686f742e676966)

- [Lin](https://github.com/questbeat/Lin)  这个插件提供了 NSLocalizedString 的自动补全插件。

- [Shark](https://github.com/kaandedeoglu/Shark) 用于将 .xcassets 文件夹转换成一个类型安全枚举的 Swift 脚本。

- [SwiftGen](https://github.com/AliSoftware/SwiftGen) 一个生成 Swift 代码工具的集合（生成资源的枚举，storyboard，本地化字符串和 UIColor）。

- [R.swift](https://github.com/mac-cain13/R.swift) 在 Swift 项目中，强类型的自动补全资源名称的工具，包括图片，单元格和 segue 的工具

- [Eject](https://github.com/Raizlabs/Eject/)  从xib生成相应的swift代码

- [JSONExport](http://bit.ly/1Fm4PHE) json数据转换成对象

  Screenshot shows JSONExport used for a snippet from Twitter timeline JSON and converting it to Swift-CoreData. [![alt tag](https://cloud.githubusercontent.com/assets/5157350/5228493/72693010-7713-11e4-9e42-625a8590424a.png)](https://cloud.githubusercontent.com/assets/5157350/5228493/72693010-7713-11e4-9e42-625a8590424a.png)

- [json2swift](http://bit.ly/2fuECkf) A macOS command line tool that generates excellent Swift data models based on JSON data. [![Overview](https://github.com/ijoshsmith/json2swift/raw/master/images/json2swift.jpg)](https://github.com/ijoshsmith/json2swift/blob/master/images/json2swift.jpg)

  ​

- ### [*Sourcery*](https://github.com/krzysztofzablocki/Sourcery)

  Swift是一门美妙的语言，产生了许多很棒的iOS app。可惜的是，它具有非常局限的运行时间并且没有元编程功能。

  这导致我们的项目包含了大量的重复代码模式，它们也可以被认为是相同的代码，只有些许不同。

  Sourcery能够让开发者不再一遍又一遍的重复做一些事情。它让我们在能够使用元编程的同时还能够保持高强度的键入，防止bug并且利用编辑器。

- [PAW](http://luckymarmot.com/paw)

  确保REST API工作正常，并且准确知道如何配置请求可以帮你减少大量错误，而不需要重新编译和通过繁琐的UI进行测试。PAW并不仅仅方便你管理API端点，它还可以缓存结果和适应环境的变化。此外，你也可以通过PAW保存会话和引用，或者和团队成员进行分享。

  让PAW与众不同的是它的代码生成工具，不仅仅是简单的cURL，甚至是NSURLConnection/AFNetworking Objective-C代码也可以。在iOS平台使用网络请求变得如此的简单。

  ![img](http://segmentfault.com/img/bVccwU)

- iSwift

  如果需要将大量OC代码转换成Swift代码，这时候你可以选择iSwift，这款工具操作简单，虽然尚有不足但是已经能够极大的减少你的工作量了

- [PaintCode](http://www.paintcodeapp.com/)

  ![img](http://segmentfault.com/img/bVccxj)

  用代码进行绘图会耗费大量的开发时间，而PaintCode是一个专为设计师准备的简单矢量图形绘图应用程序。PaintCode可帮你节省大量时间和工作量，并且没有编程经验的设计师也能立即画出美丽的控件、图标或其他UI界面元素并直接生成适用于iOS或者OS X的Objective-C代码。

- Sip

  这是我最喜欢的工具之一了，它的功能很简单就是取色，功能虽然简单但是它已经做到了极致。至少我是这么感觉的。它可以通过快捷键从快速调出取色器，并且在取色的同时生成代码（例如直接生成色值:#ff0000，又例如iOS OC代码:

  ```
  [UIColor colorWithRed:0.95 green:0.89 blue:0.89 alpha:1.00]
  ```

  Swift代码:

  ```
  UIColor(red:0.96, green:0.34, blue:0.31, alpha:1.00)
  ```
  在粘贴板上，只需要在您要的用的地方粘贴就好了。方便之极。而且还是免费哟。爽到爆。

  ![img](http://upload-images.jianshu.io/upload_images/1475667-aa89654bb6383b8f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- *QuickLocalization**

  你是否已经厌倦了反复写NSLocalizedString？如果是，那么QuickLocalization插件可以助你一臂之力。当你在编辑字符串的时候，只需要按下option+shift+d，就可以将@“Any String”转换成NSLocalizedString(@"Any String", nil)。而且还可以通过修改配置来定义要出现在comment字段中的内容。我已经离不开它了！

  ![img](http://mmbiz.qpic.cn/mmbiz/CN8VYJLAIV2e1PZOy16ib4f6DgwSzlXibpx0tSn4pQCZLD7Ajl2J0rLpBXicaNERia77K2GHBXMGAFek4iaSAAFb1aA/0?wx_fmt=gif&tp=webp&wxfrom=5&wx_lazy=1)





## 质量保证

- [infer](https://github.com/facebook/infer) Facebook 静态分析利器浅析
- oclint 
- [Slender](http://dragonforged.com/slender/) ($)  一个很棒的应用，可以分析你的应用，找出各种问题，比如缺少视网膜屏的图片，没用到的图- 片，能压缩的图片。使用Slender去除掉那些没用的图片，可以为你的iPhone应用节省好多空间。
- [Apple如何知道你用私有API](http://www.csdn.net/article/2012-02-10/311678)
- [私有API扫描工具appScanner](https://github.com/ChimpStudios/App-Scanner) 




## 诊断&调试

有时候我们正在开发应用，我们想更好的了解到底发生了什么，修bug或者改善性能。

- **[injectionforxcode](https://github.com/johnno1962/injectionforxcode)** 调试利器 

- **Chisel**  使用LLDB可以显著减少开发者的调试时间。Facebook开发了一套用于LLDB的命令十分有效，特别是当出现了一些难以复现的问题的时候。虽然熟悉它需要一定的时间，但是绝对值得。

- [Pony Debugger](https://github.com/square/PonyDebugger) – 另一个你可以嵌入一个库到你调试版本中的工具，Pony Debugger实际上使用了Chrome的开发工具来查看设备上发出的网络请求，还有一个基本的Core Data浏览器。很难描述，请看我的[screencast on Pony Debugger](http://nsscreencast.com/episodes/54-pony-debugger)吧。

- [Reveal](http://revealapp.com/)

  ![img](http://segmentfault.com/img/bVccwI)

  为了查看UI发生的变化，我们过去常常会重新编译我们的应用，不过效率非常低。Reveal为开发者带来了类似Firebug和Web Inspector的强大工具。先进的2D和3D可视化技术可以让你查看app运行时的视图层次。可以让你快速Debug视图布局问题和渲染问题。

  Reveal的强大之处并不仅限于检测你的app，[Peter Steinberger](http://petersteinberger.com/blog/2013/how-to-inspect-the-view-hierarchy-of-3rd-party-apps/)向我们展示了它是如何用在其他app中。

  此外，Reveal还支持键盘；可通过视图层级帮你理解复杂的app；3D导航，可流畅旋转，缩放，选中以及高亮；Reveal可让你清楚哪个视图执行了哪个类；Reveal可在设备或者模拟器上运行，可以简单地发现，连接至iOS app。

  参考阅读：[Reveal通过视图层次帮你理解复杂的app 并提供相关Debug功能](http://www.cocoachina.com/applenews/devnews/2013/0717/6621.html)

- [Spark Inspector](http://sparkinspector.com/) 是界面调试工具

- [Runscope](http://runscope.com/) ($) – Runscope是一个网络服务，可以捕捉请求，记录日志，给你关于你的API的有用数据。因为它是个HTTP通道API， 搭建简单，你只需要更换你的主机名就行了。

- [SimPholders](http://simpholders.com/)

  SimPholders可让你快速直接地访问iPhone模拟器应用的app文档。你可以通过SimPholders找到数据库文件、永久存储以及缓存，它是一个非常实用的app debug工具，同时还可以离线使用。

  ![img](http://segmentfault.com/img/bVccwJ)

  假如你正在寻找一款可替代的工具，你也可以看看[Folder Simulator](http://nimbleworks.co.uk/blog/simulator-folders/)。

- [simMagnifier](http://bit.ly/2izLtw9) 

  A mac app that gives you easy access to the latest run apps on your iOS Simulators. simMagnifier lets you explore Core Data content in the Simulator's Documents folders and will try to detect your Core Data configuration automatically. Once loaded you can add new instances, delete or edit current ones, filter entities, explore relationships, and execute fetch requests. It also gives you quick access to important Simulator folders, like Documents, Application Support, App Bundle, and more, and you can check data stored in NSUserDefaults.

- [Spark Inspector](http://sparkinspector.com/) –  在调试模式运行你的应用时，可以用3D来展示调试你的视图层次。这个应用你真的要看到了才会真正明白它的价值。它能帮助你了解你的应用是由哪些视图组成的。它还带有一个通知中心监视器，你可以轻松看到发出了哪些NSNotification，谁在观察它们。另一个监控NSNotification的应用是[Reveal](http://revealapp.com/)。

- [KPRunEverywhereXcodePlugin](https://github.com/kitschpatrol/KPRunEverywhereXcodePlugin) - 只需一次点击，就可以在多个 iOS 设备上构建，运行 App。

- [MCLog](https://github.com/yuhua-chen/MCLog) - 用于控制台内容筛选的插件。

- **Network Link Conditioner**

  这是一个来自苹果官方的工具，它可以模拟任何网络环境，如3G，Edge等等，也可以重新定义当前的网络环境，如网络延迟、带宽或丢包率。Network Link Conditioner也可以应用于真机，但是使用的时候需要小心，使用这个工具不仅仅对使用者起作用，还会影响整个网络。

  ​



## 源代码控制

- [**Git**](http://git-scm.com/)：分布式版本控制系统和源码管理系统，其优点是：快和简单易用。对于新手来说，可在此查看[免费电子书籍](http://git-scm.com/book)。

- [**GitHub**](https://github.com/)：声望日盛的资源分享之地。

- [**BitBucket**](https://bitbucket.org/)：GitHub的替代选择。可以免费建立私有仓库

- [**Git Flow Extensions**](https://github.com/nvie/gitflow)：一个git扩展集合，以图形化客户端来管理资料库。

- [GitDiff](https://github.com/johnno1962/GitDiff)  图形用户界面使git对开发者不显得那么吓人了。而像Tower和SourceTree这样的程序是伟大的，我常常想知道我目前工作的文件中有什么改变，在Xcode的代码编辑器。这个GitDiff插件，使这一切成为可能，多么伟大。

  它是Xcode的代码编辑器的一个微妙的补强，加上了足够的可见信息以了解上次提交以来发生了什么变化。

  ![img](https://camo.githubusercontent.com/c28d1cf0d3b079c807f79cb6deb5785aff28e9be/687474703a2f2f696e6a656374696f6e666f7278636f64652e6a6f686e686f6c6473776f7274682e636f6d2f67697464696666322e706e67)

- **ShowInGithub**

  代码审查是Netguru大神们生活方式的一部分。尽管大部分bug会在此阶段被检查出来，但我们仍然会在使用他人代码的时候发现问题。这个时候，ShowInGithub大显身手的时候到了，只需要按下ctrl+C或ctrl+G，就可以立即打开commit或file页面，同时支持Github和BitBucket，非常棒！

- [gitignore.io](http://www.gitignore.io/)

  我们知道一些文件不应该被提交到资源库，那你如何告诉git提交一个额外的.gitignore文件？我们当然不希望手动做这些细碎又麻烦的事情，运行以下命令：

  ```
  $ gi xcode,objective-c > .gitignore

  ```

  ![img](http://segmentfault.com/img/bVccwH)

- ​

  ​

## 包管理

- [CocoaPods](http://cocoapods.org/) –  管理iOS项目的重要工具。允许你轻松快速地将第三方库集成到你的应用中。它是通过创建另一个静态库工程，然后自动链接到你的工程来实现的。有成千上万个可用的pod，可以轻松地为你的项目增加那些不属于你（或者私有）的第三方库支持。我在我的每个项目里都用了CocoaPods。

- [**HomeBrew**](http://brew.sh/)：OS X上非常出色的包管理工具

- [**Alcatraz**](https://github.com/supermarin/Alcatraz)：开源的Xcode 5包管理器，可以让你发现和安装插件、模板以及配色方案，无需手动复制文件。现已支持Xcode 5。

- ​




## 测试

- [CrashMonkey](https://github.com/mokemokechicken/CrashMonkey)  iOS 平台的 Monkey 测试工具。

- [Remote](https://github.com/johnno1962/Remote)  在 Xcode 内部控制你的 iPhone 来做端到端的测试。

- [ios-driver](http://ios-driver.github.io/ios-driver/index.html)  使用 Selenium / WebDriver 测试任何 iOS 原生，混合或者移动 web 应用。

- [ios-snapshot-test-case](https://github.com/facebook/ios-snapshot-test-case) 使用屏幕快照的 iOS 单元测试。

- [pxctest](http://bit.ly/2gxsq1D) Execute tests in parallel on multiple iOS Simulators.

  [![Build Status](https://camo.githubusercontent.com/4a272db77ea28c12824225014b7fc7070d3ca6e0/68747470733a2f2f7472617669732d63692e6f72672f706c752f707863746573742e7376673f6272616e63683d6d6173746572)](https://travis-ci.org/plu/pxctest)

  [![screencast](https://github.com/plu/pxctest/raw/master/static/screencast.gif?raw=true)](https://github.com/plu/pxctest/blob/master/static/screencast.gif?raw=true)



## XCode

- [**查看项目的’TODO’,’FIXME’等**](https://github.com/trawor/XToDo)

- [Code Pilot](http://codepilot.cc/) 说到Xcode那些炙手可热的插件，很多开发者首先都会想到[Code Pilot](https://github.com/macoscope/CodePilot)。Code Pilot是Xcode 5的一款扩充插件，能够帮助开发者无需鼠标操作，即可在项目中快速方便地查找文件、方法和符号。

- [Backlight-for-XCode](https://github.com/limejelly/Backlight-for-XCode) 高亮当前编辑的行。

- [XCActionBar](https://github.com/pdcgomes/XCActionBar) - Xcode 的 Alfred。

- [AdjustFontSize](https://github.com/zats/AdjustFontSize-Xcode-Plugin) 使用 ⌘ + / ⌘ - 快捷键调整字体大小。

- [CocoaDeveloper Quicklook Plugin](http://kfi-apps.com/plugins/ipaql/)

  ![img](http://segmentfault.com/img/bVccxc)

  该程序是一个Quicklook插件，用以预览app和配置信息。

  你也可以使用iPhone Configuration Utility（[http://support.apple.com/downloads/](http://support.apple.com/downloads/)）来管理你的配置文件。

- Derived Data Exterminator

  当你在编译项目的时候，是否曾为Xcode爆出的某个奇怪的错误绞尽脑汁？我想答案是肯定的，并且我们都明白，其中的一种错误的解决办法就是—删除DerivedData!尽管我们有很多种方法解决这个问题，但Derived Data Exterminator无疑是最便捷的那种。在我们将它集成到Xcode后，就可以一键清理Derived Data。

  ![img](http://mmbiz.qpic.cn/mmbiz/CN8VYJLAIV2e1PZOy16ib4f6DgwSzlXibpnym0ibRN6IbzZb9PIneJVMuM8jgxSicicl2AcMHUQT3pJiapnibSYzCAz8g/640?wx_fmt=jpeg&tp=webp&wxfrom=5&wx_lazy=1)

- [SCXcodeMiniMap](https://github.com/stefanceriu/SCXcodeMiniMap) - SCXcodeMiniMap 为 Xcode 添加了代码地图功能

- [BBUDebuggerTuckAway](https://github.com/neonichu/BBUDebuggerTuckAway)   当你开始编辑的时候帮你隐藏调试器栏的 Xcode 插件。


​       ![img](http://segmentfault.com/img/bVce8Y)

- [XAlign](https://github.com/qfish/XAlign)

  XAlign是一款专门用于代码整理的Xcode插件，其作者为来自Geek Zoo Studio的开发者QFish。XAlign能够对开发者的代码非常快速地进行对齐优化，有“=”、宏定义、属性三种对齐模式。当然，如果默认的对齐风格不是自己喜欢的，开发者还可以自定义或提出issues。

  ![img](http://segmentfault.com/img/bVce8V)

- [Provisioning](https://github.com/chockenberry/Provisioning) 一个查看器插件，用于预览 .mobileprovision 文件。

- [Blade](https://github.com/jondot/blade)  生成 Xcode 需要的 icon 图标的命令行工具

- [CleanHeaders-Xcode](https://github.com/insanoid/CleanHeaders-Xcode) 类似 iSort 的头文件排序和重复消除插件，让你的头文件看起来更加有序。

- [ClangFormat-Xcode](https://github.com/travisjeffery/ClangFormat-Xcode) ClangFormat-Xcode是一款格式化代码工具，能够让开发者使用Clang将代码格式化为LLVM、Google、Chromium、Mozilla或WebKit等格式，其开发者为来自37signals的Travis Jeffery。通过ClangFormat，开发者不仅可以实现对代码的自动或批量格式化，还可以进行自定义配置。

  ![img](http://segmentfault.com/img/bVce8U)

  相关链接：ClangFormat-Xcode的[mobilehub主页](http://mobilehub.io/products/clangformat-xcode)

- [AutoHighlightSymbol](https://github.com/chiahsien/AutoHighlightSymbol) 高亮被选中的符号对应的所有实例。

  ![im](https://github.com/chiahsien/AutoHighlightSymbol/raw/master/screenshot.png)

- [JumpMarks](https://github.com/merrickp/JumpMarks) 使用有序的书签为你的代码做导航。

  ![img](https://github.com/merrickp/JumpMarks/raw/assets/toggle.gif)

- [CopyIssue](https://github.com/hanton/CopyIssue-Xcode-Plugin) 使复制 Xcode issuse 描述更简单。

  ![img](https://github.com/hanton/CopyIssue-Xcode-Plugin/raw/master/screenshots/ScreenShot.png?raw=true)

  ![img](https://github.com/hanton/CopyIssue-Xcode-Plugin/raw/master/screenshots/Step2Alternate.png?raw=true)

- [**Xcode Colors**](https://github.com/robbiehanson/XcodeColors)：为应用调试输出添加有颜色的代码，从而简化调试，可与CocoaLumberjack一同使用。

  ![img](http://www.cocoachina.com/cms/uploads/allimg/140417/4196_140417165641_1.jpg)

- **XCode颜色显示插件[ColorSense](https://github.com/omz/ColorSense-for-Xcode)**

  代码里的那些冷冰冰的颜色数值，到底时什么颜色？如果你经常遇到这个问题，每每不得不运行下模拟器去看看，那么这个插件绝对不容错过。更彪悍的是你甚至可以点击显示的颜色面板，直接通过系统的ColorPicker来自动生成对应颜色代码，再也不用做各种颜色代码转换了！

- [RevealPlugin](https://github.com/shjborage/Reveal-Plugin-for-Xcode)将 Reveal App 和你的项目自动合为一体的 Xcode 插件

- [RealmPlugin](https://realm.io/docs/objc/0.81.0/#xcode-plugin) 生成 Realm 模型的 Xcode 插件




## 命令行

- [**Nomad**](http://nomad-cli.com/)：优秀的iOS开发命令行工具集。具体功能可在其官方网站查看。

- **[iTerm2](https://www.iterm2.com/) – Mac上最好的终端模拟器**

  ![img](http://mmbiz.qpic.cn/mmbiz_png/k0UVxv3BTLIkJcwfeniaXfbAK0ZWqE0RWEo9YPAl9psXqL40P35VSJ345JabxV9Pv4qBFDN4Op3u88jlhrqfwcA/0?tp=webp&wxfrom=5&wx_lazy=1)
  功能强大/外观漂亮/多标签支持/专注的全屏模式/…
  (试一下 option + space, Command + Enter)



- ​




## HTTP/HTTPS抓包工具

- Charles 网络调试神器，可以断点，修改数据，映射网络数据到本地文件，[从入门到精通](http://blog.devtang.com/2015/11/14/charles-introduction/)




## 持续集成

- [**xctool**](https://github.com/facebook/xctool)：xctool是来自Facebook的优秀开发工具，可以让你通过命令行创建和测试你的应用。除了比苹果提供的xcodebuild工具好用外，它的输出可以注入CI软件，因此更具灵活性。

![img](http://www.cocoachina.com/cms/uploads/allimg/140417/4196_140417170932_1.gif)

- [**Jenkins**](http://jenkins-ci.org/)：一个开源的持续集成服务器，配置简单。通过Xcode插件，你可以用Jenkins来测试、签名、创建以及分发应用。Jenkins非常人性化，ANSI彩色输出，这些都是额外的功能。
- [**Xcode bots**](https://developer.apple.com/news/?id=6132013a)：该工具自动化了创建、分析以及测试应用的过程。使用了Mac OS X server和苹果的指令。

​      为了推广Bots，苹果于2013年10月24日向开发者免费发布了[Mac OS X server副本](http://www.macrumors.com/2013/10/24/apple-giving-ios-devs-free-copies-of-os-x-server-to-promote-xcodes-continuous-integration/)。



## 部署

- [Deploymate](http://www.deploymateapp.com/) ($) – 还需要支持iOS4，但是你在用iOS6 SDK编译？当你使用了一些在你的部署目标上不存在的符号时，Deploymate会警告你的。

- [**Nomad Shenzhen + FTP**](https://github.com/nomad/shenzhen)：让创建应用，把应用上传至FTP服务器变得异常简单的CLI工具。

- [Cupertino](https://github.com/nomad/cupertino) – Nomad CLI工具之一，Cupertino为你提供了命令行接口来管理苹果Provisioning Portal上的设备及profile。举例来说，只要键入ios devices:list就可以看到你帐号里的当前设备列表。可以用来自动化许多过程。

- [Hockey App](http://hockeyapp.net/) ($) – 管理你ad-hoc版本发布的不错服务。测试人员可以得到一个链接，无线安装新的测试版本。它还提供了健壮的崩溃报告功能，你可以轻松应对你应用中的崩溃。

- [TestFlight](http://testflightapp.com/) – 一个类似于Hockey App的免费应用。我们使用TestFlight已经取得了很大成功，轻松发布应用，从用户那收集反馈。我唯一希望他们能对这个服务进行收费。它还包括了分析和崩溃报告功能，但我们没有用到那些功能。

- [iOS Simulator Cropper](http://www.curioustimes.de/iphonesimulatorcropper/index.html) – 一个拍模拟器屏幕快照的简单方法，可以选择带或者不带状态栏，带或者不带机器外壳等等。对于App Store或者普通市场上的一些截屏很有用。

- [Status Magic](http://shinydevelopment.com/status-magic/) ($) – 拍出更好的app store截屏图。没有什么比App Store上带有低电量或者低信号标识的截屏图更让你的应用看起来糟糕的了。Status Magic让你充分定制你的状态栏，包括去除一些元素，把时间改成苹果喜欢的“9:41 AM”那样，等等。

- [deliver](https://github.com/fastlane/deliver) 部署截屏，app 元数据和 AppStore app 更新，这一切只需要一个命令就可以搞定

- **Status Barred**

  根据iTunes Connect Guidelines的要求，屏幕截图不应当包含状态栏，这个工具可以帮助我们平滑地去除状态栏，同时支持iPhone和iPad的屏幕截图。这个小应用虽然只做一件事，但是做得很好。

- [Reflector](http://www.airsquirrels.com/reflector/) ($) – 将你的iOS设备通过Air Play镜像到你的Mac上。很适合在你的电脑上做应用演示。

- [RealmPlugin](https://realm.io/docs/objc/0.81.0/#xcode-plugin) 生成 Realm 模型的 Xcode 插件。

- [Expo Sketch](https://sketch.expo.io/)

  在 JS 开发方面我们有 Codepen 和 JSFiddle 进行代码的测试与分享，我们可以直接贴我们的代码然后直接分享一个地址给其他人就可以进行即时的代码分享与演示。
  不过 React Native 方面一直没有一个这样的工具，所以 Expo Sketch 就是这样的背景下产生的。
  主要的功能点如下：

  可以在 web 或者在手机上即时测试你的代码，手机预览直接扫描页面生成的二维码即可。





## 图形图像

- **[Resizer](https://itunes.apple.com/us/app/resizer/id411277085?mt=12)**
  将 Retina 使用的图档（档名为 @2x 或 -hd 的图档）快速且完美地产生普通屏幕的图档尺寸。
- **[LifeView](http://www.zambetti.com/projects/liveview/)**
  透过 Wifi 使用 iPhone 或是 iPad 直接预览电脑画面，方便检视图片在 Retina 屏幕中的效果
- [RTImageAssets](https://github.com/rickytan/RTImageAssets) - 自动生成所需的全部 App 图标的插件。
- [ImageAlpha](http://pngmini.com/) – 一个Mac应用，可以让你将24位带透明度的PNG图转成8位的带alpha通道的PNG图。通常8位PNG图不带有alpha通道，因此如果你的图片可以用8位来表示（比如一个单色的按钮）的话，你可以通过把25位PNG转成8位的来节省很多空间。
- [ImageOptim](http://imageoptim.com/) – 另一个Mac应用，可以压缩PNG图片来节省空间。大多数PNG文件可以省掉几个百分点的大小，有时甚至30%或更多。图片更小意味着应用尺寸更小，运行时加载它们所使用的内存也更小。
- [Prepo](http://wearemothership.com/work/prepo) – 一个Mac上的小应用，可以将图片快速变换为你需要的多个尺寸。只需要拖动一个大图标文件（比如，1024*1024）到Prepo，它就会生成512*512的iTunesArtwork，114*114的 Icon@2x.png，以及其他的尺寸和文件名
- [pngcrush](http://pmt.sourceforge.net/pngcrush/) – 这个实用工具可以压缩解压缩PNG文件，当你想那些App Store上应用里的图片时很有用。只要打开iTunes，查看本地应用列表，对图标右键在Finder中打开。然后打开应用，你可以看到一堆PNG文件，但你没法查看它们。使用了pngcrush你可以将它们全部提取出来，然后用预览来查看。
- [Retini](https://github.com/terwanerik/Retini)  一个超级简单的 Retina（2x，3x）图片转换器。
- [Pixel Winch](http://www.ricciadams.com/projects/pixel-winch) UI没标注肿么办，用直接Pixel Winch自动精确测量 UI 切图之间的距离吧，相比系统手工量方便多了
- [Acorn](http://www.flyingmeat.com/acorn/) ($) – Photoshop的有力竞争者，比ps便宜多了。我发现自己最近用Photoshop越来越少了。该项目在积极的开发维护中。
- [Sketch](http://www.bohemiancoding.com/sketch/) ($) – 一个基于矢量的画图工具，随着屏幕尺寸和像素密度的改变，这个工具越来越有用。只需要设计一次，然后可以根据需要进行缩放。同时还带有一个很强大的导出系统。对于Sketch示例项目，请看[Sketchmine](http://sketchmine.co/)。我的 [screencast on Sketch](http://nsscreencast.com/episodes/079-sketch)上有视频演示。


- [Fontastic Icons for iOS](https://github.com/AlexDenisov/FontasticIcons) – 一个使用图标字体的开源类集合，例如iOS应用中的[Font Awesome](http://fortawesome.github.io/Font-Awesome/)。可以在任何像素维度上快速简便的得到一个图标。由于字体在本质上可以轻松缩放，用这种办法可以很方便的在不同平台使用的图标，而无需根据不同尺寸导出不同的版本。

- [Glypish Link](http://glyphish.com/)

  [![glphy](http://coolshell.cn//wp-content/uploads/2011/08/glphy.jpeg)](http://coolshell.cn//wp-content/uploads/2011/08/glphy.jpeg)

  你可能能从上面的这些图标中看到Flipboard 和 Twitter 在iOS上的应用使用了其中的一些图标。是的，这些个小图标对你的开发很有帮助。作者强烈推荐你花$25去购买 [Glyphish](http://glyphish.com/) 的Pro版。当然啦，你都能花$99/year开发iOS的程序，你还怕花这区区的25刀？

  ​



## 文档
啊哈，文档，每个人最爱的话题。文档很重要，因此请注意一下，我们可以让你生活变得简单一些。

- [appledoc](http://gentlebytes.com/appledoc/) – 想自动生成苹果官方那样的文档吗？不用再找了。自动在你的项目中定义超链接符号，使用特殊格式的代码注释来提取内容。生成正式文档和HTML网页。

- [Dash](http://kapeli.com/dash/) ($) – 一个必须拥有的API文档查看器和代码片段管理器。它很好用，允许你下载并搜索各种语言和框架的API文档，而且速度很快。最快访问文档的方式。为了使搜索更快，我[把Dash和Alfred集成起来使用](http://joeworkman.net/blog/post-30037947509)。

- [Dash-Plugin-for-Xcode](https://github.com/omz/Dash-Plugin-for-Xcode)

  Dash Xcode plugin是Bogdan Popescu开发的一款集成了Dash文档查看器应用的Xcode插件，允许开发者在使用Option-Click或作用相同的快捷键操作查看当前文本的相关文档时，用Dash代替Xcode的文档查看器。

  ![img](http://segmentfault.com/img/bVce80)




## 数据库

- [Mogenerator](http://rentzsch.github.com/mogenerator/) –  一个超有用的工具，在你的Core Data模型中生成NSManagedObjects智能子类。有些人使用Xcode完成这功能，通过手动子类化或者创建分类来为模型增加逻辑。Mogenerator作为预编译脚本运行来生成你可以使用的子类。它通过创建带有下划线的版本(_User)以及正常你可以修改的版本(User)来实现。

- [Base](http://menial.co.uk/software/base/) ($) – 你肯定会需要查看你的Core Data sqlite数据库来检查发生了什么。你可以使用sqlite3命令行工具，但Base给了你一个方便查看的GUI浏览器。当你看到Core Data为你创建的数据库schema时你可不要吐哦。

- [Core Data Editor](http://christian-kienle.de/CoreDataEditor) ($) -对于一些更高级的数据分析、发掘以及修改，你可以使用Core Data Editor。这个应用了解Core Data，因此你是在直接和实体打交道，而不是数据库行。

- SQLite Professional

  从名字上就能看出这是个SQLite工具，功能齐全。

  ![img](http://upload-images.jianshu.io/upload_images/1475667-6b14ac111a0941e7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- SQLiteManager

  这也是个Sqlite数据库管理工具。和SQLite Professional相比功能一样，就看你喜欢哪个了。

  ![img](http://upload-images.jianshu.io/upload_images/1475667-e23b83eebd5c888a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- Realm Browser

  如果你使用的是Realm数据库的话，那么Realm Browser也是不可或缺的一款工具。直接看名字这个是Realm可视化界面。在这里说一句题外话:Realm数据库确实强大，方便。如果大家有兴趣可以去深入了解。

- [Liya](https://itunes.apple.com/us/app/liya/id455484422?ls=1&mt=12)

  ![img](http://segmentfault.com/img/bVccwK)

  如果没有合适的工具，那么查看Core Data records会是一件非常痛苦的事情，更糟糕的是Xcode并没有为你提供一个恰当的方法。Liya可能并不是那么迷人，但它确实是一款非常轻量级的的工具，可以在不锁定正在使用的数据库的情况下很好地工作。简单使用SimPholder查找应用的文档文件夹，定位sqlite数据库文件，然后开始浏览。

  Liya允许用户在单个可视化界面同时访问三个数据库系统。Liya可以以同样的方式访问MySQL、PostgreSQL以及SQLite3数据库。通过一个3-panel进行展示，一个展示选择的数据库，一个用以编辑table structure，另一个用以编辑表的内容。Liya可使用多个窗口同时在三种系统中访问数据库，每个窗口展示单个数据库的内容。Liya还可以通过拖放操作把数据从一个数据库移植另一个。你也可以从一个数据库输出数据进行备份。




## 设计

- [Mocks](http://celestialteapot.com/mocks) ($) – 一个简单应用的快速创建iOS应用原型的工具。自带一些默认控件，你可以快速搭建原型。
- [Briefs](http://giveabrief.com/) ($) – 一个很有用的应用，可以让你创建应用原型，将原型连起来形成交互。你可以部署到真实设备上，看看在你手上是什么样的感觉。
- [UMLet](http://umlet.com/) 简单轻量级的UML设计工具，推荐




## 编辑器

- [AppCode](http://jetbrains.com/objc) – Jetbrains（ReSharper for .NET的制作公司）的一款功能全面的IDE。强大的重构工具和功能可以帮助你更快地写代码。快速识别死代码，当你使用了相关代码时自动插入#import语句，轻松选取变量、方法以及类。我唯一希望的是它能成为Xcode的一个插件。
- [Vim](http://www.vim.org/) – 等一下， vim？真的么？确实是真的，有人在vim里做所有的Objective-C开发。我并不是其中之一，但我喜欢用vim开发ruby。就因为如此，我很喜欢…
- [Xvim](https://github.com/JugglerShu/XVim) –  一个Xcode插件，能使用vim中的keybindings。
- [**Textmate**](http://macromates.com/)：Mac OS X上一个可高度自定义的编辑器，尤其在我想做出一个快速改变但又不想等待Xcode加载的时候。该工具目前已经开源（[https://github.com/textmate/textmate](https://github.com/textmate/textmate)）。


- [**Sublime Text**](http://www.sublimetext.com/) ：Mac OS X上另一款非常受欢迎的轻量级，可高度自定义的编辑器。 

- [Linguan](http://www.peerassembly.com/linguan.html)

  开发者都希望把自己的应用推广到世界各地，这时候本地化就变得非常重要。你可能需要让别人分担翻译的工作，但是Xcode一直不善于让别人牵涉其中。你不得不生成一个string文件，不过这种做法不利于归并内容，Linguan的出现正是为了解决这个问题。

  Linguan可以简化Mac和iOS app本地化的过程，为Xcode项目中所有strings文件提供了智能化的编辑器。在你复制tokens或者丢失翻译的时候，Linguan可给你一定提醒。同时，你可以输出针对某种语言丢失的tokens或者通过邮件发送给你的译者，译者也可以使用Linguan完成翻译或者使用他们的文本编辑器。




## Markdown编辑器

对于熟悉Markdown的人来说，Mou是一款不错的文本编辑器（Mac平台）。相比同类型产品，Mou 在功能性和易用性上都有众多特色，在其简单的界面之后，不仅拥有自定义样式、增量搜索、中文字体“漂移”优化，还支持终端命令行启动、内容发布、竖版文字布局，甚至还可以作为任务列表使用，其Markdown双栏布局的实时预览和同步滚动功能更是被众多应用借鉴和采用。
可惜的是Mou已不再支持macOS Sierra(10.12.x)已上的系统，所以在这里推荐其他几款支持Markdown语法的软件。

- [Mou](http://25.io/mou/download/Mou.zip)
- [MacDown](http://macdown.uranusjr.com/)
- [Typora](https://typora.io/)
- [MaHua在线编辑器](http://mahua.jser.me/)




## 其它

- [**Transmit **](http://panic.com/transmit/)：一个Mac OS X 上FTP客户端，有着非常漂亮的用户界面和有用的功能。

- Review Command AppStore应用程序评分跟踪软件 

  ![[Mac] AppStore应用程序评分跟踪软件 ： Review Command](http://77g4f4.com1.z0.glb.clouddn.com/wp-content/uploads/001-518.jpg)

- Automator

  哈哈，这个机器人熟悉吧。系统自带的一个，这个小机器人用处可是非常大的，它能帮你完成各种琐碎，简单重复的工作。就例如写这篇文章需要的图片都是从应用程序中找出来的，打多少.icns格式的，里面有很多张，而且尺寸有大有小。于是就建立这么一个流程:输入icns格式图片->格式转换成.png->调整大小->输出。如下图

  ![img](http://upload-images.jianshu.io/upload_images/1475667-70e4c9c9d1d01de2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

  这样就把事情完成了。

