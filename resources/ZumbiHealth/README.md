# Explicação da tabela

**Informação extra**: É um par com 0 e 1 indicando se um zumbi comeu terra ou foi mordido por outro zumbi. 
Ex: (0,1) = Não comeu terra e Foi mordido

**Doenças**: Tripla indicando a doença do zumbi, que pode ser lombriga, virus ou bacteria respectivamente
Ex: (1, 0, 0) = Tem lombriga

**Exames**: Indica nível sanguineo e capacidade pulmonar do zumbi
Ex: (190, 54) => nível sanguineo = 190 e capacidade pulmonar = 54
nível sanguineo: normal por volta de 150
capacidade pulmonar: normal por volta de 50

**Sintomas**: Indica valor valor da respiração, valor do batimento cardiaco, pele amarela e raiva (1 indica presença do sintoma)
Ex: (141, 214, 0, 0) => respiração = 141, batimento cardiaco = 214, não tem pele amarela e não tem raiva

**Tratamento**
Indica o tratamento correto para a doença do zumbi
Zumbidazol=> cura lombriga
Zanamivir=> cura virus
Amoxozumbicilina => cura bacteria
