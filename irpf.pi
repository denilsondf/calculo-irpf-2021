def calcular_irpf(renda):
    imposto = 0.0

    if renda > 55976.16:
        imposto += (renda - 55976.16) * 0.275
        renda = 55976.16
    if renda > 45012.60:
        imposto += (renda - 45012.60) * 0.225
        renda = 45012.60
    if renda > 33919.80:
        imposto += (renda - 33919.80) * 0.15
        renda = 33919.80
    if renda > 22847.76:
        imposto += (renda - 22847.76) * 0.075

    return imposto

# Exemplo de uso
renda_anual = float(input("Digite sua renda anual: "))
imposto = calcular_irpf(renda_anual)

print(f"Renda anual: R$ {renda_anual:.2f}")
print(f"Imposto de renda a pagar: R$ {imposto:.2f}")
