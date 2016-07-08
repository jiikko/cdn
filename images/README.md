# 画像が回転してしまう
```
convert -auto-orient -strip origin.jpg dist.jpg
```
# サイズかえつつ
```
convert -auto-orient -strip -resize 640x480 origin.jpg dist.jpg
```
