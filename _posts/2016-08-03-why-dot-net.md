---
title:  "Why .NET?"
category: Development
tags: .net
date: 2016-07-20 00:00:00
banner_feature_image: why-net-banner-feature.png
banner_image: why-net-banner.png
---

We’re excited to announce we recently launched our first [.NET course][], Try .NET MVC, kicking off our new .NET Path!
This free course is a short introduction to Microsoft’s ASP.NET MVC framework for building web applications. Historically, many companies have built their entire web infrastructure on ASP.NET MVC, and it’s recently gotten more traction with startups and open-source communities. Today, I’ll talk about some of the reasons you might choose to build your applications with .NET.

## Where Can I Use NET?
One of the things that makes developing with .NET so attractive is that it’s one of the few frameworks that runs on just about anything you can think of — both from a hardware and software standpoint.

For example, the [NetDunio][] project board runs .NET Embedded, and it has about as much power as a budget PC from the early ’90s. On the other end of the spectrum, .NET is also used in aviation training devices made using Lockheed Martin’s [Prepar3D][]. Pretty much any sort of hardware between can run it as well.

{% include image.html alt="A microcontroller board and a large computer station" image="why-net-1.jpg" %}

## What Can I Make With .NET?
Web applications are just one way you can use .NET. It also works great for just about any type of project you might consider, from Massively Multiplayer [Space Simulation][] to internal systems in your [car][].

## Where Can I Create .NET Applications?
While you’ve been able to write .NET on almost any platform for years, it wasn’t without its headaches for those using OS X and Linux. Luckily, with the creation of .NET Core, you can write, compile, and run .NET applications on Windows, OS X, and Linux just as easily as any other language out there, and there’s even a powerful cross-platform IDE called Visual Studio Code that’s quickly becoming an indispensable tool for .NET developers.
{% include image.html alt="Windows, OS X, and Linux" src="https://www.codeschool.com/blog/2016/07/20/why-net/2.png" %}

## Performance
Another common concern people have when deciding what technologies to invest time in learning is their performance and scalability. While historically .NET wasn’t known for its performance, .NET Core is making waves. Microsoft’s Scott Hanselman reported the below benchmarks at DevNation 2016 — complete with the [source code][] to run, tweak, and benchmark for yourself. (Note: .NET Core outperformed the old .NET Framework by over 2300%.)

{% include image.html alt=".NET Core can process millions more requests per second than Java Servlet, Go, and Node.js" src="https://www.codeschool.com/blog/2016/07/20/why-net/3.png" %}

## Open Source
While the .NET framework was closed source for many years, Microsoft started open-sourcing parts of it in 2008, and in 2014 they created an independent organization called the .NET Foundation to take over developing .NET in the open. They moved their source code over to GitHub and changed the licensing to be more relaxed using licenses, such as MIT and Apache, on many of their projects. They’re actively accepting pull requests, user issues, discussing issues, etc., and it is an excellent example of how open source is meant to work.

{% include image.html alt=".NET Foundation" src="https://www.codeschool.com/blog/2016/07/20/why-net/4.png" %}

## Community and Documentation
One thing .NET has really benefitted from is the size of its community and the quality of documentation and information available. ASP.NET famously had dozens of books published on it before it even came out!

You can drill into the code itself in GitHub and read up on how each and every piece of the codebase works, as well as how to use every little piece of the framework on MSDN. You also have tutorials, blogs, and example projects available to help you from your very first Hello World console application all the way to developing advanced artificial intelligences, simulations, and creating your own games utilizing motion controls and virtual reality.

If you are ever stumped or trying to figure out how to accomplish something, likely someone somewhere has taken the time to document it to help you solve your problem. If not, there are communities like Stack Overflow, Slack groups, and local .NET user groups that can usually help come up with ideas on how to tackle your problem.

## Maturity of Tooling
.NET also has some of the best tooling available. Most frameworks only allow you to use them with a single language — Ruby on Rails uses Ruby, Django uses Python, Node.js and ReactJS use JavaScript, etc. If you like the framework but not the language, that’s just too bad. With .NET, on the other hand, you can use the same framework and develop using languages like C#, VB.NET, F#, and C++. (At the time of this post, there are over 35 languages compatible with .NET, including implementations of Ruby, Python, JavaScript, PHP, and Java.)

In addition to this, Microsoft invests heavily in making sure it has some of the best tools available to developers. The Community version of Visual Studio offers auto correction, IntelliSense, debugging, built-in code testing and analytics, etc. It also has built-in database support (so you can set up, configure, make changes to, and run T-SQL all from within the application) and includes source controller functionality for TFS and Git (among other things) with an absurd level of extensions readily available to expand its functionality in any way you see fit. Tools like Visual Studio are one of the things that really give you an edge in .NET versus other frameworks.

We’ve touched on some of the big reasons here that we think you should give .NET a shot if you’ve looked past it before, and we think our [free Try .NET MVC course][] is the perfect way to get started. Let us know what you think in the comments below!

[.NET course]: https://www.codeschool.com/courses/try-net-mvc
[NetDunio]: http://www.netduino.com/
[Prepar3D]: http://prepar3d.com/
[Space Simulation]: https://www.ageofascent.com/
[car]: http://www.ford.com/technology/sync/
[source code]: https://github.com/aspnet/benchmarks
[free Try .NET MVC course]: https://www.codeschool.com/courses/try-net-mvc
