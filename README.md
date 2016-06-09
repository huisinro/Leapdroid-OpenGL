# Leapdroid-OpenGL

A cross platform OpenGL ES Emulation Layer for Android

Inside our Leapdroid virtual machine, we have implemented a very roubust OpenGL EL translator (based on Google's original Android emulator implementations).

The Android side contains encoders to forward GLES calls to the rendering side. The rendering side can be local or remote, it can be Linux, Windows, Mac or 
another mobile device, such as iOS or Android device. The rendering engine can be desktop OpenGL, or Windows DirectX, or GLES layer on another mobile device.

The protocol is optimized for performance.
