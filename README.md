import matplotlib.pyplot as plt

prevalencia = [3, 5]  # Valores de prevalencia del TDAH en porcentaje
categorias = ['Prevalencia del TDAH']

plt.bar(categorias, prevalencia)
plt.ylim(0, 5)  # Rango del eje y, del 0% al 5%
plt.ylabel('Porcentaje')
plt.title('Prevalencia del TDAH en niños en edad escolar')

plt.show()
