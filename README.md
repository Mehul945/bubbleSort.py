# bubbleSort.py




def ch_sort(li):

    for i in range(len(li)-1):
    
        if i == len(li)-1:
        
            pass
            
        elif li[i] <= li[i+1]:
        
            x = 0
            
        else:
        
            x = 1
            
            break
            
    return x


def sort(list):

    for i in range(len(list)-1):
    
        if list[i] > list[i+1]:
        
            temp = list[i]
            
            list[i] = list[i+1]
            
            list[i+1] = temp
            
    xa = ch_sort(list)
    
    if xa == 1:
    
        sort(list)
        
    return list
    


def sot(arr, v):

    arr.append(v)
    
    for i in range(0, len(arr)):
    
        if arr[len(arr)-1] <= arr[i]:
        
            break
            
    return i


if __name__ == "__main__":

    a = [2, 4, 5, 7, 9]
    
    x = sot(a, 10)
    
    print(x)
