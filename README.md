
個人推介使用Potplayer, 但Potplayer 有一些Membership 的東西會無法播放  
想機翻會限直播只好用 "ViiTor" 這個，  
但 "ViiTor" 本身翻譯只能每天用30 分鐘  
本Github 是利用它的引撆去改成本地 Whisper + Ollama 去翻譯  
翻譯大概會有一秒多的delay  

Its a Google Chrome Extenstion for Vtuber Subtitle  
which needs LOCAL Ollama + Local Whisper  
(potplayer can do the same thing, but potplayer can't play Membership content.)  

*This is a AI modded Extention for ViiTor   
which disabled the 30min free limit and the server Translate function.  


Local Voice Ollama 安裝與啟動教學  
Local Voice Ollama Install Instruct  

==========================


==========================

Step 1：解壓 Local Voice Ollama 資料夾  
Step 1: Upzip the folder "Local Voice Ollama.rar"  
--------------------------------

把 `Local Voice Ollama` 資料夾解壓到 C 槽或 D 槽。  
不建議放在 Chrome Extension 原本的資料夾裡。  


Put `Local Voice Ollama` into C :\ or D :\  
Please don't put it in the Chrome Extension Folder.  
<img width="1113" height="638" alt="1" src="https://github.com/user-attachments/assets/230622c9-b62e-4338-a922-318065f3a708" />




Step 2：安裝 Chrome 擴充功能    
Step 2：Install Chrome Extension  
---------------------

開啟 Chrome，進入：  

`chrome://extensions`

點選「載入未封裝項目」。  
Click on “Load unpacked”.  

<img width="657" height="421" alt="2" src="https://github.com/user-attachments/assets/d0a5043d-e55f-45dc-9dfe-ed8b6497fbdb" />


Step 3：選擇 2.0.4\_0 資料夾  
Step 3：Select the 2.0.4\_0 folder  
----------------------

選擇 `2.0.4_0` 資料夾，然後按「選擇資料夾」。  
Select the `2.0.4_0` folder, then click “Select folder”.  

<img width="1173" height="710" alt="3" src="https://github.com/user-attachments/assets/d45e9cf2-566b-45a1-9801-200de9f8b34a" />


Step 4：安裝 Ollama    
Step 4：Install Ollama  
----------------

前往 Ollama 官方網站下載並安裝 Ollama。  
Go to the official Ollama website to download and install Ollama.  

<img width="996" height="672" alt="4" src="https://github.com/user-attachments/assets/fc1bd452-e492-45d1-aabe-665dce5c9b88" />


Step 5：安裝 Python  
Step 5：Install Python  
----------------

前往 Python 官方網站下載並安裝 Windows 版本。  
建議安裝時勾選 `Add Python to PATH`。  
Download and install the Windows version from the official Python website.  
We recommend checking `Add Python to PATH` during installation.  



<img width="1381" height="751" alt="5" src="https://github.com/user-attachments/assets/eefc35bb-35c3-4917-bee5-1b018b0bef00" />


Step 6：開啟 PowerShell  
Step 6：Open PowerShell  
--------------------

Python 和 Ollama 安裝完成後，開啟 Windows PowerShell。  
After installing Python and Ollama, open Windows PowerShell.  


<img width="482" height="259" alt="6" src="https://github.com/user-attachments/assets/0f8e507e-2112-40e1-99b7-98b8902ef5bb" />


Step 7：安裝需要的 Python 套件  
Step 7：Install the required Python packages  
----------------------

在命令提示字元或 PowerShell 裡執行以下指令：  
Run the following commands in Command Prompt or PowerShell:  

`pip install numpy`

`pip install websockets`

`pip install faster-whisper`

<img width="654" height="511" alt="7" src="https://github.com/user-attachments/assets/665845db-48b0-47c5-a66a-fe5a47b0a68e" />


Step 8：下載 Ollama 模型  
Step 8：Download Ollama model(s)  
-------------------

在 PowerShell 輸入以下指令：  
Enter the following command in PowerShell:  

`ollama pull qwen2.5:3b-instruct`

<img width="842" height="363" alt="10" src="https://github.com/user-attachments/assets/870605f7-43e6-475b-9dfa-1af56494c83d" />


Step 9：啟動 Ollama  
Step 9：Start Ollama  
----------------

從開始選單搜尋 Ollama，並啟動 Ollama。  
Search for Ollama from the Start menu and start it.  

<img width="1920" height="1080" alt="11" src="https://github.com/user-attachments/assets/943fa1dc-4875-4864-92cd-c860a85b8b5e" />


Step 10：執行 launch.bat  
Step 10：Run launch.bat  
---------------------

進入 `Local Voice Ollama / 2.0.4_0` 資料夾，執行：  
Go to `Local Voice Ollama / 2.0.4_0` folder and run:  

`launch.bat`

<img width="1920" height="1080" alt="11-2" src="https://github.com/user-attachments/assets/890ea02a-080f-4a3f-a830-b6499a893bd0" />


Step 11：開啟擴充功能面板  
Step 11：Open the extension panel  
----------------

在 Chrome 右上角點擊 Local AI Subtitle / Local Voice Ollama 的擴充功能圖示，開啟面板。  
如果右側或命令列開始出現字幕 / 文字輸出，代表服務已經啟動成功。  
  
Click the Local AI Subtitle / Local Voice Ollama extension icon in the top-right corner of Chrome to open the panel.  
If subtitles / text output starts appearing on the right side or in the command line, it means the service has started successfully.  

<img width="1784" height="1226" alt="12" src="https://github.com/user-attachments/assets/4303f1b9-45d8-4a80-89ca-44cdf3a68c61" />


Local Voice Ollama Guide  
