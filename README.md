# Categorizando-triangulos
Treino 1
print(" Me diga qual os valores dos lados de um triângulo e eu direi se ele não existe ou se existe. Caso ele exista, eu direi qual é a sua classificação a partir dos lados")
print("")
l1 = float(input("  Qual o valor do primeiro lado? "))
l2 = float(input("  Qual o valor do segundo lado? "))
l3 = float(input("  Qual o valor do terceiro lado? "))
print("")
if l1>=l2+l3 or l2>=l1+l3 or l3>=l2+l1:
    print("Este trriângulo NÃO EXISTE")
elif l1==l2!=l3 or l2==l3!=l1 or l3==l1!=l2:
    print("esse triângulo é ISÓCELES")
elif l1==l2==l3:
    print("este triângulo é EQUILÁTERO")
elif l1<l2+l3 or l2<l3+l1 or l3<l2+l1:
    print("Este triângulo é ESCALENO")****
