Tablr
---------------------

Tablr is a database application design for the course Software Design in the 3rd bachelor of Informatics at K.U. Leuven.


Installation guide
---------------------

1. Install java and scala at 
https://ampersandacademy.com/tutorials/java-2-scala/installing-the-scala-programming-language-in-windows-10-64-bit

2. Install the IntelliJ Community Edition and download the scala plugin at 
https://docs.scala-lang.org/getting-started-intellij-track/getting-started-with-scala-in-intellij.html

3. Install the sbt via the setup at https://www.tutorialspoint.com/scala/scala_environment_setup.htm

4.  Update the Environmental Variables in Windows 10

- Add the sbt bin directory to the Path in the environmental variables for admin
- Add the sbt directory to SBT_HOME in the environmental variables system variables

5. Create a command line sbt project:
- follow the guide at https://docs.scala-lang.org/getting-started-sbt-track/getting-started-with-scala-and-sbt-on-the-command-line.html
- add dependencies as described to the build.sbt file

Libraries 
---------------------

package canvaswindow;

import java.awt.Color; 

import java.awt.Component;

import java.awt.Dimension;

import java.awt.EventQueue;

import java.awt.Graphics;

import java.awt.event.KeyAdapter;

import java.awt.event.KeyEvent;

import java.awt.event.MouseAdapter;

import java.awt.event.MouseEvent;

import java.awt.event.WindowAdapter;

import java.awt.event.WindowEvent;

import java.awt.image.BufferedImage;

import java.io.BufferedOutputStream;

import java.io.BufferedReader;

import java.io.File;

import java.io.FileInputStream;

import java.io.FileOutputStream;

import java.io.IOException;

import java.io.InputStreamReader;

import java.io.PrintWriter;

import java.util.ArrayList;

import javax.imageio.ImageIO;

import javax.swing.JFrame;

import javax.swing.JPanel;

Resources
---------------------

This [folder](https://drive.google.com/drive/folders/1MXqFnfEIg4t1m4KRv4ckeLBtw1wJRC_l?usp=sharing) has additional resources for the project.
