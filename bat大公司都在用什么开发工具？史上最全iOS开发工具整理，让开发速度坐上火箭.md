史上最全bat大公司iOS开发工具整理，让开发速度坐上火箭

iOS essential tools to skyrocket your development. one command to install.





## 代码自动生成

- 代码片段

- [**快速Add #import**](https://github.com/markohlebar/Peckham) 不用自己写import，当引用一个类时，就会自动import头文件

- ### [Auto-Importer-for-Xcode](https://github.com/citrusbyte/Auto-Importer-for-Xcode)



## 质量保证

- [infer](https://github.com/facebook/infer) Facebook 静态分析利器浅析
- oclint 
- [Slender](http://dragonforged.com/slender/) ($)  一个很棒的应用，可以分析你的应用，找出各种问题，比如缺少视网膜屏的图片，没用到的图- 片，能压缩的图片。使用Slender去除掉那些没用的图片，可以为你的iPhone应用节省好多空间。
- [Apple如何知道你用私有API](http://www.csdn.net/article/2012-02-10/311678)
- [私有API扫描工具appScanner](https://github.com/ChimpStudios/App-Scanner) 
- ​



## 源代码控制

- [CocoaPods](http://cocoapods.org/) –  管理iOS项目的重要工具。允许你轻松快速地将第三方库集成到你的应用中。它是通过创建另一个静态库工程，然后自动链接到你的工程来实现的。有成千上万个可用的pod，可以轻松地为你的项目增加那些不属于你（或者私有）的第三方库支持。我在我的每个项目里都用了CocoaPods。



## 命令行







## 诊断&调试
有时候我们正在开发应用，我们想更好的了解到底发生了什么，修bug或者改善性能。

- **[injectionforxcode](https://github.com/johnno1962/injectionforxcode)** 调试利器 
- [Pony Debugger](https://github.com/square/PonyDebugger) – 另一个你可以嵌入一个库到你调试版本中的工具，Pony Debugger实际上使用了Chrome的开发工具来查看设备上发出的网络请求，还有一个基本的Core Data浏览器。很难描述，请看我的[screencast on Pony Debugger](http://nsscreencast.com/episodes/54-pony-debugger)吧。
- [Runscope](http://runscope.com/) ($) – Runscope是一个网络服务，可以捕捉请求，记录日志，给你关于你的API的有用数据。因为它是个HTTP通道API， 搭建简单，你只需要更换你的主机名就行了。
- [SimPholders](http://simpholders.com/) – 快速简单的访问你的模拟器文件夹。根据iOS版本来浏览，然后是应用名，可以直接在Finder中打开文件夹。
- [Spark Inspector](http://sparkinspector.com/) –  在调试模式运行你的应用时，可以用3D来展示调试你的视图层次。这个应用你真的要看到了才会真正明白它的价值。它能帮助你了解你的应用是由哪些视图组成的。它还带有一个通知中心监视器，你可以轻松看到发出了哪些NSNotification，谁在观察它们。另一个监控NSNotification的应用是[Reveal](http://revealapp.com/)。
- ​



## HTTP/HTTPS抓包工具
- Charles 网络调试神器，可以断点，修改数据，映射网络数据到本地文件，[从入门到精通](http://blog.devtang.com/2015/11/14/charles-introduction/)




## 图片处理

- **[Resizer](https://itunes.apple.com/us/app/resizer/id411277085?mt=12)**
  将 Retina 使用的图档（档名为 @2x 或 -hd 的图档）快速且完美地产生普通屏幕的图档尺寸。

- **[LifeView](http://www.zambetti.com/projects/liveview/)**
  透过 Wifi 使用 iPhone 或是 iPad 直接预览电脑画面，方便检视图片在 Retina 屏幕中的效果

- [ImageAlpha](http://pngmini.com/) – 一个Mac应用，可以让你将24位带透明度的PNG图转成8位的带alpha通道的PNG图。通常8位PNG图不带有alpha通道，因此如果你的图片可以用8位来表示（比如一个单色的按钮）的话，你可以通过把25位PNG转成8位的来节省很多空间。
- [ImageOptim](http://imageoptim.com/) – 另一个Mac应用，可以压缩PNG图片来节省空间。大多数PNG文件可以省掉几个百分点的大小，有时甚至30%或更多。图片更小意味着应用尺寸更小，运行时加载它们所使用的内存也更小。
- [Prepo](http://wearemothership.com/work/prepo) – 一个Mac上的小应用，可以将图片快速变换为你需要的多个尺寸。只需要拖动一个大图标文件（比如，1024*1024）到Prepo，它就会生成512*512的iTunesArtwork，114*114的 Icon@2x.png，以及其他的尺寸和文件名

- [pngcrush](http://pmt.sourceforge.net/pngcrush/) – 这个实用工具可以压缩解压缩PNG文件，当你想那些App Store上应用里的图片时很有用。只要打开iTunes，查看本地应用列表，对图标右键在Finder中打开。然后打开应用，你可以看到一堆PNG文件，但你没法查看它们。使用了pngcrush你可以将它们全部提取出来，然后用预览来查看。




## 文档
啊哈，文档，每个人最爱的话题。文档很重要，因此请注意一下，我们可以让你生活变得简单一些。

- [appledoc](http://gentlebytes.com/appledoc/) – 想自动生成苹果官方那样的文档吗？不用再找了。自动在你的项目中定义超链接符号，使用特殊格式的代码注释来提取内容。生成正式文档和HTML网页。

- [Dash](http://kapeli.com/dash/) ($) – 一个必须拥有的API文档查看器和代码片段管理器。它很好用，允许你下载并搜索各种语言和框架的API文档，而且速度很快。最快访问文档的方式。为了使搜索更快，我[把Dash和Alfred集成起来使用](http://joeworkman.net/blog/post-30037947509)。



## 数据库
- [Mogenerator](http://rentzsch.github.com/mogenerator/) –  一个超有用的工具，在你的Core Data模型中生成NSManagedObjects智能子类。有些人使用Xcode完成这功能，通过手动子类化或者创建分类来为模型增加逻辑。Mogenerator作为预编译脚本运行来生成你可以使用的子类。它通过创建带有下划线的版本(_User)以及正常你可以修改的版本(User)来实现。

- [Base](http://menial.co.uk/software/base/) ($) – 你肯定会需要查看你的Core Data sqlite数据库来检查发生了什么。你可以使用sqlite3命令行工具，但Base给了你一个方便查看的GUI浏览器。当你看到Core Data为你创建的数据库schema时你可不要吐哦。

- [Core Data Editor](http://christian-kienle.de/CoreDataEditor) ($) -对于一些更高级的数据分析、发掘以及修改，你可以使用Core Data Editor。这个应用了解Core Data，因此你是在直接和实体打交道，而不是数据库行。



## 部署
- [Deploymate](http://www.deploymateapp.com/) ($) – 还需要支持iOS4，但是你在用iOS6 SDK编译？当你使用了一些在你的部署目标上不存在的符号时，Deploymate会警告你的。
- [Cupertino](https://github.com/nomad/cupertino) – Nomad CLI工具之一，Cupertino为你提供了命令行接口来管理苹果Provisioning Portal上的设备及profile。举例来说，只要键入ios devices:list就可以看到你帐号里的当前设备列表。可以用来自动化许多过程。

- [Hockey App](http://hockeyapp.net/) ($) – 管理你ad-hoc版本发布的不错服务。测试人员可以得到一个链接，无线安装新的测试版本。它还提供了健壮的崩溃报告功能，你可以轻松应对你应用中的崩溃。
- [TestFlight](http://testflightapp.com/) – 一个类似于Hockey App的免费应用。我们使用TestFlight已经取得了很大成功，轻松发布应用，从用户那收集反馈。我唯一希望他们能对这个服务进行收费。它还包括了分析和崩溃报告功能，但我们没有用到那些功能。
- [iOS Simulator Cropper](http://www.curioustimes.de/iphonesimulatorcropper/index.html) – 一个拍模拟器屏幕快照的简单方法，可以选择带或者不带状态栏，带或者不带机器外壳等等。对于App Store或者普通市场上的一些截屏很有用。
- [Status Magic](http://shinydevelopment.com/status-magic/) ($) – 拍出更好的app store截屏图。没有什么比App Store上带有低电量或者低信号标识的截屏图更让你的应用看起来糟糕的了。Status Magic让你充分定制你的状态栏，包括去除一些元素，把时间改成苹果喜欢的“9:41 AM”那样，等等。

- [Reflector](http://www.airsquirrels.com/reflector/) ($) – 将你的iOS设备通过Air Play镜像到你的Mac上。很适合在你的电脑上做应用演示。



## 设计

- [Mocks](http://celestialteapot.com/mocks) ($) – 一个简单应用的快速创建iOS应用原型的工具。自带一些默认控件，你可以快速搭建原型。
- [Briefs](http://giveabrief.com/) ($) – 一个很有用的应用，可以让你创建应用原型，将原型连起来形成交互。你可以部署到真实设备上，看看在你手上是什么样的感觉。
- [Acorn](http://www.flyingmeat.com/acorn/) ($) – Photoshop的有力竞争者，比ps便宜多了。我发现自己最近用Photoshop越来越少了。该项目在积极的开发维护中。
- [Sketch](http://www.bohemiancoding.com/sketch/) ($) – 一个基于矢量的画图工具，随着屏幕尺寸和像素密度的改变，这个工具越来越有用。只需要设计一次，然后可以根据需要进行缩放。同时还带有一个很强大的导出系统。对于Sketch示例项目，请看[Sketchmine](http://sketchmine.co/)。我的 [screencast on Sketch](http://nsscreencast.com/episodes/079-sketch)上有视频演示。


- [Fontastic Icons for iOS](https://github.com/AlexDenisov/FontasticIcons) – 一个使用图标字体的开源类集合，例如iOS应用中的[Font Awesome](http://fortawesome.github.io/Font-Awesome/)。可以在任何像素维度上快速简便的得到一个图标。由于字体在本质上可以轻松缩放，用这种办法可以很方便的在不同平台使用的图标，而无需根据不同尺寸导出不同的版本。

  ​

## 代码编辑器

- [AppCode](http://jetbrains.com/objc) – Jetbrains（ReSharper for .NET的制作公司）的一款功能全面的IDE。强大的重构工具和功能可以帮助你更快地写代码。快速识别死代码，当你使用了相关代码时自动插入#import语句，轻松选取变量、方法以及类。我唯一希望的是它能成为Xcode的一个插件。
- [Vim](http://www.vim.org/) – 等一下， vim？真的么？确实是真的，有人在vim里做所有的Objective-C开发。我并不是其中之一，但我喜欢用vim开发ruby。就因为如此，我很喜欢…
- [Xvim](https://github.com/JugglerShu/XVim) –  一个Xcode插件，能使用vim中的keybindings。




## 其它编辑器

- sublime 




## Markdown编辑器

对于熟悉Markdown的人来说，Mou是一款不错的文本编辑器（Mac平台）。相比同类型产品，Mou 在功能性和易用性上都有众多特色，在其简单的界面之后，不仅拥有自定义样式、增量搜索、中文字体“漂移”优化，还支持终端命令行启动、内容发布、竖版文字布局，甚至还可以作为任务列表使用，其Markdown双栏布局的实时预览和同步滚动功能更是被众多应用借鉴和采用。
可惜的是Mou已不再支持macOS Sierra(10.12.x)已上的系统，所以在这里推荐其他几款支持Markdown语法的软件。

- [Mou](http://25.io/mou/download/Mou.zip)

- [MacDown](http://macdown.uranusjr.com/)

- [Typora](https://typora.io/)

- [MaHua在线编辑器](http://mahua.jser.me/)