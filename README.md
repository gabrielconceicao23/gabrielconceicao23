<h1 align="center">Olá, eu sou o Gabriel Conceição 👋</h1>

<p align="center">
  Desenvolvedor Full Stack • Entusiasta de Robótica • Instrutor de Tecnologia
</p>

---

## 👨‍💻 Sobre mim

- 🔧 Trabalho com **web design, programação, redes, robótica e manutenção de computadores**
- 🧠 Gosto de criar soluções tecnológicas usando **HTML, CSS, JavaScript, Python, C++ e Arduino**
- 🎓 Formação em **Tecnologia da Informação**
- 🧑‍🏫 Instrutor de TI (2017 - 2025)
- 🌍 Idiomas: Inglês (básico) e Espanhol (intermediário)

---

## 🛠️ Tecnologias e Ferramentas

![HTML](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=fff&style=flat)
![CSS](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=fff&style=flat)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=000&style=flat)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=fff&style=flat)
![C++](https://img.shields.io/badge/-C++-00599C?logo=c%2B%2B&logoColor=fff&style=flat)
![C#](https://img.shields.io/badge/-CSharp-239120?logo=c-sharp&logoColor=fff&style=flat)
![Shell](https://img.shields.io/badge/-Shell%20Script-4EAA25?logo=gnu-bash&logoColor=fff&style=flat)
![Arduino](https://img.shields.io/badge/-Arduino-00979D?logo=arduino&logoColor=fff&style=flat)
![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=000&style=flat)
![Blender](https://img.shields.io/badge/-Blender-F5792A?logo=blender&logoColor=fff&style=flat)
![GIMP](https://img.shields.io/badge/-GIMP-5C5543?logo=gimp&logoColor=fff&style=flat)
![Inkscape](https://img.shields.io/badge/-Inkscape-000000?logo=inkscape&logoColor=fff&style=flat)

---

## 📫 Contato

- ✉️ Email: gabrielcostac100@gmail.com
- ▷ [Youtube](https://www.youtube.com/c/GabrielConceicao)
- 💼 [LinkedIn](https://www.linkedin.com/in/gabriel-costac/)  
- 🌐 [Portfólio](https://ogdatecnologia.wordpress.com/)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=gabrielconceicao23&show_icons=true&theme=github_dark" alt="Gabriel Conceição GitHub stats" />
</p>


---

## 🧾 Script OCR para XLSX

Criei um script em Python para extrair texto de fotos e organizar em planilha Excel.

### Arquivos

- `ocr_para_xlsx.py`
- `requirements.txt`

### Instalação

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

> É necessário ter o **Tesseract OCR** instalado no sistema.

### Uso

Extrair de uma imagem:

```bash
python3 ocr_para_xlsx.py caminho/da/foto.jpg saida.xlsx
```

Extrair de todas as imagens de uma pasta:

```bash
python3 ocr_para_xlsx.py caminho/da/pasta resultado_ocr.xlsx
```

Escolher idioma do OCR:

```bash
python3 ocr_para_xlsx.py foto.jpg saida.xlsx --idioma por
```

A planilha gerada contém:
- Aba **linhas**: texto separado por linha reconhecida.
- Aba **texto_completo**: texto integral por imagem.
- Aba **tabela**: tentativa de separar colunas de itens em `produto`, `descricao`, `unidade`, `preco_normal`, `quantidade`, `valor_total` (ideal para listas como tabelas de pedidos).
