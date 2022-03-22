# calculoMedias
# Calculo das medias escolares

# Média das notas escolares

print('\t ----Cálculo da média aritmética---- ')

nota1 = int(input('Informe a primeira nota: '))
nota2 = int(input('Informe a segunda nota: '))
nota3 = int(input('Informe a terceira nota: '))

media = (nota1+ nota2+ nota3)/3

print('Média Aritmética' '=', media)

if(media <6):
    print('reprovado :(')
elif(media >6):
    print('aprovado :)')
if(media >9):
    print('parabens voce é um excelente aluno!!')
elif(media <4):
    print('voce precisa estudar mais!!')
    
# Renato Barbosa
