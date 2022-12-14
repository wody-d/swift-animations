<div align="center"><h2> swift-animations</h2></div>

<div align="center"><img src="https://raw.githubusercontent.com/hello-woody/img-uploader/master/uPic/swift%20animation.png"></div>

### Introduce

ππ» Hi, I'm μ΄μ¬μ©, wanna be good iOS developer.

Inspired by Chanhee Jung, Younghoo Im (my academy collegues) and also dribbles, I created animations in Swift.
Animations are something that I really like, so I will add animations continually to this repository. I hope that anyone who comes to this repository will be inspired by animations, then create other wonderful animations.

μ°¬ν¬, μν (μμΉ΄λ°λ―Έ λλ£λ€)μκ², κ·Έλ¦¬κ³  λλ¦¬λΈμμ μκ° λ°μ Swiftλ‘ λͺ κ°μ§ μ λλ©μ΄μμ κ³΅λΆνλ©° λ§λ€μμ΅λλ€. μ λλ©μ΄μμ μ§μ  λ§λλ κ²μ μ λ§ μ¬λ°κ³  μ λλ κ²½νμ΄μμ΅λλ€! μμΌλ‘λ κ³μν΄μ μΆκ°νλ €κ³  ν΄μ. λκ΅¬λ  μλ μμ λ€μ λ³΄κ³  μκ° λ°μ λ λ©μ§ μ λλ©μ΄μμ κ΅¬ννμ¨μΌλ©΄ μ’κ² μ΅λλ€! 

<br />

<br />

### Animations

1. μ΄λ―Έμ§ frameμ μ΄μ©ν νλ©΄ μ ν μ λλ©μ΄μ - unsplashed clone app

`UIViewControllerTransitioningDelegate` / `UIPresentationController` / `UIViewControllerAnimatedTransitioning` 

<img src="https://user-images.githubusercontent.com/56102421/153770814-5a9a8220-1030-4d5b-9aaf-6a4f20b02fbd.gif" width="250"> <img src="https://user-images.githubusercontent.com/56102421/153770887-88090415-7d3e-4b32-9438-ac39752ee6b5.gif" width="250">  <img src="https://user-images.githubusercontent.com/56102421/153770957-c486b2de-f358-4764-83e5-79b95433fdce.gif" width="250" /> 

2. λκ·ΈλΌλ―Έ λ‘λ© μ λλ©μ΄μ - circular loading animation

- `CABasicAnimation` / `CAKeyframeAnimation` / `CAReplicatorLayer``
- ``CoreAnimation`μ νμ΅νλ©° μ ν λ¬Έμμ κΈ°λ³Έ μμ λ€λ‘λΆν° μκ°μ λ°μ λ§λ€μμ΅λλ€. 

<img src="Animation 2 - Circular Loading/Circular Loading Animation.gif" width="250"> 

3. λ³ λ°°κ²½ μ λλ©μ΄μ - shining star background animation 

- `CAGradientLayer` / `CABasicAnimation` / `CAKeyframeAnimation` / `drand48()` / `Double.random(in: 0...1)` / `CATransaction` / `UIBezierPath` 
- μ°μ£Ό μ»¨μ νλ‘μ νΈλ₯Ό μ§ννλ€ λ°λ°ν μ± λ°°κ²½μ CoreAnimationμ ν΅ν΄ νλ ₯μ μ£Όμμ΅λλ€. μ€μ  μ±μ λ°°κ²½μ μ μ²΄μ μΌλ‘ λ£μμ΅λλ€. (μ± μ€ν μ΄μ μ¬λΌμ€λ©΄ κ³΅μ ν κ²μ!)

<img src="Animation 3 - Star Background/shining star background animation.gif " width="250"> 

4. λ§λμ§ μλ 3κ°μ νΈ μ λλ©μ΄μ - three circular loading animation

- `UIBezierPath` / `CABasicAnimation` / `AnchorPoint` vs `Position` / Math
- [μ νλΈ](https://www.youtube.com/watch?v=1Aq9OJuS3ok)μ μκ³ λ¦¬μ¦μ΄ μΆμ²ν΄μ€ μμμ λ³΄κ³  μκ°μ λ°μ λ§λ€μμ΅λλ€. μμ κ°λλ₯Ό κ³μ°νκΈ° μν΄ `asin`μ μ¬μ©νμ΅λλ€. 
  μνμ μΈ μκ°κ³Ό μ°μ°μ ν΅ν΄ κ΅¬νν  μ μλ μ¬λ°λ μ λλ©μ΄μμλλ€. 

<img src="Animation 4 - Three Circular Loading/three circular loading.gif" width="250"> 

5. μ°μ£ΌλΉνμ¬ λ¦¬νλ μ μ λλ©μ΄μ - astronaut refresh animation 

- `UIScrollViewDelegate` / `UIView.animate` / `CABasicAnimation` / `CAKeyframeAnimation` / `UIBezierPath`
- μ€ν¬λ‘€ μ λμ λ°λΌ μ°μ£ΌλΉνμ¬κ° μ΄λνλ©° λ‘λ©λλ λμ μ°μ£ΌλΉνμ¬κ° λκ³  λ‘λ©μ΄ μλ£λλ©΄ λ€μ μμλ³΅κ·λλ μ λλ©μ΄μμλλ€. 

<img src="Animation 5 - Blackhole Refresh/astronaut refresh animation.gif" width="250"> 

6. μΊλ¦°λλ·° μκ° μ£Όκ° - Calendar

- `Infinite Scroll` / `Day Calculation
- μ£Ό, λ¬ κ° λ¬λ ₯ μ ν μ λλ©μ΄μμ΄ νμ¬λ λ¬λ ₯μλλ€.

<img src="https://raw.githubusercontent.com/hello-woody/img-uploader/master/uPic/2022-11-22%2013.44.06.gif" width="250"> 

<br />

<br />

### Reference

**Design Concepts**

- Swift Documentation
- [Dribble](https://dribbble.com)
- My Collegues ([chaneeii](https://github.com/chaneeii), [Asher3576](https://github.com/Asher3576))
- [cubic-bezier](https://cubic-bezier.com/#.1,.97,.82,.07)

**Developments**

- Swift Documentation
- [Core Animation Basics Guide](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/CoreAnimation_guide/CoreAnimationBasics/CoreAnimationBasics.html#//apple_ref/doc/uid/TP40004514-CH2-SW3)
- [Raywenderlich](https://www.kodeco.com/books/ios-animations-by-tutorials/v6.0/chapters/14-layer-keyframe-animations-struct-properties)

