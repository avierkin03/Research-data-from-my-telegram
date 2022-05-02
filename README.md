# Researching data from my telegram
In this work I analyzed my behavior in the telegram. Using information about messages, groups, chats from my telegram, I made a visualization of some questions that statistically show data about me as a user of this messenger (file *'code.ipynb'*).
## Instruction to reproduce
*To collect your Telegram data*:
  1. install dependencies *`pip install -r requirements.txt`*
  2. get your credentials https://my.telegram.org/apps
  3. set credentials (api_id, api_hash) in config/config.json (can be based on the config_example.json)
  4. Get *'0_download_dialogs_list.py'* and *'1_download_dialogs_data.py'*
  5. Download all dialogues *`python 0_download_dialogs_list.py --dialogs_limit -1`*
  6. Download dialogues data *`python 1_download_dialogs_data.py --dialogs_ids -1 --dialog_msg_limit 100000`* <br>
  7. Specify where you saved *'dialogs_data_all.csv'* and *'dialogs_users_all.csv'* in *'code.ipynb'* <br>
    `DIALOGS_MERGED_DATA_ALL_PATH = "/your path/dialogs_data_all.csv"` <br>
    `DIALOGS_MERGED_DATA_USERS_ALL_PATH = "/your path/dialogs_users_all.csv"`


## Some visualization examples
![image](https://user-images.githubusercontent.com/93377331/166219509-d6c0a000-0f66-4cfe-8a4e-9b3457ae5bb3.png)
![image](https://user-images.githubusercontent.com/93377331/166219640-fce4f6cd-03b3-4559-81e0-0430a6324bb9.png)
![image](https://user-images.githubusercontent.com/93377331/166219670-fcb98db7-6aaa-460a-8ee6-29a727adc16c.png)
![image](https://user-images.githubusercontent.com/93377331/166219683-58e83048-fe55-46ac-8c23-4ffe2f4573e1.png)
![image](https://user-images.githubusercontent.com/93377331/166219694-b0c503a0-d00b-4e46-8d72-8c597f9d55a4.png)
![image](https://user-images.githubusercontent.com/93377331/166219722-b7a5b13b-783f-4ee1-bb1b-935ef7498425.png)
![image](https://user-images.githubusercontent.com/93377331/166219823-e65cc50d-e2e7-4e07-9095-5a6a02fe9957.png)
![image](https://user-images.githubusercontent.com/93377331/166219830-73d047bf-0c01-4a90-a813-aab4b63540b0.png)
![image](https://user-images.githubusercontent.com/93377331/166219755-3e6982e4-c8ea-4421-941d-b2baf20e5fc9.png)
![image](https://user-images.githubusercontent.com/93377331/166219801-977f9b45-905a-4b75-811a-32f28a3784c7.png)







