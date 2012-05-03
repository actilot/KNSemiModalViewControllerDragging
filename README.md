## UIViewController+KNSemiModal Category

UIViewController+KNSemiModal is an effort to make a replica of semi-modal view found in the beautiful [Park Guides](http://itunes.apple.com/us/app/national-parks-by-national/id518426085?mt=8) app. You can see this original semi-modal view below.

This library (ARC) is designed as a Category to UIViewController so you don't have to subclass and you can simply drop in any project and it will just work!

<img src="https://github.com/kentnguyen/KNSemiModalViewController/blob/master/Docs/original.png?raw=true" />``
<img src="https://github.com/kentnguyen/KNSemiModalViewController/blob/master/Docs/ss1.png?raw=true" />``
<img src="https://github.com/kentnguyen/KNSemiModalViewController/blob/master/Docs/ss2.png?raw=true" />

### Demo

Download a demo clip [here](https://github.com/kentnguyen/KNSemiModalViewController/blob/master/Docs/KNSemiModalDemo.mov?raw=true) (1.3MB, .mov)

### Features
* Works with bare UIViewController
* Works with UIViewController contained inside UINavigationController
* Works with UIViewController contained inside UINavigationController, contained inside UITabbarController
* Easy to understand and very small code base
* Easy to use as subclass

### TODO
* iPad support
* Landscape support

### Installation / How to use
* Import `UIViewController+KNSemiModal.h` in your ViewController
* Call `[self presentSemiModalView:myView]`

Read my [blog post](http://kentnguyen.com/ios/) for detailed usage.

### License

UIViewController+KNSemiModal is licensed under MIT License
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.