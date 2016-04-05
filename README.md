# Media content for my github repos

## Instruction to create gif from video
[learnt from this gist](https://gist.github.com/dergachev/4627207)

ffmpeg -i in.mov -s 600x400 -pix_fmt rgb24 -r 10 -f gif - | gifsicle --optimize=3 --delay=3 > out.gif

