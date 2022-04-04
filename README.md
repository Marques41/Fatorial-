# Fatorial-
Calcule o Fatorial de um numero qualquer
n = int(input('Digite um humero para calcular o Fatorial: '))
c = n
f = 1
print('Calcule {}! = '.format(n), end='')
while c > 0:
    print('{}'.format(c), end='')
    print(' x ' if c > 1 else '=', end=' ')
    f *= c
    c -= 1
print('{}'.format(f))
