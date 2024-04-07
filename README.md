> [!IMPORTANT]  
> Dont run anything you dont trust.

> [!TIP]
> Make registry backup before using this.

# StartAllBackCleanup <img src="https://img.shields.io/badge/Status-working-green.svg"></img></img>
Just a StartAllBack reset trial period (100d)

## How it works?
The program is a powershell script used to remove some registry keys to reset the trial period of StartAllBack software.
It needs to restart the *explorer.exe* process to take effect, **it will ask you permission to do it**.

## Download
<a href="https://github.com/5qw/StartAllBack/releases/latest/download/StartAllBackCleanup.exe">Click here (StartAllBack-Cleanup.exe)</a> <br>
or<br>
Download .ps1 files and execute: <br>
<a href="https://github.com/5qw/StartAllBack/releases/latest/download/StartAllBack-Cleanup.ps1"> StartAllBack-Cleanup.ps1</a>  ➝  ask you permission to restart *explorer.exe* process (same as .exe file) <br>
<a href="https://github.com/5qw/StartAllBack/releases/latest/download/StartAllBackCleanup-CLEAN.ps1"> StartAllBackCleanup-CLEAN.ps1</a>   ➝  you will need to restart *explorer.exe* process manually. (if you feel more safe)


> [!TIP]
> If you get execution policies warning using .ps1 files try this to bypass:
> - Open powershell as administrator
> - Use this command: ``powershell.exe -executionpolicy unrestricted <FILE PATH>``
> - Example: *powershell.exe -executionpolicy unrestricted C:\Users\Administrator\Desktop\StartAllBack-Cleanup.ps1*



## Virus detection
> [!NOTE]  
> Detections because it removes registry keys. Use the .ps1 file if you feel more safe to use. <br>

| Virustotal (.exe) | Virustotal (.ps1) | Hybrid-Analysis (.exe) |
| -------- | -------- | -------- |
| <a href="https://www.virustotal.com/gui/file/4ce67dea08dde89c24b1c06895c3315b07b6a000bf584d83ea99a138739b57f6">Link</a>   | <a href="https://www.virustotal.com/gui/file-analysis/YmNlYjZmOGFmMWFiY2ZlMjY1NjNmNWMyYTU1NGY2NzU6MTY5ODg0MDk5MQ==">Link</a>   | <a href="https://www.hybrid-analysis.com/sample/4ce67dea08dde89c24b1c06895c3315b07b6a000bf584d83ea99a138739b57f6">Link</a>   |
| <img src="https://img.shields.io/badge/VirusTotal-12/72-darkred.svg">   | <img src="https://img.shields.io/badge/VirusTotal-0/0-darkgreen.svg">   | <img src="https://img.shields.io/badge/HybridAnalysis-malicious-darkred.svg">   |
<br>
<br>
<br>
<br>
Skid from: https://gist.github.com/vaginessa/a65c38b2c76809c0fffc2c67ce8f5493 // https://github.com/iandiv/StartAllBack-Cleanup
