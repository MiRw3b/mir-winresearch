So, did you ever experience a crash with KseCDD.sys, saying "KMODE_EXCEPTION_NOT_HANDLED" ?
i did sadly, when i would upload files, it would instantly crash whenever the explorer opened to select a file, but i've now found the fix.

The issue came from the fact that i've hugely tweaked and debloated my Windows.

So, to fix it, you need to re-enable KsecPkg

Download servi-win https://www.nirsoft.net/utils/serviwin.html

(get the correct version, if your CPU and OS are on x64 bits, take the x64 bits version)

now, after you've downloaded it, make sure to right click on it, and run it as ADMINISTRATOR.

also make sure to be on this tab "Drivers" (screen below)

![image](https://github.com/MiRw3b/mir-winresearch/assets/60517683/724e9e30-3576-4f92-b885-130de08bffaf)

Now, what you need to do is find KsecPkg.

After you've found it, right click on it and go on Change Startup Type, and then **choose System**

Then, again right click on it and now go on Change Status, and choose **Start**

Voila! It should now stop crashing !
