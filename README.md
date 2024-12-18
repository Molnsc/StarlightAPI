# StarlightAPI Discord Injector And Executer
*Contains Execution and Injection Source Code (and compiled DLL)* <br>
*Modified to contain a DLL usable to reference the API and use within a C# Project*
# Version
*Source:* **3.0.9** <br>
*Not latest version may experience issues!*
# Injection (Source Version)
**Lite-Injection *72%* DEV_TOOLS Process** <br>
**Chromium WebApp RM Debug Flag Abuser** <br>
# Docs
*No related docs*
# Required
*For building from Scratch or extra* <br>
**Loaders**
```cs
using System;
using System.Diagnostics;
using System.Net.Http;
using System.Threading.Tasks;
using System.Windows.Forms;
using WebSocketSharp; NUGET PACK
using Newtonsoft.Json.Linq; // NUGET PACK
using System.IO;
using System.Linq;
using System.Drawing;
using Newtonsoft.Json; // NUGET PACK
using System.Security.Cryptography;
```
<br>
**Global Variables**

```
private string URLinPass = null;
private WebSocket _webSocket = null;
private bool dragging = false;  // Flag to track if the form is being dragged (Optional for borderless forms) -- Not required
private Point startPoint = new Point(0, 0); // Flag to track form start point (Optional for borderless forms) -- Not required
public string debugURL = "";
public string authHD = "none";
public string globalcid = "";
public string globalgid = "";
public bool attached = false;
```
<br>

