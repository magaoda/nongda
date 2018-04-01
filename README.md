# nongda
'''
def star(rows=5):   #形参 参数默认值
    row = 0
    while row < rows:
        row += 1
        space = 0
        while space < rows - row:
            space += 1
            print(" ", end="")
        star = 0
        while star < 2 * row - 1:
            print("*", end="")
            star += 1
        print("")
star()
star(3)
star(6)
star(10)
'''
