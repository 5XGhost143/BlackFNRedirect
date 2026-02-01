# BlackFNRedirect

**What is this?**

**So when I first developed BlackFN I noticed there were only small parts that I had to puzzle together to make BlackFN working I didn't liked this so I open-sourced and made configuration easy for everyone but I'm getting out of context BlackFNRedirect is basically the 10.000 Redirect for OGFN but this one is different this one opens a Proxy on Port "8432" this means every device that supports Fortnite and an External Proxy will be able to Redirect Epic's Backend to for example the BlackFN Backend or any other OGFN Backend**


**Requirements:**

**=> .NET 10 (Desktop Runtime should be enough)**

**=> and an Server that is decent for this Proxy**


**Setup:**

**Go into Terminal and run BlackFNRedirect here is an example how to execute the Proxy: BlackFNRedirect.exe --use-port 4221 --use-target https://ols.blackfn.ghost143.de**

**Arguments meanings:**

**=> --use-port basically sets the Port where the Proxy should run but this isn't required to set.**

**=> --use-target this one is the very important argument because this says to Proxy on which Backend it should redirect this is also not required to set if u don't set this one it will automatically redirect to the BlackFN Backend**


**Note: I only tested it on Windows so idk if it works on Linux, but I still made an Linux Build in the Actions**


