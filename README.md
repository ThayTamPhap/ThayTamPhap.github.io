## MP3 to Opus (optimized for speech)

```sh
# brew install sox opus-tools
sox file.mp3 -t s16 --rate 32000 -c 1 - | opusenc --downmix-mono --bitrate 12  \
  --raw-rate 32000 --raw-bits 16 --raw-chan 1 - file.ogg
```

## Text-to-Speech

- https://vbee.vn/

- https://responsivevoice.org/


## Start a local server

```sh
ruby -run -e httpd . -p 3000
```


## Image optimized for web 

https://imageoptim.com/mac

## Results

png to lossy png  16% (16.6mb / 102.4mb) 1357 files

mp3 to opus (ogg) 42% (29.7mb /  69.0mb)
