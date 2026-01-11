import sys

# 颜色代码
BONE_WHITE = "\033[97m" # 亮白色，像骨头
BLOOD_RED = "\033[31m"  # 鲜血红
DARK_GRAY = "\033[90m"  # 暗灰色，用于阴影
RESET = "\033[0m"

def print_bone_banner():
    # 使用方案一：Vertebrae
    banner = f"""{BONE_WHITE}
d8888b. d888888b .d88b.   d888b  d88888b 
88  `8D   `88'   88  `8D 88' Y8b 88'     
88   88    88    88oobY' 88      88ooooo 
88   88    88    88`8b   88  ooo 88~~~~~ 
88  .8D   .88.   88 `88. 88. ~8~ 88.     
Y8888D' Y888888P 88   YD  Y888P  Y88888P {RESET}
    """
    
    # 标语用深红色，形成鲜明对比
    slogan = f"{BLOOD_RED}:: Singing the final song for the vulnerable. ::{RESET}"
    
    print(banner)
    print(slogan.center(60)) # 居中对齐
    print("\n")

if __name__ == "__main__":
    print_bone_banner()
An AI-powered automated binary exploitation agent based on Antigravity
Running in stealth mode. Initial release coming soon.
