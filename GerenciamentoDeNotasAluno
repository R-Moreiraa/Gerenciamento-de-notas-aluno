def cadastrar_notas():
    notas = []
    print("Digite as notas do aluno (de 0 a 10)")
    print("Para encerrar, digite -1")
    
    while True:
        try:
            nota = float(input("Nota: "))
            
            if nota == -1:
                break
                
            if 0 <= nota <= 10:
                notas.append(nota)
                print(f"Nota {nota} adicionada com sucesso!")
            else:
                print("Nota inválida! Digite um valor entre 0 e 10.")
                
        except ValueError:
            print("Por favor, digite um número válido.")
    
    return notas

def calcular_media(notas):
    if len(notas) == 0:
        return 0
    
    soma = sum(notas)
    media = soma / len(notas)
    return media

def determinar_situacao(media):
    if media >= 7:
        return "Aprovado"
    else:
        return "Reprovado"

def sistema_notas():
    print("=== SISTEMA DE GESTÃO DE NOTAS ===\n")
    
    # Coletar as notas
    notas_aluno = cadastrar_notas()
    
    # Verificar se foram inseridas notas
    if len(notas_aluno) == 0:
        print("\nNenhuma nota foi inserida!")
        return
    
    # Calcular média
    media_calculada = calcular_media(notas_aluno)
    
    # Determinar situação
    situacao = determinar_situacao(media_calculada)
    
    # Mostrar resultados
    print("\n" + "="*40)
    print("RELATÓRIO FINAL")
    print("="*40)
    print(f"Notas registradas: {notas_aluno}")
    print(f"Total de notas: {len(notas_aluno)}")
    print(f"Média final: {media_calculada:.2f}")
    print(f"Situação: {situacao}")
    print("="*40)

# Executar o programa
if __name__ == "__main__":
    sistema_notas()
