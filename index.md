### [LXC (LibXConvolver)](https://github.com/AchimTuran/LibXConvolver)
LXC is an optimized cross platform open source library for [fast convolution](https://en.wikipedia.org/?title=Convolution#Fast_convolution_algorithms). The library implements a simple API, which can be used for real applications, prototyping or as a tutorial on how to use the included functions in order to develop more advanced applications. 
<br>
<br>

### [asplib (Achim's Signal Processing LIBrary)](https://github.com/AchimTuran/asplib/)
This is my cross platform C/C++ signal processing library. At the moment it includes the following features:
- A cross platform biquad filter class, implemented with a factory design pattern to create filters with different processor optimizations
- Audio buffer implementations via a C/C++ template class interface
- An easy to use [PortAudio](http://www.portaudio.com/) interface class for rapid prototyping of C/C++ audio processing algorithms
- This library is already widely usable and features are constantly added while keeping API backwards compatibility
<br>
<br>

### [adsp.template](https://github.com/AchimTuran/adsp.template)
It's a framework and starting point for developing new audio add-ons for Kodi's Audio DSP extension point. This framework is still extended and constantly improved while developing [adsp.biquad.filters](https://github.com/AchimTuran/adsp.biquad.filters) and also an [adsp.xconvolver](https://github.com/AchimTuran/adsp.xconvolver).
<br>
<br>

### [adsp.xconvolver](https://github.com/AchimTuran/adsp.xconvolver)
adsp.xconvolver is a convolution engine addon for Kodi’s audio processing system. It is based on [LibXConvolver](https://github.com/AchimTuran/LibXConvolver), [adsp.template](https://github.com/AchimTuran/adsp.template) and [asplib](https://github.com/AchimTuran/asplib/).
<br>
<br>

### [adsp.biquad.filters](https://github.com/AchimTuran/adsp.biquad.filters)
This project is another addon for Kodi's audio processing system. At the moment it already contains a 10 band equalizer to adjust the frequency band levels.
<br>
<br>

### [My Google Summer of Code 2015 project](http://achim-turan.de/gsoc-blog/)
My project [Creating cross-platform room correction for Kodi](http://www.google-melange.com/gsoc/proposal/public/google/gsoc2015/achim_turan/5629499534213120) was chosen out of many proposals, which has the goal to optimize the decoded audio data itself during playback to perfectly fit into the environment of the listener. The progress of this project can be monitored by visiting my [weekly blog posts](http://achim-turan.de/gsoc-blog/weekly-reports/).