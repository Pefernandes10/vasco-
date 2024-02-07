DEBIAN+ NEOFECTH 
 Exercicio 1: Criar um container com o Debian e que seja interativo, que dentro dele tenha o neofetch.
1. podman run -it debian /bin/bash
2. apt-get update && apt-get install -y neofetch
3. neofetch

DEBIAN + PYTHON 
  Exercicio 2: Criar um container com o Debian destacável, que tenha python.
1. podman pull debian
2. podman run -it debian
3. apt update && apt install python3 -y

 FEDORA + YT-DLP
  Exercicio 3: Criar um container fedora, interativo que tenha yt-dlp.
1. podman pull fedora
2. podman run -it fedora
3. sudo dnf update && dnf install python3
4. sudo dnf install yt-dlp

 


