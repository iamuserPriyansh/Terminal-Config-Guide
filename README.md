# Terminal Config
---
# Appereance

### Text

- **Terminal Size**
    
    Columns ↠ 80
    Rows ↠ 20
    
- **Font**
    
    Font Name ↠ [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)
    Font Size ↠ 13px
    
- **Cell Spacing**
    
    Width ↠ 1.00
    Height ↠ 1.00
    
- **Cursor**
    
    Cursor Shape ↠ Underline
    Cursor blinking ↠ Default
    
- **Sound**
    
    Terminal Sound ↠ Disabled
    

### Colors

- **Text and Background Color ↠ Custom**
   <a href="https://ibb.co/5cS1GjF"><img src="https://i.ibb.co/q1cD7g5/Color-Scheme.png" alt="Color-Scheme" border="0"></a><br>
    <a herf="">Color Code</a>
    
- **Palette ↠ Custom**
    
    <a href="https://ibb.co/Rh5DZGw"><img src="https://i.ibb.co/3fJCG5Z/Palette.png" alt="Palette" border="0"></a><br>
 <a herf="">Color Code</a>
### Scrolling

Show Scrollbar ↠ Disabled
Scroll on output ↠ Disabled
Scroll on keystroke ↠ Enabled
Limit scroll back to ↠  Disabled

---
# OhmyZSH

### Installation

```jsx
git clone https://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
```

### Themes

• Find the line ZSH_THEME="robbyrussell" replace `robbyrussell` with fino theme in `.zshrc` File (**CTRL + X & Enter to Save**)

<a href="https://ibb.co/p25NRVR"><img src="https://i.ibb.co/8MtGdvd/Theme.png" alt="Theme" border="0"></a><br>

### Plugins

open `Terminal` and go to `home directory` 

<a href="https://ibb.co/Jx1F7f2"><img src="https://i.ibb.co/bH0RBSL/ls.png" alt="ls" border="0"></a><br>

```jsx
cd .oh-my-zsh/custom/plugins
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git
git clone https://github.com/zsh-users/zsh-autosuggestions.git
```

• Find the line plugins=(

 and add the following lines in `.zshrc` File (**CTRL + X & Enter to Save**)

```
 sudo
web-search
copyfile
copybuffer
dirhistory
history
brew
vscode
xcode
torrent
toolbox
terraform
zsh-syntax-highlighting
zsh-autosuggestions
```

<a href="https://ibb.co/3cnNZQZ"><img src="https://i.ibb.co/x6NjTdT/Plugins.png" alt="Plugins" border="0"></a><br>

---
# HomeBrew

### Installation

go to `home directory` and open `terminal`

```jsx
git clone https://github.com/Homebrew/install.git
cd install && sudo bash ./install.sh
```

and follow the instruction. To verify homebrew is installed or not :

type “`brew config`" in terminal
