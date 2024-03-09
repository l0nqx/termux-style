## Welcome to my Termux Style

<p align="center"><img src="https://raw.githubusercontent.com/l0nqx/termux-style/main/images/img1.png"</p>

## **1. Installation**

```
pkg install zsh git
```

```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

<p align="center"><img src="https://raw.githubusercontent.com/l0nqx/termux-style/main/images/img3.png"</p>

```
nano ~/.zshrc
```

Change it to this **ZSH_THEME="agnoster"**

<p align="center"><img src="https://raw.githubusercontent.com/l0nqx/termux-style/main/images/img4.png"</p>

Go end & add this,

```
prompt_context(){ prompt_segment black default your-text }
```

<p align="center"><img src="https://raw.githubusercontent.com/l0nqx/termux-style/main/images/img5.png"</p>

```
mkdir -p ~/.termux
```

## **2. Themes & Fonts**

• First, We need to do close termux and open again.

```
git clone https://github.com/adi1090x/termux-style
```

```
cd termux-style
```

```
./install
```

• **Second,**

```
termux-style
```

**And We're done!**