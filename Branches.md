
# Git & GitHub 게임 답안지

## Branches

### 1. Moving through time
```
git checkout 97beddbdb3c6580e3a8967fdda5081c20d04f78e
git checkout Piggy_bank
//파일수정
git add .
git commit -m”Restore sisters peace.”
```
### 2. Make parallel commits
```
git checkout HEAD~2
//파일 수정
git add .
git commit -m"Lion gets something to eat."
```

### 3. Creating branches
```
git checkout c1d7ccb1329ff31cddca146cf8b3afbbbb0a6506
git branch birthday
git checkout b327110c1835a02329ed069d0935270e83151826
git branch concert

```
### 4. Branches grow with you!
```
git checkout birthday
//파일 수정
git add .
git commit -m”change ‘you’ file”
git checkout concert
//파일 수정
git add .
git commit -m”change ‘you’ file”
```
### 5. Deleting branches
```
git checkout 3cd30b5a87ae8210035fb43c0d5921b1426befad
git branch -D friend

git checkout 335f6e592254f33c296820f74c96b1830f8659b0
git branch -D ice-cream

git checkout 41814386f259dad490d82e627ff923856818bb07
git branch -D music
```
### 6. Moving branches around
```
git checkout donut
//파일 수정
git add .
git commit -m “You ate a donut."

git checkout baguette
git reset —hard  8cd8f7ec6ce7b12a57ccc9204a1f855eeec9c322

git checkout coffee
git reset --hard b54dae7eac18e9e8699625440a6d7c9cd7ed9089
```



