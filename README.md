# 🔎 TikTok Username Checker
• A proxyless username checker for TikTok to check available usernames in bulk. <br/>
• Works with Windows and MacOS (not tested on Linux) <br/>
• Allows you to check thousands of usernames at a fast speed! <br/>

# 🛠 Installation
(Python is required to use this program. You can [install it here]([https://www.python.org/downloads/]).)
1. Download the [.zip file]([https://www.python.org/downloads/]) and extract it into a folder
2. Install the required modules by running `python3 -m pip install -r requirements.txt` in your Command Prompt/Terminal. 
     - You can also run the automated bash file linked
     - For Windows, simply open the .bat file and it will install the required modules.
     - For macOS, open Terminal and cd into the extracted zip folder, then drag the install requirements .sh file into Terminal and press enter
     - For macOS, you can also watch the instruction video I included.
3. Insert your usernames inside of the `usernames.txt` file. 
4. Run the python by executing the command `python3 main.py` in your Command Prompt/Terminal. 
5. Choose the amount of threads. You can only use 5 or below to prevent TikTok from ratelimiting your IP.
6. All available usernames will be sent into a text file named `Available.txt`

If you run into any errors, please [report it here]([https://www.python.org/downloads/]).

# 📝 Notes
• May not work on Linux (untested) <br/>
• If you are on macOS, run the python file with the (macOS) parentheses. It is the same script but without the stats feature. <br/>
• Do not go above 5 threads as TikTok may limit or ban your IP. <br/>
• The usernames that are marked as Available may not all be available, they could be banned. <br/>
• Since this isn't using TikTok's API, the results may be inaccurate but from most tests, this program works. <br/>
