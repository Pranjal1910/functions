def countWordsFromFile():
    filename = input("Enter The file Name :-")


    numberOfWords = 0 

    file = open(filename, 'r')
    for line in file:
        words = line.split()
        numberOfWords = numberOfWords + len(words)

    print("Number Of Words:")        
    print(numberOfWords)


countWordsFromFile() 
