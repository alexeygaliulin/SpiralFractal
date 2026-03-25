Spiral fractal is a lua based program i wrote , that works in command (console) mode to create serialized fractal images based on custom complex math formula that you can input with -cl:z=c_sqr(z) .
It utilizes Lua Jast-In-Time compiler luajit, parallel processing that requres opencl support,
and image api that needs microsoft developer dlls :
https://download.microsoft.com/download/0/6/4/064f84ea-d1db-4eaa-9a5c-cc2f0ff6a638/vc_redist.x64.exe.
Download rar file if your GPU requires 64 bit, otherwise download and extract zip file.
To try automatic generation of fractals using my program on windows run fractest.bat .
To show 3D opengl version display of fractal images as the a randomly generated - run fractgl.bat . 
