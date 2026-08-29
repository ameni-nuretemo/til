# ImageMagickの使い方

## インストール

```powershell
winget install ImageMagick.ImageMagick
```

## 使いかた

```powershell
magick input.png -quality 90 output.jpg
```

## まとめて変換
```powershell
Get-ChildItem *.png | ForEach-Object {
    magick $_.FullName -quality 90 ($_.DirectoryName + "\" + $_.BaseName + ".jpg")
}
```
