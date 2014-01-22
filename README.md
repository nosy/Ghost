# [鬼](https://github.com/TryGhost/Ghost) [![Build Status](https://travis-ci.org/TryGhost/Ghost.png?branch=master)](https://travis-ci.org/TryGhost/Ghost)

Ghost is a free, open, simple blogging platform that's available to anyone who wants to use it. Lovingly created and maintained by [John O'Nolan](http://twitter.com/JohnONolan) + [Hannah Wolfe](http://twitter.com/ErisDS) + an amazing group of [contributors](https://github.com/TryGhost/Ghost/contributors).

Visit the project's website at <http://ghost.org>!

Full documentation is available at <http://docs.ghost.org>.

## 参与文库建设

Want to report a bug, request a feature, or help us build or translate Ghost? Check out our in depth guide to [Contributing to Ghost](https://github.com/TryGhost/Ghost/blob/master/CONTRIBUTING.md). We need all the help we can get! You can also join in with our [community](https://github.com/TryGhost/Ghost#community) to keep up-to-date and meet other Ghosters.



## 入门

There are **two** main ways to get started with Ghost, take care to use the method which best suits your needs.

**Please note** - the downloadable zip files we provide on [Ghost.org](http://ghost.org/download) are pre-built packages designed for getting started quickly. Cloning from the git repository requires you to install several dependencies and build the assets yourself. 

### 博主入门指南

If you just want to get a Ghost blog running in the fastest time possible, this method is for you.

For detailed instructions for various platforms visit the [Ghost Installation Guide](http://docs.ghost.org/installation/). If you get stuck, help is available on [our forum](http://ghost.org/forum/).

1. 安装 [Node.js](http://nodejs.org) - 鬼需要 **Node v0.10.***
1. 从[Ghost.org](http://ghost.org/download)下载最新的幽灵包 . 
   **如果你克隆了GitHub的库，您应该遵循[开发者](https://github.com/TryGhost/Ghost#getting-started-guide-for-developers)说明。**
1. 创建一个要在其中运行代码的新目录，并解压包到该位置。
1. 启动终端（或在Windows中的node命令提示符），并更改目录到Ghost应用程序的根 (config.example.js 和 index.js所在的位置)
1. 运行 `npm install --production` 安装node依赖包. 如果在这步看到 `error Error: ENOENT`，确定你是否在应用目录并再试一次。
1. 启动幽灵, 运行 `npm start`
1. 在浏览器中访问 `http://localhost:2368/` 并去 `http://localhost:2368/ghost` 页登录

查看[文档](http://docs.ghost.org/)获得更详细的说明, 或如果您遇到问题，通过[论坛](http://ghost.org/forum)取得联系。



### 开发人员入门指南

If you're a theme, app or core developer, or someone comfortable getting up and running from a `git clone`, this method is for you.

If you clone the GitHub repository, you will need to build a number of assets, such as SASS and JavaScript templates. This requires you to have Ruby and a number of other pre-requisites.
Full instructions can be found in the [Contributing Guide](https://github.com/TryGhost/Ghost/blob/master/CONTRIBUTING.md) under the heading "[Working on Ghost Core](https://github.com/TryGhost/Ghost/blob/master/CONTRIBUTING.md#working-on-ghost-core)".

Check out the [Documentation](http://docs.ghost.org/) for more detailed instructions, or get in touch via the [forum](http://ghost.org/forum) if you get stuck.

### 同步更新

Documentation on updating can be found in the [Ghost Guide](http://docs.ghost.org/installation/upgrading/)

### 第一时间登录

Once you have the Ghost server up and running, you should be able to navigate to `http://localhost:2368/ghost/` from a web browser, where you will be prompted for a login.

1.  Click on the "register new user" link
2.  Enter your user details
3.  Return to the login screen and use those details to log in.

Note - this is still very alpha. Not everything works yet.


## 社区

Keep track of Ghost development and Ghost community activity.

* Follow Ghost on [Twitter](http://twitter.com/TryGhost), [Facebook](http://facebook.com/tryghostapp) and [Google+](https://plus.google.com/114465948129362706086).
* Read and subscribe to the [The Official Ghost Blog](http://blog.ghost.org).
* Join in discussions on the [Ghost Forum](http://ghost.org/forum/)
* Chat with Ghost developers on IRC. We're on `irc.freenode.net`, in the `#Ghost` channel. We have a public meeting every Tuesday at 5:30pm London time.


## 版本

For transparency and insight into our release cycle, and for striving to maintain backward compatibility, Ghost will be maintained according to the [Semantic Versioning](http://semver.org/) guidelines as much as possible.

Releases will be numbered with the following format:

`<major>.<minor>.<patch>-<build>`

Constructed with the following guidelines:

* A new *major* release indicates a large change where backwards compatibility is broken.
* A new *minor* release indicates a normal change that maintains backwards compatibility.
* A new *patch* release indicates a bugfix or small change which does not affect compatibility.
* A new *build* release indicates this is a pre-release of the version.


## 版权及许可

Copyright (C) 2014 The Ghost Foundation - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
