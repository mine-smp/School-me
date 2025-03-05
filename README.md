while True:

    r = int(input("math = "))
    
    if r > 20:
        print("\033[91mERROR\033[0m")  
        
        continue
    
    k = int(input("history = "))
    
    if k > 20:
        print("\033[91mERROR\033[0m")
        
        continue
    
    l = int(input("parsi = "))
    
    if l > 20:
        print("\033[91mERROR\033[0m")
        
        continue
    
    a = int(input("Arabic = "))
    
    if a > 20:
        print("\033[91mERROR\033[0m")
        
        continue

    m = int(input("english = "))
    
    if m > 20:
        print("\033[91mERROR\033[0m")
        
        continue
  
    x = (m + l + k + r + a) / 5
    
    print("-------------------------")
    print(f"GPA: {x}")
    
    break
