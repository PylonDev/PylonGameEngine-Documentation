# `PylonGameEngine - Documentation`
This is the Documentation of my [PylonGameEngine](https://github.com/PylonDev/PylonGameEngine)

## Code Documentation
bla bla
## Creating New Project
Creating a new Project is really simple:
#### 1. Just Create a new console application project
#### 2. Reference all the libraries
#### 3. Paste sample code
```cs
using PylonGameEngine;
using PylonGameEngine.GUI.GUIObjects;
using PylonGameEngine.Input;
using PylonGameEngine.Mathematics;
using PylonGameEngine.Render11;
using PylonGameEngine.SceneManagement;
using PylonGameEngine.SceneManagement.Objects;
using PylonGameEngine.Utilities;
using System;
using System.Drawing;
using System.IO;

namespace Sample
{
    internal static class Program
    {
        [STAThread]
        static void Main(string[] args)
        {
            GameProperties.GameName = "Sample";
            GameProperties.Version = new MyVersion(0, 0, 0, -1);
            //GameProperties.SplashScreen = new SplashScreen((Bitmap)Bitmap.FromFile(@"SplashScreen.png"));
            MyGame.Initialize();
            
            //YOUR CODE HERE

            MyGame.Start();
        }
    }
}
```
## Debugging
bla bla
