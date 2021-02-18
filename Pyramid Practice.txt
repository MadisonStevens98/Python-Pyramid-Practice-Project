def print_pyramid(type): ##required method
    if type == "left": #selection statement for left
        print("# \n## \n### \n#### \n##### \n###### \n#######") #left pyramid
    elif type == "right": #selection for right
        print(" #\n ##\n ###\n ####\n #####\n ######\n #######")#right pyramid
    elif type == "both":#selection for both
        print(" ## \n ####\n ######\n ########\n ##########\n ############\n##############")#both pyramid
    else:#improper input
        print("Invalid input, please type right, left, or both")
        #tells user they messed up

def main():#main loop through program
    while True:
        prompt()
              
def prompt():#prompts user for type
    type = input("Please type right, left, or both")#assigns type
    print_pyramid(type)#calls and runs print_pyramid

if __name__ == '__main__':
    main()
