# Wiki

**Note**. This sample uses preview features of C# 9 that is only available on .NET 5 SDK Preview 7. Since this preview has not been released yet, download it from the nightly build [here](https://github.com/dotnet/installer).

This is a Single File Application (SFA) that provide wiki functionality.

- It supports markdown
- You can rename pages
- It is stored using LiteDB
- It has a nice markdown editor

All the code is contained within `Program.cs`.

Please be noted that SFA is a very limited approach in web system development. It is really fun for quick hacking but as of now, there is a lot of nice functionality such as Model Binding that is not available for this style of development.

Used libraries:

* Storage - [LiteDB](https://github.com/mbdavid/LiteDB).
* Framework - [FeatherHttp](https://github.com/featherhttp/framework).
* Text Template - [Scriban](https://github.com/lunet-io/scriban).
* Markdown Support - [Markdig](https://github.com/lunet-io/markdig).
* Validation - [FluentValidation](https://github.com/FluentValidation/FluentValidation).
* Html Generation - [HtmlBuilders](https://github.com/amoerie/HtmlBuilders).
* Markdown Editor - [EasyMDE](https://github.com/Ionaru/easy-markdown-editor).
* Sanitizing Input - [HtmlSanitizer](https://github.com/mganss/HtmlSanitizer).