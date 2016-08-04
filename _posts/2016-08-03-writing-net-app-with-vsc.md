---
title:  "Writing .NET Applications With Visual Studio Code"
category: Development
date: 2016-07-27 00:00:00
banner_feature_image: writing-net-app-with-vsc-banner-feature.jpg
banner_image: https://www.codeschool.com/blog/2016/07/27/writing-net-applications-with-visual-studio-code/banner.jpg
tags: .net
---
If you ask any .NET developers about their favorite part of building .NET apps, they’ll likely talk about the tooling.
Mature tooling is an extremely powerful and useful thing. The main tool used for development in .NET over the last 15 years has been the IDE Visual Studio, but there are a few other tools you can use to write .NET application code.

## Terminal and Code Editors
Like most programming, the minimum requirement for writing code is just an application that you can type text into and save with the right file extension. On OS X or Linux this could be a Terminal window, and on Windows you could use a program like Powershell. Once you’ve installed [.NET Core][], creating and running a project only takes a few quick commands:

```
dotnet new
dotnet restore
dotnet run
```

These commands will create the project, restore its packages, and run the project. That’s it — you’ve just made your first working .NET console application that says “Hello World.”

That’s all well and good, but what if you want more than a simple “Hello World” console app? Perhaps something like a web application? Instead of dotnet new, we’ll use `dotnet new -t web`, which tells dotnet we want our new project to use the “web” template. With this, you have a complete working MVC application with home, about, and contact pages.

If you weren’t using a full IDE, you might be using a program like VIM, Emacs, Notepad++, or Sublime Text to write code, but I’d like to recommend [Visual Studio Code][] (not to be confused with Visual Studio, which is a full-blown IDE).

{% include image.html src="https://www.codeschool.com/blog/2016/07/27/writing-net-applications-with-visual-studio-code/1.png" %}

Visual Studio Code has a lot of the features you’d expect in an IDE while remaining a lightweight code editor. You’ll notice on the left side you have your entire working directory, search functionality, source control, debugger, and extensions. This goes even further with support for IntelliSense, Peek, and similar functionality that helps with code discovery. For example, Peek lets us look into a method at the point we’re calling it — without losing our spot.

{% include image.html src="https://www.codeschool.com/blog/2016/07/27/writing-net-applications-with-visual-studio-code/2.png" %}

IntelliSense works well for code discovery as well. IntelliSense actually compiles behind the scenes to be able to tell you everything that’s available, not just what you use commonly or have used before. It also shows a description of what each method does, so you can make sure you’re picking the right one from a list.

{% include image.html src="https://www.codeschool.com/blog/2016/07/27/writing-net-applications-with-visual-studio-code/3.png" %}

Visual Studio Code even goes one step further in running code analytics to locate issues in your code that make it less clear, perform worse, or follow bad practices (even if that code technically compiles and works). For example, the class file in the screenshot below has a number of unused `using` directives. These create clutter, so Visual Studio Code was kind enough to underline them for us. When you mouse over them, they’ll say “Unnecessary using directive” so you know what action to take. As an added bonus, if you click on the little lightbulb icon, it will give you the option to just have Visual Studio Code remove all the unnecessary `using` directives from the file. This will also handle a lot of things, like unreachable code, conditions that are always true, if/else conditions that could be switch/case statements, and more.

{% include image.html src="https://www.codeschool.com/blog/2016/07/27/writing-net-applications-with-visual-studio-code/4.png" %}

These are just some of the benefits Visual Studio Code offers. If you’d prefer to stay away from a larger IDE, you can still develop pretty effectively using just Terminal and a good code editor like Visual Studio Code.

After you’ve finished playing our new [.NET MVC course][], Try .NET MVC, and viewing the [Watch Us Build][] screencast, you should try downloading Visual Studio Code and building a .NET application. If you’ve got another editor of choice, let us know in the comments section below!

[.NET Core]: https://www.microsoft.com/net/core
[Visual Studio Code]: https://code.visualstudio.com/
[.NET MVC course]: https://www.codeschool.com/courses/try-net-mvc
[Watch Us Build]: https://www.codeschool.com/screencasts/build-a-net-mvc-app
