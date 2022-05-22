# 🔎 TikTok Username Checker
• A proxyless username checker for TikTok to check available usernames in bulk.
• Works with Windows and MacOS (not tested on Linux)
• Allows you to check thousands of usernames at a fast speed!

# 🛠 Installation
(Python is required to use this program. You can [install it here]([https://www.python.org/downloads/]).)
1. Download the [.zip file]([https://www.python.org/downloads/]) and extract it into a folder
2. Install the required modules by running `python3 -m pip install requirements.txt` in your Command Prompt/Terminal. 
3. Insert your usernames inside of the `usernames.txt` file. 
4. Run the python by executing the command `python3 main.py` in your Command Prompt/Terminal. 
5. Choose the amount of threads. You can only use 5 or below to prevent TikTok from ratelimiting your IP.
6. All available usernames will be sent into a text file named `Available.txt`

If you run into any errors, please [report it here]([https://www.python.org/downloads/]).

# 📝 Notes
• May not work on Linux (untested)
• If you are on MacOS, do the instructions above but replace `main.py` with `macos.py`. It is the same script but without the stats feature.
• Do not go above 5 threads as TikTok may limit or ban your IP.
• The usernames that are marked as Available may not all be available, they could be banned. 
• Since this isn't using TikTok's API, the results may be inaccurate but from most tests, this program works. 
