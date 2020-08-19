 Loongson .NET Core Home
===========================

The [gsvm/loongson-dotnet](https://github.com/gsvm/loongson-dotnet) repository is a good starting point for Loongson's port of .NET Core.

We hope to implement .NET Core 3.1 of Loongson/MIPS Port first, then upgrade to upstream [dotnet/runtime](https://github.com/dotnet/runtime) .

This repository may be temporary, but may exist for a long time. Our hope is to merge into upstream.


## Current Status

Nearly all tests in [CoreCLR](https://github.com/gsvm/coreclr) have been passed. We are debugging tests in [CoreFX](https://github.com/gsvm/corefx) and [ASP.NET Core](https://github.com/dotnet/aspnetcore), and tests with various parameters. 


## How to Use MIPS Port of .NET Core

It has not yet reached the state of use. We released [Early-Access (EA) builds](https://github.com/gsvm/loongson-dotnet/releases)  of .NET Core MIPS64 Port. EA Build is not for production use. EA build has many bugs and is very unstable.


## How to Engage, Contribute and Provide Feedback

We encourage contributions, both issues and PRs. All contributions and suggestions are greatly welcomed. If you have any problems or want any support, feel free to file an issue or contact us via email to aoqi@loongson.cn.

## Useful Link

[Who is Loongson](http://www.loongson.cn/)

[Open-sourcing CoreCLR MIPS64 Port](https://github.com/dotnet/runtime/issues/38069)

[Guide for porting .NET to a new processor architecture](https://github.com/dotnet/runtime/blob/master/docs/design/coreclr/botr/guide-for-porting.md)

["arch-mips64" label](https://github.com/dotnet/runtime/labels/arch-mips64)

[Debugging CoreCLR on Loongson (Chinese)](http://ask.loongnix.org/?/article/689)
