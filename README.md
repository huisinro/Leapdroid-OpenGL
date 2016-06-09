# Leapdroid-OpenGL

A cross platform OpenGL ES Emulation Layer for Android

Inside our Leapdroid virtual machine, we have implemented a very roubust OpenGL EL translator (based on Google's original Android emulator implementations).

The Android side contains encoders to forward GLES calls to the rendering side, and the rendering side has decoders to decode the parameters and send them to host engine for rendering. 

The rendering side can be local or remote, it can be Linux, Windows, Mac or 
another mobile device, such as iOS or Android device. The rendering engine can be desktop OpenGL, or Windows DirectX, or GLES layer on another mobile device.

The protocol is highly optimized for performance, including compression. In addition, we also provide an encryption mechansim to protect the content if necessary.

If Android and host are running on the same machine, such as inside our LeapDroid vm (http://www.leapdroid.com), we use highly efficient memory sharing for data transmission.


