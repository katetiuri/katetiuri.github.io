# katetiuri.github.io

### How to resize an image
```
docker run -v /path/in/local:/path/in/container jrottenberg/ffmpeg -i /path/in/container/image.jpg -vf scale=1920:-1 /path/in/container/image-resized.jpg
```