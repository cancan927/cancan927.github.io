# 多分支git工作流入门

## 无论你是参与开源项目还是公司项目，都建议使用这一套git工作流




### 1. 从远程pull代码

![image](https://github.com/user-attachments/assets/1c68c649-c37b-4c15-a0aa-867f602a28cc)

### 2. 本地创建新分支feature1

![image](https://github.com/user-attachments/assets/7cd14435-c8d8-48d4-bcd0-177b59fec34b)

### 3. 本地新分支feature1开发

![image](https://github.com/user-attachments/assets/cc9b4206-0e63-44dc-9061-b773fc7e763c)

### 4. 将本地新分支push到远端，同时发现远程master有新变化

![image](https://github.com/user-attachments/assets/c32341f0-29f6-4a63-87bc-af2cfbef7be4)

### 5. 本地切换到master分支，同步远端master的变化

![image](https://github.com/user-attachments/assets/532d2e67-edef-4401-8bba-059cb9874aef)

### 6. 回到feature1分支，同步远端master的变化

![image](https://github.com/user-attachments/assets/521ae903-dacd-4884-96b2-19bee2062e0b)

### 7. 将本地feature1的变化同步到远程feature1分支

![image](https://github.com/user-attachments/assets/c9788395-bb08-427f-8ce7-c025c4e6753e)

### 8. 创建pull request，将feature1分支的变化合入master分支

![image](https://github.com/user-attachments/assets/d074dd4b-1aae-496e-a07e-6103903df09a)

### 9. master维护者审查合格后，将feature1合入master分支

Squash and merge 扁平化合并，就是把feature1的多次提交合并成一次

![image](https://github.com/user-attachments/assets/e8ddd569-3880-43d4-b0cc-48233a4facde)

### 10. 删除远程feature1分支，然后删除本地feature1分支，切换到master分支，同步远端的变化

也可以不删除feature1分支，或者只删除远程不删除本地

![image](https://github.com/user-attachments/assets/fd0f4648-cbb3-4163-8f05-b2c8894f3b27)



