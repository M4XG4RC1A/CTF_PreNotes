# Cripto
No hacer propia crypto

## Cifrados comunes
> Caesar
Cifrado simple mover caracteres (a en 3 es d)
> Vigenere

> XOR
> Sustitucion
CCN-CERT Mayusculas, Cifrado por sustitucion deducir palabras para ver como 
> RSA
> Salsa20/ChaCha20
> AES
> Blowfish
> PGP simetrico
greps para rockyou
```console
egrep -v '([letras])[letras]*\1' ~/doc.txt | egrep '*(.)6,7$' > lista
-v (Excluir)
longitud
```

use john
Archivo para john
```console
~/snap/john-the-ripper/459/run/gpg2john message-2def3de75a007fa096097626a097930.asc > readyforjohn
message... File.asc
```

```console
john -wordlist:lista readyforjohn
```
## CyberChef
https://gchq.github.io/CyberChef/

## Ver longitud
```console
wc -l doc
```

# Estenografia
hide stenography

hide content in content with whitespace (lenguaje)
open file in nano

> Image in Image
> Image in file
> Message in Image
> Message in Sound
> Message in Video
> Message in Message

## DockerHelp
https://github.com/DominicBreuker/stego-toolkit

## Download image or video

## VLC
Open video on VLC and convert to audio if you think is audio

## Sonic visualizer
Use for audio 
Layer > Add new spectrogram

## Steghide
Image or audio 
```console
steghide extract -sf steg.jpg -p password -xf output.txt
password wordYou think
Can give a new thing
```

## Steghide
Image or audio 
```console
cat file | base64 -d | file -
if enc data with salted password other
```

## exiftool
Obtain a password autor
```console
exiftool file
```

## openssl
decifrate
```console
cat file | base64 -d > fileClear
openssl enc -d -aes256 -md -md5 fileClear -out outputName
```

## vlc
decifrate
```console
file outputName
vlc outputName
```

# Imagen
## unzip
try with image
```console
unzip imageName
```

Despues de PK tenemos informacion

https://www.youtube.com/watch?v=LsDOpDQtu_8