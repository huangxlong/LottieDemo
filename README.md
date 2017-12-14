1. compile 'com.airbnb.android.lottie:2.3.1'
2. 将动画的 JSON 文件，放在 app/src/main/assets 目录下，在 Layout 布局文件中，可以直接使用。(Json文件资源下载：https://www.lottiefiles.com/)
    使用 LottieAnimationView
    它支持几个属性：
      lottie_fileName : 播放动画的 json 文件。
      lottie_loop：是否循环播放，默认为 false。
      lottie_autoPlay：是否加载完成之后，自动播放，默认为 false。
3. 想要监听动画的开始结束等状态，可以使用 addAnimatorListener() 方法
   如果我们想要监听 Lottie 动画的中间状态，例如执行的进度等等，可以使用 addAnimatorUpdateListener()。
   
   Lottie Github：
https://github.com/airbnb/lottie-android


Lottie 官方文档：
http://airbnb.io/lottie/
