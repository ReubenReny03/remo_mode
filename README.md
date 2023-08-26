```
-----------------------------------------
 ______     _______    ______      _____
(_____ \   (_______)  |  ___ \    / ___ \
 _____) )   _____     | | _ | |  | |   | |
(_____ (   |  ___)    | || || |  | |   | |
      | |  | |_____   | || || |  | |___| |
      |_|  |_______)  |_||_||_|   \_____/
                                          
------------------------------------------
```

REMO MODE : A ALIAS AUTOMATION TOOL

**INSTALLATION**


---




Git clone [https://github.com/ReubenReny03/remo_mode-alias-manager.git](https://github.com/ReubenReny03/remo_mode-alias-manager.git)


unzip remo_mode-alias-manager


cd remo_mode-alias-manager


source installremo


**YOUR SYSTEM WILL REBOOT AFTER THIS DO NOT PANIC**


After reboot type “remo_mode” this should start the ReMo mode


**USAGE**




---


The main use of this is to make your life easy and make use of alias to make you feel like “its your own linux” if you are a student you can add all your needed






1. Classes link
2. Shortcut Folder Jumps
3. Shortcut open folder from terminal


**Configuration**




---


How much can you change this tool ?


There are 2 editing options in this tool






1. remo_edit_auto → to add more features to the automation
2. remo_edit_name →to change ReMo to your own name.


**Features**




---






1. Add links to open directly with a command
2. Open a folder directly with a command
3. Open file manager **(will change for different distributions)**




## **Getting Started**




---


We will discuss the following things work :
<ol>
<li> How to add link to a website</li>
<li>How to set a shortcut to a directory</li>
<li>How to open file manager at current position from the terminal</li>
</ol>


1.Let's say you want to add a shortcut link to google.com then
   <ol>
       <li>type "remo_edit_auto."</li>
       <li>Add the following line:
           <pre><code>alias {shortcut_name}="firefox {link}"</code></pre>
       </li>
       <li>Save the changes and then run "remo_mode" again.</li>
   </ol>


2.How to set a shortcut to a directory
  <ol>
       <li>type"remo_edit_auto "</li>
       <li>Insert the following line:
           <pre><code>alias {shortcut_name}="cd ~/{full path to directory}"</code></pre>
       </li>
       <li>Save the changes and then run "remo_mode" again.</li>
   </ol>
3.How to open file manager at current position from the terminal
   <ol>
       <li>Find the command to open the file manager at the current directory (e.g., "thunar" for Mint).</li>
       <li>type "remo_edit_auto."</li>
       <li>Add the alias with the correct command:
           <pre><code>alias {shortcut_name}="{your command}"</code></pre>
       </li>
       <li>Save the changes and then run "remo_mode" again.</li>
   </ol>
