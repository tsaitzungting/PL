import sys
from termcolor import colored, cprint
 
text = colored('Hello, World!', 'red', attrs=['reverse', 'blink'])
print(text)
cprint('Hello, World!', 'green', 'on_red')
 
 
def print_red_on_cyan(x): return cprint(x, 'red', 'on_cyan')
 
 
print_red_on_cyan('Hello, World!')
print_red_on_cyan('Hello, Universe!')
 
for i in range(10):
    cprint(i, 'magenta', end=' ')
 
cprint("Attention!", 'red', attrs=['bold'], file=sys.stderr)

# PL


<table>
    <tr>
        <td>test</td>
    </tr>
</table>

# <111-1 師大科技系程式語言> <red>

<ol>
<li>老師:陳芸琤</li>
<li>系級:科技系2年級</li>
<li>姓名:蔡宗廷</li>
</ol>
    
---------------------------- 

## 課程筆記區

## 作業連結區

## 專題連結區

# my channel:
https://www.youtube.com/watch?v=dQw4w9WgXcQ
