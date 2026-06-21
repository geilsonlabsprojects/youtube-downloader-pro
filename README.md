# YOUTUBE DOWNLOADER PRO v6.1.0

Sistema automatizado para download de playlists do YouTube em MP3, com processamento paralelo, recuperação automática e organização inteligente por artista.

## ✨ Recursos

- 🎵 Conversão automática para MP3
- 🖼️ Incorporação de capas e metadados
- ⚡ Downloads paralelos
- 🔄 Recuperação automática após interrupções
- 🚫 Prevenção de downloads duplicados
- 🍪 Detecção automática de cookies do navegador
- 📊 Dashboard em tempo real no terminal
- 📁 Organização automática por artista
- 📄 Relatórios automáticos em HTML, JSON e TXT

---

## 📦 Download

Baixe a versão mais recente na página de Releases:

https://github.com/geilsonlabsprojects/youtube-downloader-pro/releases

Ou clone o repositório:

```bash
git clone https://github.com/geilsonlabsprojects/youtube-downloader-pro.git
```

---

## 🛠️ Requisitos

- Python 3.12 ou superior
- FFmpeg configurado no `PATH` do sistema

Verifique a instalação do FFmpeg:

```bash
ffmpeg -version
```

---

## 💻 Ambiente Recomendado

Recomendamos utilizar o **PyCharm Community Edition**.

Alternativas compatíveis:

- Visual Studio Code
- Thonny
- IDLE

---

## 🚀 Instalação

### 1. Entre na pasta do projeto

```bash
cd youtube-downloader-pro
```

### 2. Instale as dependências

```bash
pip install -r requirements.txt
```

### 3. Execute o programa

```bash
python downloader.py
```

Na primeira execução, o programa criará automaticamente toda a estrutura necessária.

---

## ⚙️ Configuração

Edite apenas o arquivo:

```text
Config/playlists.txt
```

Formato:

```text
# Artista|URL

Imagine Dragons|https://www.youtube.com/playlist?list=XXXX

Coldplay|https://www.youtube.com/playlist?list=YYYY
```

---

## 📁 Estrutura do Projeto

```text
youtube-downloader-pro/

├── downloader.py
├── requirements.txt
├── LICENSE
└── README.md
```

---

## ⚠️ Observações

- O FFmpeg é obrigatório para a conversão de áudio.
- O programa utiliza a biblioteca `yt-dlp`.
- Downloads interrompidos são retomados automaticamente.
- Vídeos já baixados não serão baixados novamente.

---

## 📄 Licença

Copyright (c) 2026 Geilson Labs Projects.

Este software é destinado exclusivamente ao uso pessoal, educacional e não comercial.

O uso comercial é proibido sem autorização prévia e por escrito.

Consulte o arquivo `LICENSE` para obter os termos completos.

---

## ⚖️ Aviso Legal

O usuário é responsável por cumprir os termos de serviço do YouTube e a legislação de direitos autorais aplicável em sua região.
