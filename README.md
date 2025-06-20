<p align="center"> <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fxiv3r%2FBurpsuite-Professional&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=%F0%9F%91%81%EF%B8%8F+++%F0%9F%91%81%EF%B8%8F&edge_flat=false">

![Screenshot_2024-09-19_17_45_09](https://github.com/user-attachments/assets/873ef98a-48e0-445b-b5dc-eb5959ad5b34)

# <h1 align="center"> Burpsuite Professional v2024.12.1 latest </h1>

<p align="center"> Burp Suite Professional is the web security tester's toolkit of choice. Use it to automate repetitive testing tasks - then dig deeper with its expert-designed manual and semi-automated security testing tools. Burp Suite Professional can help you to test for OWASP Top 10 vulnerabilities - as well as the very latest hacking techniques. Advanced manual and automated features empower users to find lurking vulnerabilities more quickly. Burp Suite is designed and used by the industry's best.</p>

<h1 align="center">

[Overview](https://portswigger.net/burp/pro)
 </h1>
 
<br></br>

<h1 align="center"> Linux Installation </h1>

<br></br>

- ### Auto Install
```sh
wget -qO- https://raw.githubusercontent.com/xiv3r/Burpsuite-Professional/main/install.sh | sudo bash
```
- ### Run
```sh
burpsuitepro
```
<details><summary>

### Update [Optional]
</summary>

```sh
cd && rm -rf Burpsuite-Professional && wget -qO- https://raw.githubusercontent.com/xiv3r/Burpsuite-Professional/refs/heads/main/update.sh | sudo sh
```
</details>

<details><summary>

### Java Version [ stable: openjdk-21-jre ]
</summary>

```sh
sudo update-alternatives --config java
```               
</details>

- ### Setup Licenses

<div align="center">
 
https://github.com/xiv3r/Burpsuite-Professional/assets/117867334/c25831a4-68a2-44ee-b6dd-5ff18165f340
</div>
 
Note: Copy the license from loader to the burpsuite > manual activation > copy burpsuite request key to loader request >  copy response key to the burpsuite.

- ### Create a Launcher (xfce)

     right click the desktop -> create a launcher name it Burpsuite Professional, add command `burpsuitepro` and select burpsuite community icon.

<div align="center">
 <img width="500" height="500" src="https://github.com/xiv3r/Burpsuite-Professional/blob/main/Launcher.jpg">
</div>

# <h1 align="center"> Windows Installation</h1>

<br>
 
- Make a `Burp` directory name in `C Drive` for faster access.

- Download [install.ps1](https://codeload.github.com/xiv3r/Burpsuite-Professional/zip/refs/heads/main) and extract move the file inside to `C:\Burp`

- Open `Powershell` as administrator and execute below command to set Script Execution Policy.


      Set-ExecutionPolicy -ExecutionPolicy bypass -Scope process

- Inside PowerShell go to `cd C:\Burp`

- Now Execute `install.ps1` file in Powershell to Complete Installation.

      ./install.ps1
 
- Change the icon of `Burp-Suite-Pro.vbs` to the given icon 

- Create a shortcut to Desktop. Right Click over `Burp-Suite-Pro.vbs` Go to Shortcut tab, and below there is `Change Icon` tab

- Click there and choose the `burp-suite.ico` from `C:\Burp\`

   <div align="center">
    
    <img src="https://user-images.githubusercontent.com/29830064/230825172-16c9cfba-4bca-46a4-86df-b352a4330b12.png">
</div>

- For Start Menu Entry, copy `Burp-Suite-Pro.vbs` file to 

      C:\ProgramData\Microsoft\Windows\Start Menu\Programs\


<h1 align="center" >


 <details><summary>Credits 👇</summary>


* Loader.jar 👉 [h3110w0r1d-y](https://github.com/h3110w0r1d-y/BurpLoaderKeygen)
* Modified 👉 [cyb3rzest](https://github.com/cyb3rzest/Burp-Suite-Pro)

</details>
</h1>
