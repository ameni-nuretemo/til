# 最初の設定
```
sudo apt install git
git config --global user.name "ameni"
git config --global user.email "ameni@****"

# そのフォルダだけの場合はglobalを外す

ssh-keygen -t ed25519 -C "ameni@***"
# ファイルを変える場合は -F id_ed25519_****を使う

cat .ssh/id_ed25519.pub

```
