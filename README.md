# YOUTUBE DOWNLOADER PRO v6.1.0

Sistema automatizado para download de playlists do YouTube em MP3, com processamento paralelo, recuperação automática e organização inteligente por artista.

## ✨ Recursos

* 🎵 Conversão automática para MP3
* 🖼️ Incorporação de capas e metadados
* ⚡ Downloads paralelos
* 🔄 Recuperação automática após interrupções
* 🚫 Prevenção de downloads duplicados
* 🍪 Detecção automática de cookies do navegador
* 📊 Dashboard em tempo real no terminal
* 📁 Organização automática por artista
* 📄 Relatórios automáticos em HTML, JSON e TXT

---

## 🛠️ Requisitos

Antes de começar, instale:

* Python 3.12 ou superior
* FFmpeg configurado no `PATH` do sistema

Verifique a instalação do FFmpeg:

```bash
ffmpeg -version
```

---

## 💻 Ambiente Recomendado

Recomendamos utilizar o **PyCharm Community Edition** para facilitar a instalação, configuração e execução do projeto.

Alternativas compatíveis:

* Visual Studio Code
* Thonny
* IDLE

---

## 📂 Estrutura do Projeto

```text
YOUTUBE DOWNLOADER PRO v6.1.0/

├── downloader.py
├── requirements.txt
├── LICENSE
└── README.md
```

---

## 🚀 Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/youtube-downloader-pro.git
```

### 2. Entre na pasta do projeto

```bash
cd youtube-downloader-pro
```

### 3. Crie um ambiente virtual (opcional)

#### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

#### Linux e macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 4. Instale as dependências

```bash
pip install -r requirements.txt
```

### 5. Execute o programa

```bash
python downloader.py
```

Na primeira execução, o programa solicitará a pasta de destino e criará automaticamente toda a estrutura necessária.

---

## ⚙️ Configuração

Você precisa editar apenas um arquivo:

```text
Config/playlists.txt
```

Formato:

```text
# Artista|URL

Imagine Dragons|https://www.youtube.com/playlist?list=XXXX

Coldplay|https://www.youtube.com/playlist?list=YYYY
```

### Regras

* Linhas iniciadas com `#` serão ignoradas.
* Linhas vazias serão ignoradas.
* Utilize `|` para separar o artista da URL.

Nenhuma outra configuração é necessária.

---

## ▶️ Como Usar

1. Execute o programa.
2. Escolha a pasta onde os arquivos serão salvos.
3. Edite o arquivo `Config/playlists.txt`.
4. Adicione os artistas e as URLs das playlists.
5. Salve o arquivo.
6. Execute o programa novamente.

Pronto.

---

## 📁 Estrutura Criada Automaticamente

```text
Downloads/
Logs/
Reports/
Backups/
Database/
Config/
```

---

## ⚠️ Observações

* O FFmpeg é obrigatório para a conversão de áudio.
* O programa utiliza a biblioteca `yt-dlp`.
* Downloads interrompidos são retomados automaticamente.
* Vídeos já baixados não serão baixados novamente.

---

## 📄 Licença

Copyright (c) 2026 Geilson Labs Projects.

Este projeto está licenciado sob uma licença personalizada de uso não comercial.

É permitido utilizar, modificar e distribuir este software exclusivamente para fins pessoais, educacionais e não comerciais.

O uso comercial, total ou parcial, é proibido sem autorização prévia e por escrito da Geilson Labs Projects.

Consulte o arquivo `LICENSE` para obter os termos completos.

---

## ⚖️ Aviso Legal

Este projeto é fornecido apenas para fins pessoais e educacionais.

O usuário é responsável por cumprir os termos de serviço do YouTube e a legislação de direitos autorais aplicável em sua região.
