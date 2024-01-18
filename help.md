# Criar uma tabela de contingência (crosstab) entre Género e Intenção de Uso
tabela_contingencia = pd.crosstab(usabilidade_df['Género'], usabilidade_df['Intenção de Uso'],margins=True)
print(tabela_contingencia)
#margins=True inclui os totais por linha e por coluna


# Criar o diagrama de dispersão
plt.scatter(usabilidade_df['Idade'], usabilidade_df['Tempo de Utilização (min)'], c='blue', alpha=0.5)
plt.title('Diagrama de dispersão entre Idade e Tempo de Utilização')
plt.xlabel('Idade')
plt.ylabel('Tempo de Utilização (min)')
plt.show()