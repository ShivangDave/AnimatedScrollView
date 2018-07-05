
# Preview
![Alt Text](https://github.com/ShivangDave/AnimatedScrollView/blob/master/AnimatedScrollView.gif)

# AnimatedScrollView

UIScrollView that smooth scrolls on its own. Pretty Animation!

# How to use:

# Manually
- Download and Import AnimatedScrollView.swift in your existing project.
- Assign it as a class to your regular UIScrollView or create a new instance.
- Call animate method.

# CocoaPods
In project directory:

```
pod init
```

Paste following:

```
pod 'AnimatedScrollView', :git => 'https://github.com/ShivangDave/AnimatedScrollView.git', :tag => '1.0.2'
```

Install:

```
pod install
```

# Implementation
```
let scrollView = AnimatedScrollView()

scrollView.animate(self.view, "Image.jpg", true)
```
