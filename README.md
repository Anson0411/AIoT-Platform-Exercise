# AIoT-Platform-Exercise
## AIoT-Platform GCP - 即時影像辨識 

```mermaid
graph TD;
    相機-->AI影像辨識 邊緣;
    AI影像辨識 邊緣-->發布警訊;
    AI影像辨識 邊緣-->雲端保存 GCP;
    AI影像辨識 邊緣-->影像串流;
```

### 利用GCP創建虛擬機
### (本機)連線至虛擬機 - SSH  (或是直接從網頁進入)

1. 建立key

`$ ssh-keygen` 

`$ cat C:\Users\{username}/.ssh/id_XXXXX.pub`

2. 在GCP的安全殼層金鑰，新增項目，貼上上個步驟的內容
   
3. 在本機輸入虛擬機外部IP連線

`$ ssh {外部IP}`
   



