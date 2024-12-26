---
title : VimCommand
pubDate: 2024-12-29 
categories : ['vim','tools']
description: 'Some commonly used Vim commands in daily usage '
slug: 
---

## Delete 
* di/da + '('/''{' : delete the content in the brackets(i:exclude the brackets,a: include the brackets))
*    : delete the brackets
* 

## Change
* gS + brackets : add brackets arround the selected contents (nvim-surround.nvim  is needed)
*  

## Substitute
ot : origin text ; tt : target text 
* :s/ot/tt/g : Substitute in current line, /g : Substitute all matched
* :%s/ot/tt/g : in whole file 
* 

## Select 
* V : current line
* \<C-v\> : select blocks
* ggVG : select whole file quickly


## Buffers vs Windows
* :q ; quit current buffer  
* :qa ; quit all buffer 
* :sp ; the same buffer below


