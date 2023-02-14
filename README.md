<div align="center" id="madewithlua">
    <img src="./resources/chatbot.png" width=200>
</div>

<h1 align="center">Scribe AI</h1>

<h4 align="center">
  <a href="https://github.com/ajikan/ScribeAI#-features">Features</a>
  ·
  <a href="https://github.com/ajikan/ScribeAI#-getting-started">Getting Started</a>
  ·
  <a href="https://github.com/ajikan/ScribeAI#%EF%B8%8F-support-and-gratitude">Support and Gratitude</a>
</h4>

<p align="center">
    <a href="https://github.com/ajikan/ScribeAI">
      <img src="https://img.shields.io/github/last-commit/ajikan/ScribeAI?style=for-the-badge&logo=github&color=7dc4e4&logoColor=D9E0EE&labelColor=302D41"/>
    </a>
    <a href="https://marketplace.visualstudio.com/items?itemName=AndrewZhang.scribeai">
      <img src="https://img.shields.io/visual-studio-marketplace/v/AndrewZhang.scribeai?style=for-the-badge&logo=gitbook&color=8bd5ca&logoColor=D9E0EE&labelColor=302D41"/>
	</a>
    <a href="https://github.com/ajikan/ScribeAI">
      <img src="https://img.shields.io/github/stars/ajikan/ScribeAI?style=for-the-badge&logo=apachespark&color=eed49f&logoColor=D9E0EE&labelColor=302D41"/>
    </a>
    <br>
    <a href="https://marketplace.visualstudio.com/items?itemName=AndrewZhang.scribeai">
      <img src="https://img.shields.io/visual-studio-marketplace/stars/AndrewZhang.scribeai?style=for-the-badge&logo=visualstudiocode&color=ee99a0&logoColor=D9E0EE&labelColor=302D41"/>
    </a>
    <a href="https://marketplace.visualstudio.com/items?itemName=AndrewZhang.scribeai">
      <img src="https://img.shields.io/visual-studio-marketplace/d/AndrewZhang.scribeai?style=for-the-badge&logo=webpack&color=cba6f7&logoColor=D9E0EE&labelColor=302D41"/>
    </a>
</p>

<p align="center">
Scribe AI is a ChatGPT-like extension for VS Code. Now you can have an AI chatbot like ChatGPT right in VS Code! Use it as your AI programming assistant which you can talk with to understand complex code, modify and improve your code, or generate comments for your code. The possibilities are endless. To start, highlight a piece of code and click on the plus icon on the left to open up a chat and start talking with Scribe AI just like in ChatGPT! All your conversations are saved in your workspace so you can look back on them as notes.
</p>

<h4 align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=AndrewZhang.scribeai">🔗 VSCode Marketplace</a>
</h4>

&nbsp;

# 📢 v1.1.3 Update
- With latest VSCode 1.75.0 update a bug has been introduced where the highlighted code couldn't be retrieved via vscode API. This bug has now been fixed and "Ask AI" and "AI Edit" extension features should be working now in latest v1.1.3. 

- The leaked ChatGPT model has been taken down by OpenAI and it is no longer available. Only the GPT3 models are available for now.

- The GPT3 models are also now more performant thanks to experimentation with prompt engineering and tuning additional parameters. You can now expect to get longer and more detailed responses.


&nbsp;

# 🌟 Preview
<p align="center">
  <img src="./previewDemo.gif" />
</p>

&nbsp;

# ✨ Features
-	💬 **Ask AI:** Highlight a piece of code, click on the chat icon, and type in any questions you might have about the code such as `Explain the code`. Then hit `Ask AI` button! The AI will respond back to you with the response. You can continue to reply to the AI’s response and hold a conversation with the AI just like in ChatGPT! The conversation context is maintained between queries. The conversation will be saved in your workspace and you can close it and open it anytime. You can also edit your comments and delete them. 

<p align="center">
  <img src="./previewDemo.gif" />
</p>

***Editing:***

<p align="center">
  <img src="./editComment.gif" />
</p>

&nbsp;

-	🧠 **AI Edit:** Highlight a piece of code and click on the chat icon, then enter the instruction on how you want the AI to modify the code such as `Refactor the code to include comments`, `Rewrite the code in Python`, and much more! The possibilities are endless. Now finally hit `AI Edit` button and you will see that your selected code has been modified. If you don’t like the result you can always Undo it by pressing `Mac:` <kbd>⌘ Command</kbd> + <kbd>Z</kbd>, `Windows:` <kbd>Ctrl</kbd> + <kbd>Z</kbd> or go to `Edit -> Undo`. Sometimes the formatting of the result is not correct or your originally highlighted section gets messed up, in such cases you can rehighlight the code and ask AI to `Reformat the code so that it’s correct` and press the `AI Edit` button.

