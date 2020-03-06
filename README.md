# mastering-gitignore

เบื้องต้นให้เข้าไปดูที่ https://github.com/github/gitignore ว่า ภาษาที่เราเขียน , IDE และ OS ที่เรากำลังใช้ เราควรต้อง ignore ไฟล์อะไรบ้าง

### ตัวอย่าง Windows
```
# Windows thumbnail cache files
Thumbs.db
Thumbs.db:encryptable
ehthumbs.db
ehthumbs_vista.db

# Dump file
*.stackdump

# Folder config file
[Dd]esktop.ini

# Recycle Bin used on file shares
$RECYCLE.BIN/

# Windows Installer files
*.cab
*.msi
*.msix
*.msm
*.msp

# Windows shortcuts
*.lnk
```

### ตัวอย่าง VS Code
```
.vscode/*
!.vscode/settings.json
!.vscode/tasks.json
!.vscode/launch.json
!.vscode/extensions.json
*.code-workspace
```
