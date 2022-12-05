常用CMD指令：
1.系統校時查詢:w32tm /query /status
2.查詢網域使用者狀態
net user <username> /domain
ex:net user louis0512 /domain
3.系統檔案掃描修復(需管理員)
sfc scannow
4.查詢該電腦目前使用者帳戶
wmic/node:<電腦名稱> computersystem  get  username
5.系統狀態查詢
systeminfo   (查詢本機)
systeminfo /s <電腦名稱>    (查詢遠端電腦)
6.GPO狀態查詢
gpresult /z
7.GPO 政策更新
gpupdate /force
