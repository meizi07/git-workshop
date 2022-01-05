# 12/25-26 Node.js心得
By MFEE22 陳玟靜

我覺得老師的教學很詳細，之前就有學過git，不過都沒有像這樣這麼深入的學習terminal的指令，透過老師的教學讓我對git更加熟練了，也算是又完完整整的複習一次！很喜歡老師的教學方式，教得非常仔細，個人覺得自己理解力算高但吸收速度很緩慢，有點金魚腦趨勢，但上過老師的課不僅印象更深刻，對教學內容也更加熟練了！


# 2021/12/26 node.js筆記
安裝網址 https://github.com/coreybutler/nvm-windows/releases

## nvm 指令

```bash=
# 查詢 nvm 指令
nvm ??

# 列出可以安裝的版本
nvm ls-remote 16
# windows版本
nvm list available

# 安裝最新版本號
nvm install 16.13.1

# 切換要使用的 node 版本
nvm use 16.13.1

# 確認目前執行的版本
node -v

# 列出你目前主機安裝的版本
nvm ls
# windows版本
nvm list   
```
github 作業
MFEE22 public

## 壓力測試
```bash=
console.time(n);//壓力測試
```

## big O
寫程式要考慮執行效率、可行性、擴充性、維護性

