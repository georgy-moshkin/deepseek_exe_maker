I've asked Deepseek to create a windows executable application
without installing any IDEs or command line utilites. It turns out
Windows 8,10 and 11 is shipped with C# compiler located at
C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc.exe
which can be used to create console and GUI applications!

Demos:
1) Hello World console app
C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc.exe hello.cs

2) Hello World GUI dialog
C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc.exe /target:winexe hello_calculator.cs

3) Simple calculator
C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc.exe /target:winexe hello_dialog.cs

4) Sine wave animation
C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc.exe /target:winexe sinewave.cs
