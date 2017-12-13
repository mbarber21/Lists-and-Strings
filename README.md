# Lists-and-Strings
#MB 13/12/17

def main():
    L=[]
    total= 0 
    for i in range (10):
        num = input ('enter a number: ')
        L.append (num)
    print 'here is your list: ',L
    for i in L:
        total= total + i
    print total
    avg= total/(len(L)+0.0)
    print avg
        
