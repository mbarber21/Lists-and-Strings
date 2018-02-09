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
    print L2 
    for i in L2:
        if i%2 == 1:
            print i
        list.sort(L2)
    print L2
    list.reverse(L2) #highest number first- check if even, 'h' as substitution until know how to take first int from list
    print L2

    if h%2 == 0:
        print h

        
#how do i keep checking if even from starting integer in list until first even int, print, then stop
#why check if numbers even if list only prints odd numbers? then how would there be a highest number thats even?
            


list2()
    

    
