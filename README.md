# 考題吸血鬼(閃卡製作) AI應用規劃師

# 發想與設計

想考AI應用師，整理閃卡整理到很累，乾脆寫一個自己生產Obsidian中的.md  

# 程式運作

程式會問想要創建的資料夾名稱  
程式會讀取data資夾下的所有.json檔案，產出.md檔案並丟到目的資料夾  
至於如何整理成.json格式，我是叫GPT直接整理成目的規格  
prompt.txt是我給予的基本提示詞，但有時候還是會錯  
題目來源自：https://vocus.cc/article/67bc7d0efd89780001b4fd4c   

# 配套插件
我使用的是Obsidian的第三方插件 Spaced Repetition製作閃卡  
.md的設定格式主要是按照我的插件設定運作
![image](https://github.com/user-attachments/assets/26a31f5f-b260-49bd-899e-c668a41ecf00)


# 已知問題

由於是拿題目名稱建.md檔案
當題目名稱包含不能建檔的符號時會出錯  
ex. 在機器學習中，A/B測試常用於哪一方面？  
