def calcular_descuento(monto_total, porcentaje_descuento=10):
    """
    Calcula el monto del descuento y devuelve el monto descontado.
    
    :param monto_total: Total de la compra en moneda local.
    :param porcentaje_descuento: Porcentaje de descuento a aplicar (por defecto 10%).
    :return: Monto del descuento.
    """
    descuento = (monto_total * porcentaje_descuento) / 100
    return descuento


# Llamadas a la función
monto1 = 200  
descuento1 = calcular_descuento(monto1)
monto_final1 = monto1 - descuento1
print(f"Monto total: ${monto1} - Descuento aplicado: ${descuento1} - Monto final a pagar: ${monto_final1}")

monto2 = 500  
porcentaje2 = 15  
descuento2 = calcular_descuento(monto2, porcentaje2)
monto_final2 = monto2 - descuento2
print(f"Monto total: ${monto2} - Descuento aplicado: ${descuento2} - Monto final a pagar: ${monto_final2}")
