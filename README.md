# **ComboJack for ALC Dell series**

A window will appear and allow you to choose **Headphones** or **Headsed** mode when an audio device is connected.


![popup](https://user-images.githubusercontent.com/92006941/141351074-7b03cd61-ea71-49e9-8d82-89a9d414cc64.png)


# **Supported codecs:**

+ ALC255
+ ALC256
+ ALC295 (Dell Inspiron 7590/7591)
+ ALC298

# Status

+ Currently only **Headphones** mode and **Headset** mode are supported

# **Installation**
**1**. Remove CodecCommander.kext if you use
**2**. Copy **VerbStub.kext** to **kexts folder**

   - If you using **Clover** copy **VerbStub.kext** to : EFI/Clover/kexts/Other
   - If you using **Opencore** copy **VerbStub.kext**: EFI/OC/kexts. (You need add kext to Config.plist so you just need open Config.plist with Propertree and Press CTRL + R, kext will be automatically added. After that, Ctrl + S to save)

**3**. Run **install.sh** in **ComboJack_Installer/install.sh** then **Combo Jack** will be installed.

# **Download**

- **Download ComboJack from [HERE](https://github.com/HowNeft/ComboJack/releases/tag/Release)**.

**Original sources:** [hackintosh-stuff](https://github.com/hackintosh-stuff/ComboJack)
