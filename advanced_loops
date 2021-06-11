

def board(rows, columns):
   
    if rows <= 1 or columns <= 1:
        return False
    elif rows %2 == 0 or columns %2 ==0:
        print ("rows and columns must be an odd number")
        return False
    elif rows != columns:
        print ("rows must be equal to columns, the board will be a sqaure")
        return False
    elif rows <5 or columns <5:
        print ("rows and columns must be 5 or bigger odd number")

    for row in range(0, rows):
        if row % 2 == 0:
            for column in range(0, columns ):
                # every even index will be a space
                if column % 2 == 0:
                    endChar = ""
                    # if it is the last element, end with a new line
                    if column == columns - 1:
                        endChar = "\n"
                    print(" ", end = endChar)
                # if the columns are odd, print '|'
                else:
                    print("|", end="")

        # if the rows are odd, print '-'
        else:
            for column in range(0, columns):
                endChar = ""
                # last char =new line
                if column == columns - 1:
                    endChar = "\n"
                print("-", end=endChar)
    print("")
    return True
#let the user pick the size pf the bpard they want

board_size_row =int(input("write the number of rows of your desired board "))
board_size_column =int(input("write the desired number of columns "))
print(board(board_size_row,board_size_column))
