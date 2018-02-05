# Lists-and-Strings
#MB 13/12/17

##def main():
##    L=[]
##    total= 0 
##    for i in range (10):
##        num = input ('enter a number: ')
##        L.append (num)
##    print 'here is your list: ',L
##    for i in L:
##        total= total + i
##    print total
##    avg= total/(len(L)+0.0)
##    print avg
##main()
     
     _______________________________________________________ ____________________________________________________________
     
     
# Lists-and-Strings
#MB 13/12/17

from random import*
        
def list2():
    L2=[]
    for i in range (20):
        num = randint (1,100)
        L2.append (num)
    print L2 #sort list then reverse so highest number first and check if even
    for i in L2:
        if i%2 == 1:
            print i 
    
list2()

    
