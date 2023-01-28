1. Install ApkTool https://ibotpeaches.github.io/Apktool/install/

Download Mac wrapper script (Right click, Save Link As apktool)
 - than clear extantion FileInfo

Download apktool-2 (find newest here)
Rename downloaded jar to apktool.jar
Move both files (apktool.jar & apktool) to /usr/local/bin (root needed)
Make sure both files are executable (chmod +x)
 - run in terminal: chmod +x apktool, chmod +x apktool.jar
Try running apktool via cli

apktool d *.apk
2. Install dex2jar https://github.com/pxb1988/dex2jar
move from zip dex2jar.sh and folders "lib" "bin"

3. JD_GUI
 - run if some error:
java -jar ./JD-GUI.app/Contents/Resources/Java/jd-gui-1.6.6-min.jar        
or
/usr/libexec/java_home -v 1.8 && open /Applications/JD-GUI.app 
