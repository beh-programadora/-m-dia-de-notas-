# Calculador de Média de Notas

Este projeto é um script em Python que solicita ao usuário três notas, calcula a média dessas notas e exibe o resultado formatado.

## Objetivo

O objetivo deste projeto é criar um script que:
1. Solicite ao usuário a entrada de três notas.
2. Calcule a média das notas fornecidas.
3. Exiba a média formatada com duas casas decimais.

## Código

O código funciona da seguinte maneira:
1. Solicita ao usuário três notas e as armazena em uma lista.
2. Calcula a média das notas.
3. Exibe a média formatada com duas casas decimais.

```python
# Leitura das notas 
notas = []
for i in range(3):
    nota = float(input(f"Digite a nota {i+1}: "))
    notas.append(nota)

# Cálculo da média 
media = sum(notas) / len(notas)

# Exibição da média 
print(f"A média das notas é {media:.2f}")
Como Executar
1. Certifique-se de ter o Python instalado em seu sistema.

2. Salve o código acima em um arquivo chamado calcular_media.py.

3. Execute o código usando o seguinte comando:
python calcular_media.py
4. Insira três notas quando solicitado e veja a média calculada.

Aqui estão os arquivos README, .gitignore e o enunciado para o projeto que calcula a média de notas fornecidas pelo usuário:

README.md
markdown
Copiar código
# Calculador de Média de Notas

Este projeto é um script em Python que solicita ao usuário três notas, calcula a média dessas notas e exibe o resultado formatado.

## Objetivo

O objetivo deste projeto é criar um script que:
1. Solicite ao usuário a entrada de três notas.
2. Calcule a média das notas fornecidas.
3. Exiba a média formatada com duas casas decimais.

## Código

O código funciona da seguinte maneira:
1. Solicita ao usuário três notas e as armazena em uma lista.
2. Calcula a média das notas.
3. Exibe a média formatada com duas casas decimais.

```python
# Leitura das notas 
notas = []
for i in range(3):
    nota = float(input(f"Digite a nota {i+1}: "))
    notas.append(nota)

# Cálculo da média 
media = sum(notas) / len(notas)

# Exibição da média 
print(f"A média das notas é {media:.2f}")
Como Executar
Certifique-se de ter o Python instalado em seu sistema.

Salve o código acima em um arquivo chamado calcular_media.py.

Execute o código usando o seguinte comando:

bash
Copiar código
python calcular_media.py
Insira três notas quando solicitado e veja a média calculada.

Contribuição
Sinta-se à vontade para fazer sugestões ou melhorias. Se encontrar um problema ou tiver uma ideia para aprimorar o projeto, por favor, abra uma issue ou envie um pull request.

Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.
