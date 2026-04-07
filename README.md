def fatorial(n):
    if n == 0 or n == 1:   # Caso base
        return 1
    else:                  # Passo recursivo
        return n * fatorial(n - 1)

# Exemplo de uso
print(fatorial(5))  # Saída: 120
