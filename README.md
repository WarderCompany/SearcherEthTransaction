# SearcherEthTransaction
React app, for search 5/10/15 Cards for eth wallet

## How to start

```
1. yarn install  
2. npm start
```
## Screens
![Screenshot](sample.jpg)


##Api, which i used
Test sample request :
```
http://api.etherscan.io/api?module=account&action=txlist&address=0x0fD081e3Bb178dc45c0cb23202069ddA57064258&sort=desc&apikey=YourApiKeyToken&offset=5&page=1
```

### Problems ?
if problems with users   
echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p