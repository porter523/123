📄 .gitignore（可選）
如果你不想把某些暫存檔、壓縮檔或個人設定推送到 
# 忽略壓縮檔與暫存檔
*.zip
*.log
*.bak
Thumbs.db
.DS_Store

# PowerShell 執行記錄
*.ps1xml
*.pssc



如果你已經 clone 了你的 repo，可以這樣操作：

cd glowing-invention
git add .
git commit -m "Add Luen 系統最佳化工具包 v3.0"
git push origin main
