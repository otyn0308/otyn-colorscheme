# otynium
colorscheme

![otynium](https://github.com/otyn0308/otynium/blob/master/picture/Screenshot%20from%202018-12-08%2012-24-38.png)
![otynium_colorling](https://github.com/otyn0308/otynium/blob/master/picture/otynium_colorling.png)

## install

```
$ git clone https://github.com/otyn0308/otynium.git
:!echo $VIMRUNTIME
$ cd ~/otynium/colors
$ sudo cp otynium.vim /usr/share/vim/vim81/colors
```
  
コピー先は ```:!echo $VIMRUNTIME```で出てきた場所の```/colors```ってところ．
  
これをやったら.vimrcに
```colors otynium```
と書き足す．  

ここでいう /usr/share/vim/vim81 は `:!echo $VIMRUNTIME` で出てきたやつ  
自分用メモなので雑です．
