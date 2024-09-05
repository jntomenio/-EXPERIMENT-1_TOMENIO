## **EXPERIMENT #1 - Introduction to Python Programming**
### Name: Tomenio, Julian Bernice Kristoffer
### Section: 2ECE-A

#### Date Submitted: August 27, 2024

## Alphabet Soup Problem
def alphabet_soup(x):
    sorted(x)
    string=''.join(sorted(x))
    print(string)

y = input("Enter the word you want to re-arrange in alphabetical order:")
alphabet_soup(y)

## Emoticon Problem
def emotify(feel):

    feel = feel.replace("Smile", ":)")
    feel = feel.replace("Grin", ":D")
    feel = feel.replace("Sad", ":((")
    feel = feel.replace("Mad", ">:(")
    return feel

feel = input("Enter what you feel right now:")
print (emotify(feel))

## Unpacking List Problem
Book = [1,2,3,4,5,6]

first = Book[0]
middle = Book[1:-1]
last = Book[-1]

print("First Variable: " + str(first), "     Midlle Variables: " + str(middle), "     Last Variable: " + str(last))
