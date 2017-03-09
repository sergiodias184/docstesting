VisionSpace
===================
The script **converter.py** allows you convert any docx file into a Markdown file and any PDF file into a Markdown, text and HTML file. 

### System Requirement
- Python installation

- Pandoc:
>wget https://github.com/jgm/pandoc/releases/download/1.19.2.1/pandoc-1.19.2.1-1-amd64.deb
>sudo dpkg -i pandoc-1.19.2.1-1-amd64.deb
- pdf2htmlex:
>sudo apt install pdf2htmlex 

- pdfminer:
Download the source code through the following link and unpack it. 
https://pypi.python.org/packages/57/4f/e1df0437858188d2d36466a7bb89aa024d252bd0b7e3ba90cbc567c6c0b8/pdfminer-20140328.tar.gz#md5=dfe3eb1b7b7017ab514aad6751a7c2ea
In the pdfminer folder: 
> python setup.py install

> **Note:** The files **converter.py** and **main.py** have to be in the same directory as well the folder **pdf2md** 



