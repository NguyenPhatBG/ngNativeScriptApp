# Sample, Templates, Plugins 
https://market.nativescript.org/?tab=samples&framework=all_frameworks&category=all_samples <br/>
## Set Up
Step 01: Install Node.js <br/>
Step 02: Install the NativeScript CLI (npm install -g nativescript) <br/>
Verify that the installation was successful by running tns in the terminal. <br/>
Step 03: Install iOS and Android requirements <br/>
Windows:  
a. In cmd as an administator (Windows key > type "cmd" > right click > Run as Administrator) <br/>
b. @powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((new-object net.webclient).DownloadString('https://www.nativescript.org/setup/win'))" <br/>
c. Set up environment variables JAVA_HOME and ANDROID_HOME are required for Android development. <br/>
Step 04: Verify the setup <br/>
To verify the setup, run the tns doctor command which will check for any issues with the installation. If you see “No issues were detected” you’re good to go! <br/>
...successfull! <br/>
<br/>
NativeScript Advanced Setup: Windows <br/>
https://docs.nativescript.org/angular/start/ns-setup-win <br/>

TIP: To develop iOS applications on a Windows system or bypass the need to configure your environment for local Android development, you can use the cloud build service available in NativeScript Sidekick. <br/>
https://www.nativescript.org/nativescript-sidekick <br/>

## Creating apps
Basics of the NativeScript CLI <br/>
https://docs.nativescript.org/angular/start/cli-basics#creating-apps <br/>
Step 01: tns create HelloWorld --template tns-template-blank-ng
Step 02: cd root folder project => tns run (android || ios)



