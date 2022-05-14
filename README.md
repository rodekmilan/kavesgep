# kavesgep

# válltozók
válassz = input("válassz egy kávét a négy közül: latte; bécsi; hosszú; rövid:  ")
pénztár = 0 
kávék = ["latte" , "bécsi" , "hosszú" , "rövid"]
pénz = int(input("dobja be a pénzt! "))


# látte kávé

if válassz == "latte":
    if pénz == 160:
        print("latte kávé")
    elif pénz < 160:
        print("kevés a pénz")
    elif pénz > 160:
        print("latte kávé visszajáró; " , pénz - 160)

# bécssi kávé

if válassz == "bécsi":
    if pénz == 180:
        print("bécsi kávé")
    elif pénz < 180:
        print("kevés a pénz")
    elif pénz > 180:
        print("bécsi kávé visszajáró; " , pénz - 180)

# hosszú kávé

if válassz == "hosszú":
    if pénz == 200:
        print("hosszú kávé")
    elif pénz < 200:
        print("kevés a pénz")
    elif pénz > 200:
        print("hosszú kávé visszajáró; " , pénz - 200)

# rövid kávé

if válassz == "rövid":
    if pénz == 130:
        print("rövid kávé")
    elif pénz < 130:
        print("kevés a pénz")
    elif pénz > 130:
        print("rövid kávé visszajáró; " , pénz - 130)
