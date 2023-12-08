# 1st-github-project

#VOWELS AND CONSONANTS

ch=input("ch: ")
vowels=['a','e','i','o','u','A','E','I','O','U']
if ch.isalpha():
    if (ch in vowels):
        print("vowels")
    else:
        print("consonants")
else:
    print("not an alphabet")
