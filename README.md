# OpenGL
My OpenGL starter code with the help of Gland and GLFW <d>
All the projects of OPENGL are made with the tutorial of LearnOpenGL:https://learnopengl.com/Code-repository<br>
main.cpp contains the code required to create a GLFW Window where everything we do will be seen<br/>
  
I suggest compiling GLFW yourself<br>
Instrutions for compiling GLFW as it can be difficult and a bit confusing even if using the LearnOpenGL tutorial:
  1. Get the 64 bit souce code of GLFW: https://www.glfw.org/
  2. Extract the zip file where you want to
  3. Download and install C Make: https://cmake.org/
  4. Give the source folder of GLFW
  5. Give destination for the build, i used a sepeate folder
  6. Configure and select the Version of VS you have.
  7. Click Generate
  8. Click Open Project in the CMAKE or go the GLFW.sln file in the build folder.
  9. Click build. Make sure to be in Dubug mode.(The list before start/Local Window debugger and the type of instuction set)
  10. Next go to GLAD website: https://glad.dav1d.de/https://glad.dav1d.de/
  11. Select C/C++ langauge.
  12. Select OpenGL
  13. Selec the version of OpenGl which is supported by your GPU.
  14. Set Profile to CORE. My code runs on Core profile so get that.
  15. Click generate.
  16. Download zip file and extract contents.
  17. Create a "lib" and "include" folder. These folders will be used every time a new project is started. 
  18. Put Glad include contents into the the folder.
  19. Create a empty project in Visual Studio.
  20. Add glad.c file into project.
  21. Go to project properties and into VC++ properties.
  22. Select the include directories in VC++ and enter path to the folder. Make sure to add ";$(IncludePath)"  at the end of path.
  22. Do the same for library directories. 
  23. once done, Go to Linker input properties.
  24. Add "glfw3.lib" and "glfw3.lib" into additnal files.
  25. Set up project as a 64bit program and also make sure it is in Debug mode.
  26. You are now ready to write OpenGL Code.
  
  
  
