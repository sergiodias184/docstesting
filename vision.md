Documents converter
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

### Docx
The script creates a new folder with the file name, and there are the Markdown file and their images.

### PDF
Sometimes PDF files have some restrictions, and the scrip starts to remove this restrictions and create a new file without them. The script also creates a folder with the file name and there are 3 files (Markdown,Text and HTML) and the extract images from the PDF.

**Usage**
=======
After you downloaded the project:
>git clone https://github.com/visionspacetec/papper.git
>cd papper 

Just type: 

>python converter.py  `<dir>`

where **`<dir>`** is the script input, that desfines the location containing the input files.



