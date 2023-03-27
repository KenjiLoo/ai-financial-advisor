# 🤜 TO RUN THE SOFTWARE 🤛

## Create a JSON 📑
1) Create a JSON file containing your ChatGPT session-token 
2) Name it "GPT_SECRET_KEY.json"
3) The file should look like: `{ "API_KEY": "your session token here" }`
4) You can get your ChatGPT session token from:
  - Go to ChatGPT (Make sure it is producing prompts)
  - Right click > inspect element
  - Click on Application > Cookies > https://.......
  - Your session token as the first value that pops up
  - ![image](https://user-images.githubusercontent.com/80972386/227776185-74947a22-77f7-4413-b257-7ed4fa520fce.png)
5) Put the file into Google Colabs like this: 
  - ![image](https://user-images.githubusercontent.com/80972386/227776965-c8124a2b-a1a1-473d-8547-14a20ab8e7de.png)


## Get your OpenAI API-Key 🗝
1) Go to: https://platform.openai.com/account/api-keys
2) Click on "Create new secret key" 
3) This will be your API-Key
  - ![image](https://user-images.githubusercontent.com/80972386/227776824-b84abaff-c51c-4787-8130-69b47e5e71ed.png)
4) Insert this key into the `openai.api_key = "insert your key here"` under the section "IMPORTS"

## Start having fun! 🥳
1) Make sure your Google Colabs is connected to a GPU
2) You can click on Session > Run all cells 
3) The interface will look like this
![image](https://user-images.githubusercontent.com/80972386/227777114-cc3749d1-51b5-473c-95dd-cabd67055fa3.png)

Credits to: Bhavesh Bhatt on youtube ****


