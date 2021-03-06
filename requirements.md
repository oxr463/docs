
# Requirements
## Static Analysis
* **Mac**
  * Install [Git](https://www.atlassian.com/git/tutorials/install-git)
  * Install [Python **3.8-3.9**](https://www.python.org/)
  * After installing Python 3.8+, go to `/Applications/Python 3.8/` and run `Update Shell Profile.command` first and then `Install Certificates.command`
  * Install [JDK 8+](https://www3.ntu.edu.sg/home/ehchua/programming/howto/JDK_Howto.html)
  * Install command line tools `xcode-select --install`
  * Download & Install [wkhtmltopdf](https://wkhtmltopdf.org/downloads.html) as per the [wiki instructions](https://github.com/JazzCore/python-pdfkit/wiki/Installing-wkhtmltopdf)
  * Windows App Static analysis requires a Windows Host or Windows VM for Mac and Linux. [More Info](https://github.com/MobSF/Mobile-Security-Framework-MobSF/blob/master/mobsf/install/windows/readme.md)


* **Ubuntu/Debian based Linux**:
  * Install Git `sudo apt-get install git`
  * Install Python **3.8-3.9** `sudo apt-get install python3.8`
  * Install JDK 8+ `sudo apt-get install openjdk-8-jdk`
  * Install the following dependencies
    ```bash
    sudo apt install python3-dev python3-venv python3-pip build-essential libffi-dev libssl-dev libxml2-dev libxslt1-dev libjpeg8-dev zlib1g-dev wkhtmltopdf
    ```
  * Windows App Static analysis requires a Windows Host or Windows VM for Mac and Linux. [More Info](https://github.com/MobSF/Mobile-Security-Framework-MobSF/blob/master/mobsf/install/windows/readme.md)

* **Windows**
  * Install [Git](https://git-scm.com/download/win)
  * Install [Python **3.8-3.9**](https://www.python.org/)
  * Install [JDK 8+](https://www3.ntu.edu.sg/home/ehchua/programming/howto/JDK_Howto.html)
  * Install [Microsoft Visual C++ Build Tools](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=BuildTools&rel=16)
  * Install [OpenSSL (non-light)](https://slproweb.com/products/Win32OpenSSL.html)
  * Download & Install [wkhtmltopdf](https://wkhtmltopdf.org/downloads.html) as per the [wiki instructions](https://github.com/JazzCore/python-pdfkit/wiki/Installing-wkhtmltopdf)
  * Add the folder that contains `wkhtmltopdf` binary to environment variable PATH.


?> **IMPORTANT:** Set `JAVA_HOME` environment variable. iOS IPA Analysis works only on **Mac, Linux and Docker containers**.

***
## Dynamic Analysis
* **Dynamic Analysis will not work if you use MobSF docker container or setup MobSF inside a Virtual Machine.**
* Install [Genymotion](https://www.genymotion.com/fun-zone/) or [Genymotion Cloud VM](https://www.genymotion.com/cloud/) or [Android Studio Emulator](https://developer.android.com/studio)

