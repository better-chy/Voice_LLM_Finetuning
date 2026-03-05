# Voice_LLM_Finetuning
- Qwen2.5-3B_xiaoming 为3b模型使用本地数据微调的模型, 效果比Qwen2.5-7B_xiaoming好
- 7b微调后任然多官方语言,而3b更加符合训练数据,口语好
- 训练使用显卡: NVIDIA GeForce RTX 4090 Laptop GPU 16 GB
- 训练用时: 
- - 3b: 1day
- - 7b: 3day
<img width="2075" height="1365" alt="bef1c9b93f96722b94b191aa1f7dc11" src="https://github.com/user-attachments/assets/27ce8b5e-e995-4c8a-9515-d691ebe9f7df" />

### 因github单个文件上传大小限制,两个模型均删除部分权重文件
<img width="1881" height="991" alt="image" src="https://github.com/user-attachments/assets/4d6460e8-3aba-4cfb-8ccb-34ffba681449" /> <img width="1557" height="821" alt="image" src="https://github.com/user-attachments/assets/586d69bd-549f-4661-a506-2fe03491c933" />

### 启动llama-factory的webui，部署模型后即可聊天，输入指令：llamafactory-cli webui
<img width="1593" height="827" alt="1772707160352" src="https://github.com/user-attachments/assets/0f8b3b4a-b23e-45d2-9e11-c20f73f0ea72" />
<img width="3183" height="1907" alt="2c051dba301d75cc1047f1d58eeb2b6" src="https://github.com/user-attachments/assets/7c8189e6-0302-4053-bf9d-9fcf7e0364a9" />
