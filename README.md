# Anime4KPython
This is an implementation of Anime4K in Python. It based on the [bloc97's Anime4K](https://github.com/bloc97/Anime4K) algorithm version 0.9 and some optimizations have been made.
This project is for learning and the exploration task of algorithm course in SWJTU.  
***NOTICE: The Python version will be very slow. It is about 100 times slower than [Go version](https://github.com/TianZerL/Anime4KGo), because it take too much time to traverse the image. So it just suitable for learning how the Anime4K works. If you want to use anime4k in python, see [pyanime4k](https://github.com/TianZerL/pyanime4k).***

# pyanime4k
[pyanime4k](https://github.com/TianZerL/pyanime4k) is a simply package to use anime4k in python, easy, fast and powerful, which support both image and video processing, based on [Anime4KCPP](https://github.com/TianZerL/Anime4KCPP). 

# About Anime4K
Anime4K is a simple high-quality anime upscale algorithm for anime. it does not use any machine learning approaches, and can be very fast in real-time processing.

# Usage
Please install opencv-python before using.  

    pip install opencv-python  

See the example.py, it is very easy to use. 
 
There are four main arguments:
- **passes**: Passes for processing.
- **strengthColor**: Strength for pushing color,range 0 to 1,higher for thinner
- **strengthGradient**: Strength for pushing gradient,range 0 to 1,higher for sharper
- **fastMode**: Faster but maybe lower quality

# Other implementations
- Go
  - [TianZerL/Anime4KGo](https://github.com/TianZerL/Anime4KGo)
- C++
  - [TianZerL/Anime4KCPP](https://github.com/TianZerL/Anime4KCPP)
- C#
  - [shadow578/Anime4kSharp](https://github.com/shadow578/Anime4kSharp)
  - [net2cn/Anime4KSharp](https://github.com/net2cn/Anime4KSharp)
- Java
  - [bloc97/Anime4K](https://github.com/bloc97/Anime4K)
- Rust
  - [andraantariksa/Anime4K-rs](https://github.com/andraantariksa/Anime4K-rs)