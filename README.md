<h1 align="center">
  <br>
  <a href="https://github.com/mkdirlove/chatgpt-desktop"><img src="https://github.com/mkdirlove/chatgpt-desktop/blob/main/icon.png" height="150px" width="150px" alt="chatgpt-desktop"></a>
  <br>
  ChatGPT Desktop Client
  <br>
</h1>

### Windows Installation
Building the app manually
```
git clone https://github.com/mkdirlove/chatgpt-desktop.git
```
```
cd chatgpt-desktop
```
```
python3 -m pip install -r requirements.txt
```
Create new viertual environment
```
virtualenv venv
```
Enable virtual environment in Windows
```
.\venv\Scripts\activate
```
Enable virtual environment in GNU/Linux
```
source venv/bin/activate
```
Now install your project's dependencies in this new environment:
```
python3 -m pip install -r requirements.txt
```
Building an EXE package
```
pyinstaller --onefile chatgpt-desktop
```

Go to release page or click
[Download Here.](https://github.com/mkdirlove/chatgpt-desktop/releases/download/v1.0.0/chatgpt-desktop_x64)

### Linux Installation
Manual package installation or [Download Here.](https://github.com/mkdirlove/chatgpt-desktop/releases/download/v1.0.0/chatgpt-desktop_x64.deb)
```
curl -O chatgpt.deb https://github.com/mkdirlove/chatgpt-desktop/releases/download/v1.0.0/chatgpt-desktop_x64.deb
```
```
sudo dpkg -i chatgpt.deb
```
```
sudo chmod +x /usr/bin/
```
Manually fix the execute permission.
```
sudo chmod +x /usr/bin/chatgpt-desktop
```

### Building GNU/Linux installation package
```
git clone https://github.com/mkdirlove/chatgpt-desktop.git
```
```
cd chatgpt-desktop
```
```
dpkg-deb --build chatgpt
```
### Preview
https://github.com/mkdirlove/chatgpt-desktop/raw/main/demo.mov

### ToDo
```
Fix execute permission for GNU/Linux
```