***Refactoring:***
<p align="center">
  <img src="./aiEdit.gif" />
</p>

***Rewriting in another lanugage:***
<p align="center">
  <img src="./aiEditPython.gif" />
</p>

***Adding docstring:***
<p align="center">
  <img src="./aiEditDocstring.gif" />
</p>

***Fixing mistakes:***
<p align="center">
  <img src="./aiEditFixMistake.gif" />
</p>

&nbsp;

-	📝 **Note Taking:** You can also add notes inside your conversation by typing your note and pressing `Create Note`. Your notes won’t get sent over to AI.
<p align="center">
  <img src="./createNote.gif" />
</p>

&nbsp;

# 🚀 Getting Started
## 📦 Installation
- To use this extension, you can either install it from the VSCode marketplace or download and install `.vsix` file from Releases.

### 📑 Download extension from VSCode Marketplace
- Click on the Extensions icon(Ctrl+Shift+X)

- Search for "Scribe AI"

- The extension on VSCode marketplace looks like this, click the install button.

	![image](https://user-images.githubusercontent.com/26835888/218777021-59781cc1-788d-47e5-93bd-be1f8336f3ec.png)

- Once installation is complete, go to settings and search for "scribe AI" to add your OpenAI API key, when you install and use ScribeAI for the firsttime, it will ask you for your OpenAI API key. This is used by the extension to access the API and is only sent to OpenAI.

	![OpenAI](https://user-images.githubusercontent.com/26835888/218778164-1dbc6040-d44f-46be-b4a0-45baf4779e1c.jpg)

- When you are done adding the API key; reload/restart the extension to apply the changes

- Go to the explorer in VSCode and open any file that you want to work on or edit. 

- Inside the open or active editor click the ` + ` icon that often appears on the left

- When you first use ScribeAI whether by `Ask AI` or `AI Edit`, it will ask you for your OpenAI API key. This is used by the extension to access the API and is only sent to OpenAI.
<p align="center">
  <img src="./apiKeyInput.png" />
</p>

### 📑 Download and install `.vsix` file from Releases.
- Click on releases tab.

- You are redirected to a page that looks like this; Click on the preferred zipped file format; and download 

	![image](https://user-images.githubusercontent.com/26835888/218781965-cce59390-fb10-42c0-9d88-d7444ead98cd.png)

- Unzip the downloaded file, and open the folder with VSCode 

- Go through the process elaborated above to add your OpenAI API key and setup ScribeAI for the first time


## ⚙️ Settings
- You can also change your API key in User Settings via `Code` -> `Preferences` -> `Settings` and under `Extensions` you will find `ScribeAI` settings. Or you can just search `ScribeAI` in search box.
<p align="center">
  <img src="./userSettings.png" />
</p>

### 🗝️ To find your OpenAI API key:
1. Go to https://beta.openai.com/account/api-keys. You will need to log in (or sign up) to your OpenAI account.
2. Click "Create new secret key", and copy it.
3. You should then paste it into VS Code when prompted.


- If you wish to change the AI model you use which by default is `code-davinci-002` (because it’s free currently), then you can change it in User Settings.
- 💥 Remember to restart your extension and workspace when you change your settings. You can do that by clicking on `restart your extension` in the API key settings 💥


&nbsp;

> **Note**  
> Temporarily, the extension is using Codex, a similar GPT model by OpenAI, instead of ChatGPT, since the official ChatGPT API is not out yet. We do this because using unofficial ChatGPT API is unsupported by OpenAI and it's not reliable. Our team has figured out a way to simulate ChatGPT using OpenAI's current available GPT models. You can choose between `code-davinci-002` and `text-davinci-003` in the User Settings. When the official ChatGPT API is out our team will immediately offer an option to choose the ChatGPT model. 
> UPDATE: ChatGPT API is now out and we've added it to our extension. You can now find it in the settings to start using it!

&nbsp;

# ❤️ Support and Gratitude
- This wouldn't have been possible without OpenAI's API to access its AI services.
- I want to thank the wonderful VS Code community and all the developers that maintain VS Code.
- If you like this extension and found it useful, please consider donating me as I am only a new grad developer and any amount of donation will be of tremendous help and encourage me to keep going.
- <a target="_blank" href="https://icons8.com/icon/uZrQP6cYos2I/chatbot">Chatbot icon by Icons8</a>

&nbsp;

<p align="center">
<a href='https://ko-fi.com/C0C0I5XTZ' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi1.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
</p>

&nbsp;

<p align="center">Copyright &copy; 2022-present Scribe AI Team</p>
