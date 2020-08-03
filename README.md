[ >>> 中文版](README_ch.md)

# QCefWidget

The QCefWidget project provide a widget that used to view webpage. 

Support:

✅ Easy to use, can be integrated into your project with a few lines code;

✅ Supports both CEF OSR and non-OSR mode;
   
✅ Show background transparent webpage in irregularity window;

✅ Javascript and Qt interaction;

✅ OpenGL graphics acceleration;

✅ Third-party input method software;

✅ Perfect exit app without any CEF assert/exception in debug/release mode;

✅ Separate CEF rendering process and plugin process;

✅ Support Adobe Flash without any warnning, eg "Control-click to run Adobe Flash Player".

✅ Drag/Drop frameless window like Electron throught setting CSS property.

✅ Automatically adapt to system's DPI change.

# Quick start
Use QCefWidget as a normal QWidget:

```c++
QCefWidget pCefWidget = new QCefWidget();
pCefWidget->navigateToUrl("https://www.google.com");
```

For more property settings, see [QCefWidget.h](.\SDK\msvc2017_x86_shared\include\QCefWidget.h).

# QCefWidgetTester
QCefWidgetTester is a test project of QCefWidget. You can see some of the features of QCefWidget throught it.

Run:
`QCefWidgetTester\QCefWidgetTest.exe`

---

# Screenshot
![screenshot1 on windows](Screenshot/screenshot1.png)

![screenshot2 on windows](Screenshot/screenshot2.png)

---

`Email: winsoft666#outlook.com`
