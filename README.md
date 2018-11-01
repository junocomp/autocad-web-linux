# AutoCAD Web for Linux
AutoCAD Web desktop app for Linux

<img src="https://raw.githubusercontent.com/giovannicaligaris/autocad-web-linux/master/Screenshot%20from%202018-11-01%2017.44.34.png">

<b>You will need an AutoCAD or AutoCAD LT subscription, otherwise it will only work as a CAD viewer. </b>


<b>INSTALLATION</b>

In order to build this, you will need Nativefier first.

https://github.com/jiahaog/nativefier/

Once Nativefier is installed, run the following command:

```bash
nativefier --name "AutoCAD Web" "https://web.autocad.com" --user-agent "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/62.0.3202.94 Safari/537.36" --platform "linux" --internal-urls ".*?\autodesk\.*?"

cd auto-cad-web-linux-x64
./auto-cad-web
```
