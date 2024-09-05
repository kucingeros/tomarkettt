
# TomarketBot
🖱️ clicker for [https://t.me/Tomarket_ai_bot](t.me/Tomarket_ai_bot/app?startapp=0000i73A)


# Functionality
| Functional                                                                      | Supported |
|----------------------------------------------------------------|:---------:|
| Auto Claim                                                     |     ✅     |
| Auto Play Game                                                 |     ✅     |
| Suppport Multi Account                                         |     ✅     |
| Proxy Support                                                  |     ✅     |

# Warning !
According to [Telegram TOS](https://core.telegram.org/api/obtaining_api_id#using-the-api-id) all accounts that sign up or log in using unofficial Telegram API clients are automatically put under observation to avoid violations of the Terms of Service.

So be careful, hopefully your account won't get banned.


## Settings data file
| Setting                      | Description                                                                                    |
|------------------------------|------------------------------------------------------------------------------------------------|
| query_id        | fill the `data.txt` file with your data, how to get data you can refer to [How to Get Data](#how-to-get-data)                      |




# Requirements
- Python 3.9 (you can install it [here](https://www.python.org/downloads/release/python-390/)
- How to Get Data (you can get them [here]((#how-to-get-data](https://github.com/kucingeros/tomarket))
  
Make sure you computer was installed python and git.

# Suggestion: Use python version 3.8+ (3.8 and above or latest)

python site : [here](https://python.org)

git site : [here](https://git-scm.com/)

# Clone this repository

	git clone https://github.com/kucingeros/tomarket

# goto tomarket directory

	cd tomarket
 
# install the require library

	python -m pip install -r requirements.txt

Edit data.txt, input you data token in data.txt, find you token in How to Find Account Token. One line for one data account, if you want add you second account add in new line!

# execute the main program

	python bot.py

# how to get app webdata telegram
right click on mini app> f12 or inspect element
go to console> type allow pasting
and copy paste> 
copy(Telegram.WebApp.initData)

*note: fill data.txt with query_id=xxx
