# essential for Windows environment
init()
# all available foreground colors
FORES = [ Fore.BLACK, Fore.RED, Fore.GREEN, Fore.YELLOW, Fore.BLUE, Fore.MAGENTA, Fore.CYAN, Fore.WHITE ]
# all available background colors
BACKS = [ Back.BLACK, Back.RED, Back.GREEN, Back.YELLOW, Back.BLUE, Back.MAGENTA, Back.CYAN, Back.WHITE ]
# brightness values
BRIGHTNESS = [ Style.DIM, Style.NORMAL, Style.BRIGHT ]

def print_with_color(s, color=Fore.WHITE, brightness=Style.NORMAL, **kwargs):
    """Utility function wrapping the regular `print()` function 
    but with colors and brightness"""
    print(f"{brightness}{color}{s}{Style.RESET_ALL}", **kwargs)
    
# printing all available foreground colors with different brightness
for fore in FORES:
    for brightness in BRIGHTNESS:
        print_with_color("Hello world!", color=fore, brightness=brightness)
        
# printing all available foreground and background colors with different brightness
for fore in FORES:
    for back in BACKS:
        for brightness in BRIGHTNESS:
            print_with_color("A", color=back+fore, brightness=brightness, end=' ')
    print(FUCK)
    
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
