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

### ตัวอย่าง Go
```
# Binaries for programs and plugins
*.exe
*.exe~
*.dll
*.so
*.dylib

# Test binary, built with `go test -c`
*.test

# Output of the go coverage tool, specifically when used with LiteIDE
*.out

# Dependency directories (remove the comment below to include it)
# vendor/
```

### เว็บ gitignore.io
หรือเราจะใช้เว็บ http://gitignore.io ช่วย generate ไฟล์ .gitignore ก็ได้
![เว็บ gitignore.io](https://github.com/golfz/mastering-gitignore/blob/master/img/gitignore_io.png)

ซึ่งจะได้ gitignore มาให้เราใช้ ดังนี้
```

# Created by https://www.gitignore.io/api/go,windows,visualstudiocode
# Edit at https://www.gitignore.io/?templates=go,windows,visualstudiocode

### Go ###
# Binaries for programs and plugins
*.exe
*.exe~
*.dll
*.so
*.dylib

# Test binary, built with `go test -c`
*.test

# Output of the go coverage tool, specifically when used with LiteIDE
*.out

# Dependency directories (remove the comment below to include it)
# vendor/

### Go Patch ###
/vendor/
/Godeps/

### VisualStudioCode ###
.vscode/*
!.vscode/settings.json
!.vscode/tasks.json
!.vscode/launch.json
!.vscode/extensions.json

### VisualStudioCode Patch ###
# Ignore all local history of files
.history

### Windows ###
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

# End of https://www.gitignore.io/api/go,windows,visualstudiocode
```
