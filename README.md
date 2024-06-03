def calc(p):
    vowels=set('aeiouAEIOU')
    for chr in p:
        if chr in vowels:
            print("error")
            return
    print("positive")

x=str(input("enter the word"))
calc(x)
