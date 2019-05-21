<h1 align="center">Jetpack Compose Playground</h1>

[![jCenter](https://img.shields.io/badge/MIT-green.svg)](https://github.com/Foso/Jetpack-Compose-Playground/blob/master/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![All Contributors](https://img.shields.io/badge/all_contributors-1-range.svg?style=flat-square)](#contributors)
  <a href="https://twitter.com/intent/tweet?text=Hey, check out KotlinReactNativeMpp https://github.com/Foso/KotlinReactNativeMpp via @jklingenberg_ #Android 
"><img src="https://img.shields.io/twitter/url/https/github.com/angular-medellin/meetup.svg?style=social" alt="Tweet"></a>

> A Jetpack Compose Example App

<p align="center">
    <img src ="https://github.com/Foso/Jetpack-Compose-Playground/blob/master/docs/compose.png" height=500 />
 
</p>

## Introduction 🙋‍♂️
This is an example project that is using an early alpha version of Jetpack Compose https://android.googlesource.com/platform/frameworks/support/+/refs/heads/androidx-master-dev/compose/

# 🏠 Architecture

## 🛠️ Built With
### Kotlin
[![jCenter](https://img.shields.io/badge/Kotlin-1.3.40-green.svg)]()


### Project Structure
* <kbd>androidx_prebuilts</kbd> - This folder contains the Compose Libraries 1.0.0-alpha01 and the Compiler Plugin 1.0.0-alpha01
I compiled this versions from the AndroidX git repo. Because Compose is still in early alpha stage, Google doesn't offer any binaries online. In the AndroidX repo, Compose is used with a special Kotlin compiler "1.3.30-compose-20190503", but i figured out, it is also working with the Kotlin compiler v1.3.40-eap-21. 

* <kbd>app</kbd> - Base android project directory
* <kbd>compose</kbd> - a android library module that is using the compose libraries. It contains my example/test functions and 
the demo classes i copied out of the AndroidX repo (https://android.googlesource.com/platform/frameworks/support/+/androidx-master-dev/ui/material/integration-tests/) 
Inside the MyComposeApp() you can change the demo page that should be opened


## ✍️ Feedback

Feel free to send feedback on [Twitter](https://twitter.com/jklingenberg_) or [file an issue](https://github.com/foso/Jetpack-Compose-Playground/issues/new). Feature requests are always welcome.


## 📜 License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/Foso/Jetpack-Compose-Playground/blob/master/LICENSE) file for details

### Find this project useful ? :heart:
* Support it by clicking the :star: button on the upper right of this page. :v:

License
-------

   MIT License

Copyright (c) 2019 Jens Klingenberg

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



## Acknowledgments
Projects that helped me understand how to setup the project:
* [Mishkun/try-compose
](https://github.com/Mishkun/try-compose)
