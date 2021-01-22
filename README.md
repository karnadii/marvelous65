# Marvelous65
A 65% wireless hotswap keyboard with Rotary encoder, OLED display and RGB underglow.

## V1
![img](https://i.imgur.com/Np1dnCb.jpg)
![](https://i.imgur.com/QaL3Zr7.jpg)
![](https://i.imgur.com/UT9RIDT.jpg)
![](https://i.imgur.com/qvQjEH1.jpg)
## V2
![](https://i.imgur.com/FA5Elsy.jpg)
![img](https://i.imgur.com/hqNk5MB.jpg)

## V1 vs V2
![](https://i.imgur.com/0wT6L0c.jpg)


This keyboard is inspired by luantty2's Candy BLE (https://github.com/luantty2/nRF52840-instruction). When I first saw that I was like "Beautiful! Marvelous!" but that would be nice to make that in 65%. So With no basic knowledge of electronic I brave myself to learn Kicad with the guide of https://wiki.ai03.com/books/pcb-design/page/pcb-guide-part-1---preparations. Basically this is just an nrfmicro 1.4 by Joric embedded in PCB.
I also learn some basic Fusion 360 to make a keyboard case and plate. Since my printer is ender 3 pro, I have to split everything in two. You might notice there is a litle gap in the keyboard, that is where I split my plate.

This is my first PCB and I make a lot of stupid design decision, I will share it the PCB case and plate design once I done with the revison. I plan to make it multi layout with split backspace, 6.5u spacebar and split space.
with this small board actually it makes sense with split spacebar cause I need more modifier (2 Fn). But if this is gonna be multi layout there will be no hotswap. maybe i will make it two version. The split spacebar is 2u, 1.25 and 2.75u. I choose 2u rather than 2.25 because I consider the keycap availability.

When I finish designing this, I realize I am not he first one to design this, there is someone in zfrontier forum already done it, it is called Rainbow65, check it out https://www.zfrontier.com/app/flow/e1rpMAd9Nz75.
and there is someone planning an IC for similar layout and feature. 

Anyway here is the photos of me making this board https://imgur.com/gallery/9tkokVy

## Update
### 28/12/2020
I have finished the v2 pcb. Just have to order a ptototype from JLCpcb. This is gonna be multilayout hostwap so the best plate for this pcb is plate generated from swillkb for plate mount stab. If you prefer pcb mount stab I will still release the pcb mount stab version but you have to desolder some of uneeded hotswap that interfre with the stab for your choosen layout. 

## Firmware
The firmware will use [ZMK](https://zmkfirmware.dev/) and QMK (if you don't care about license). you can choose between those two firmware. 

## Features
- Dual mode wireless and wired
- rotary encoder
- oled display
- rgb underglow
- hotswap
- multilayout

## PCB (v2)
![](https://i.imgur.com/TqCldaq.png)
![](https://i.imgur.com/ZD6vsq7.png)

## Layout (v2)
![](https://i.imgur.com/o3pjJZ5.png)
try it in [KLE](http://www.keyboard-layout-editor.com/##@_name=marvelous65%3B&@_x:3%3B&=~%0A%60&=!%0A1&=%2F@%0A2&=%23%0A3&=$%0A4&=%25%0A5&=%5E%0A6&=%2F&%0A7&=*%0A8&=(%0A9&=)%0A0&=%2F_%0A-&=+%0A%2F=&_a:6&w:2%3B&=Back&_x:0.25%3B&=enc1&_x:1&a:7%3B&=&=%3B&@_x:3&a:4&w:1.5%3B&=Tab&=Q&=W&=E&=R&=T&=Y&=U&=I&=O&=P&=%7B%0A%5B&=%7D%0A%5D&_w:1.5%3B&=%7C%0A%5C&_x:3&a:7&w:1.25&h:2&w2:1.5&h2:1&x2:-0.25%3B&=%3B&@_a:4&w:1.25&w2:1.75&l:true%3B&=Caps%20Lock&_x:1.75&w:1.75%3B&=Caps%20Lock&=A&=S&=D&=F&=G&=H&=J&=K&=L&=%2F:%0A%2F%3B&=%22%0A'&_a:6&w:2.25%3B&=Enter&_x:2&a:7%3B&=%3B&@_w:1.25%3B&=&=&_x:0.75&a:6&w:2.25%3B&=Shift&_a:4%3B&=Z&=X&=C&=V&=B&=N&=M&=%3C%0A,&=%3E%0A.&=%3F%0A%2F%2F&_a:6&w:1.75%3B&=Shift%3B&@_y:-0.75&x:17.25&a:7%3B&=%E2%86%91%3B&@_y:-0.25&x:3&a:6&w:1.25%3B&=Ctrl&_w:1.25%3B&=Win&_w:1.25%3B&=Alt&_a:7&w:6.25%3B&=&_a:6%3B&=Alt&=Fn&=Ctrl%3B&@_y:-0.75&x:16.25&a:7%3B&=%E2%86%90&=%E2%86%93&=%E2%86%92%3B&@_x:6.75&w:2.25%3B&=&_w:1.25%3B&=&_w:2.75%3B&=&_w:1.5%3B&=&_w:1.5%3B&=) 

## Case (v2)
![](https://i.imgur.com/s04cfbT.png)
![](https://i.imgur.com/OeKKgvj.png)
![](https://i.imgur.com/71my9OR.png)


