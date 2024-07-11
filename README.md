def hexagon(row,col):

    top = " ___"

    middle = " /  \\"

    bottam = " \\___/"

    grid=""

    for r in range(row):

        grid+= ("___"*col)+"\n"

        grid += ("/  \\" * col) + "\n"

        grid += ("\\__/" * col) + "\n"

    print(grid)



print("grid 1: ")

print(hexagon(4,7))

print("\ngrid 2: ")

print(hexagon(3,5))

