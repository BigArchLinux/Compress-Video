Uso:

./converter-v2.sh <input_file_or_directory> <target_size_in_MB> [options]


### Opções:

- -v video_codec: Especifica o codec de vídeo a ser usado. Padrão: libx264.
- -a audio_codec: Especifica o codec de áudio a ser usado. Padrão: aac.
- -p passes: Especifica o número de passagens para a codificação. Padrão: 2.
- -f framerate: Define a taxa de quadros (framerate) do vídeo codificado.
- -r resolution: Define a resolução do vídeo codificado, por exemplo, 1920x1080.

### Exemplos:

1. Codificar um vídeo para 15MB:

./converter-v2.sh video.mp4 15


2. Codificar todos os vídeos de um diretório para 20MB com codec de vídeo libx265:

./converter-v2.sh /path/to/directory 20 -v libx265


3. Codificar um vídeo para 10MB com 24fps e resolução de 1280x720:

./converter-v2.sh video.mp4 10 -f 24 -r 1280x720

4. Codificar pasta inteira

./converter-v2.sh '/home/Usuario/Downloads/Pasta' 100

---

![image](https://github.com/Glorioso-Tv/Compress-Video/assets/61152842/ffbc057d-752c-4845-b47d-4c8b041c8460)

