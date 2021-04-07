# NPRuntime Plugin

### This sample plugin can be scripted, JavaScript can call into the plugin via NPRuntime.

### copy from https://www.codeproject.com/Articles/92787/Working-on-an-NPAPI-browser-plugin

### build by vs2010

### there is another demo https://github.com/axgle/npapi-chrome-plugin-helloworld

### download .h files from https://ftp.mozilla.org/pub/xulrunner/releases/latest/sdk/

### register the plug in for Firefox52 on Windows

```
REG ADD HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\MozillaPlugins\npplugin.sample.mine
REG ADD HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\MozillaPlugins\npplugin.sample.mine /v Path /t REG_SZ /d d:\github\np-sample\Debug\npmydemo.dll
REG ADD HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\MozillaPlugins\npplugin.sample.mine\MimeTypes
REG ADD HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\MozillaPlugins\npplugin.sample.mine\MimeTypes\application/x-npmydemo
```

