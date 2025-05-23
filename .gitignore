print("-"*42)
print("Bem-vindo(a) ao menu do estudante")
print("-"*42)
alunos = []
professores = []
disciplinas = []
turmas = []
matriculas = []

#Loop - 00
while True:
        print("[1] Estudante")
        print("[2] Professores")
        print("[3] Disciplínas")
        print("[4] Turmas")
        print("[5] Matrículas")
        print("[0] Sair")
        print("-"*42)

        #opção

        opcao=int(input("Escolha uma opção válida  "))
        print("-"*42)

        #Programação menu 01
        if opcao == 1 or opcao == 2 or opcao == 3 or opcao == 4 or opcao == 5:
            print("Opção válida")
            print("~"*42)

            # Escolha
            escolha = opcao - 0
            if escolha == 1:
                print("Estudante")
                #Estudante

                # Menu02
                print("-" * 42)
                print("Menu [Estudante]")
                print("-" * 42)
                print("[1] Listar")
                print("[2] Atualizar")
                print("[3] Criar")
                print("[4] Excluir")
                print("[0] Voltar")
                print("-" * 42)
                # opção 002
                opcao_secundaria = int(input("Escolha uma opção válida  "))
                print("-" * 42)
                # Programação menu 002
                if opcao_secundaria == 1 or opcao_secundaria == 2 or opcao_secundaria == 3 or opcao_secundaria == 4 or opcao_secundaria == 0 or opcao_secundaria == 5:
                    print("Opção válida")
                    print("~" * 42)
                    # Escolha
                    escolha = opcao_secundaria - 0
                if escolha == 1:
                    print("Listar")
                    print(alunos)
                    print('-'*42)
                    if len(alunos) == 0:
                        print("Não temos alunos cadastrados")
                        print('-'*42)
                elif escolha == 2:
                    print("Atualizar")
                    print(alunos)
                    print(len(alunos))
                    atualizar = input("Atualizar nome do úsuario  ")
                    if atualizar in alunos:
                        alunos.remove(atualizar)
                        print(alunos)
                        print("Renomear")
                        alunos_novos=input("Novo nome  ")
                        alunos.append(alunos_novos)
                        print(alunos)
                        print('-'*42)
                    elif alunos:
                        print("Não é um Aluno!")
                elif escolha == 3:
                    for i in range(1):
                        alunos_novos = input("Digite o nome do Aluno  ")

                        alunos.append(alunos_novos)
                        print("Você adicionou", alunos_novos)
                        print('-'*42)
                elif escolha == 4:
                    print("Remover úsuario")
                    print(alunos)
                    remover_aluno = input("Nome do usuario  ")
                    if remover_aluno in alunos:
                        alunos.remove(remover_aluno)
                        print("Aluno deletado")
                        print(alunos)
                        print('-'*42)
                    else:
                        print("Esse aluno não está no sistema")
                        print('-'*42)
                elif opcao_secundaria == 0:
                    print("Você está voltando ao menu principal")
                    print('-'*42)
                elif escolha >= 5:
                    print("Essa não é uma opção válida")
                    print("Voltando ao menu principal")
                    print('-*42')

            elif escolha == 2:
                print("Professores")

                #Professores

                # Menu02
                print("-" * 42)
                print("Menu [Professor]")
                print("-" * 42)
                print("[1] Listar")
                print("[2] Atualizar")
                print("[3] Criar")
                print("[4] Excluir")
                print("[0] Voltar")
                print("-" * 42)
                # opção 002
                opcao_terciaria = int(input("Escolha uma opção válida  "))
                print("-" * 42)
                # Programação menu 027
                if opcao_terciaria == 1 or opcao_terciaria == 2 or opcao_terciaria == 3 or opcao_terciaria == 4 or opcao_terciaria == 0 or opcao_terciaria == 5:
                    print("Opção válida")
                    print("~" * 42)
                    # Escolha
                    escolha_secundaria = opcao_terciaria - 0
                if escolha_secundaria == 1:
                    print("Listar")
                    print(professores)
                    print('-' * 42)
                    if len(professores) == 0:
                        print("Não temos professores cadastrados")
                        print('-' * 42)
                elif escolha_secundaria == 2:
                    print("Atualizar")
                    print(professores)
                    print(len(professores))
                    atualizar = input("Atualizar nome do úsuario  ")
                    if atualizar in professores:
                        professores.remove(atualizar)
                        print(professores)
                        print("Renomear")
                        professores_novos = input("Novo nome  ")
                        professores.append(professores_novos)
                        print(professores)
                        print('-' * 42)
                    elif professores:
                        print("Não é um professor!")
                elif escolha_secundaria == 3:
                    professores_novos = []
                    for i in range(1):
                        professores_novos = input("Nome do professor(a) ")
                        professores.append(professores_novos)
                        print("Você adicionou", professores_novos)
                        print("A lista é",professores)
                        print('-' * 42)
                elif escolha_secundaria == 4:
                    print("Remover úsuario")
                    print(professores)
                    remover_professor = input("Nome do usuario  ")
                    if remover_professor in professores:
                        professores.remove(remover_professor)
                        print("Professor deletado")
                        print(professores)
                        print('-' * 42)
                    else:
                        print("Esse professor não está no sistema")
                        print('-' * 42)
                elif escolha_secundaria == 0:
                    print("Você está voltando ao menu principal")
                elif escolha_penta >= 5:
                    print("Essa não é uma opção válida")
                    print("Voltando ao menu principal")
                    print('-*42')

            elif escolha == 3:
                print("Disciplínas")
            #Disciplínas

            #Menu02
                print("-" * 42)
                print("Menu [Disciplinas]")
                print("-" * 42)
                print("[1] Listar")
                print("[2] Atualizar")
                print("[3] Criar")
                print("[4] Excluir")
                print("[0] Voltar")
                print("-" * 42)
                # opção 002
                opcao_quartenaria = int(input("Escolha uma opção válida  "))
                print("-" * 42)
                # Programação menu 027
                if opcao_quartenaria == 1 or opcao_quartenaria == 2 or opcao_quartenaria == 3 or opcao_quartenaria == 4 or opcao_quartenaria == 0 or opcao_quartenaria == 5:
                    print("Opção válida")
                    print("~" * 42)
                    # Escolha
                    escolha_terciaria = opcao_quartenaria - 0
                if escolha_terciaria == 1:
                    print("Listar")
                    print(disciplinas)
                    print('-' * 42)
                    if len(disciplinas) == 0:
                        print("Não temos disciplinas cadastradas")
                        print('-' * 42)
                elif escolha_terciaria == 2:
                    print("Atualizar")
                    print(disciplinas)
                    print(len(disciplinas))
                    atualizar = input("Atualizar nome da disciplinas  ")
                    if atualizar in disciplinas:
                        disciplinas.remove(atualizar)
                        print(disciplinas)
                        print("Renomear")
                        disciplinas_novos = input("Novo nome  ")
                        disciplinas.append(disciplinas_novos)
                        print(disciplinas)
                        print('-' * 42)
                    elif disciplinas:
                        print("Não é uma disciplina!")
                elif escolha_terciaria == 3:
                    disciplinas_novos = []
                    for i in range(1):
                        disciplinas_novos = input("Nome da discplina ")
                        disciplinas.append(disciplinas_novos)
                        print("Você adicionou", disciplinas_novos)
                        print("A lista é",disciplinas)
                        print('-' * 42)
                elif escolha_terciaria == 4:
                    print("Remover disciplinas")
                    print(disciplinas)
                    remover_disciplina = input("Nome do usuario  ")
                    if remover_disciplina in disciplinas:
                        disciplinas.remove(remover_disciplina)
                        print("Disciplina deletada")
                        print(disciplinas)
                        print('-' * 42)
                    else:
                        print("Esse professor não está no sistema")
                        print('-' * 42)
                elif escolha_terciaria == 0:
                    print("Você está voltando ao menu principal")
                elif escolha_terciaria >= 5:
                    print("Essa não é uma opção válida")
                    print("Voltando ao menu principal")
                    print('-*42')

            elif escolha == 4:
                print("Turmas")
            #Turmas

            # Menu02
                print("-" * 42)
                print("Menu [Turmas]")
                print("-" * 42)
                print("[1] Listar")
                print("[2] Atualizar")
                print("[3] Criar")
                print("[4] Excluir")
                print("[0] Voltar")
                print("-" * 42)
                # opção 002
                opcao_penta = int(input("Escolha uma opção válida  "))
                print("-" * 42)
                # Programação menu 027
                if opcao_penta == 1 or opcao_penta == 2 or opcao_penta == 3 or opcao_penta == 4 or opcao_penta == 0 or opcao_penta == 5:
                    print("Opção válida")
                    print("~" * 42)
                    # Escolha
                    escolha_quarta = opcao_penta - 0
                if escolha_quarta == 1:
                    print("Listar")
                    print(turmas)
                    print('-' * 42)
                    if len(turmas) == 0:
                        print("Não temos turmas cadastrados")
                        print('-' * 42)
                elif escolha_quarta == 2:
                    print("Atualizar")
                    print(turmas)
                    print(len(turmas))
                    atualizar = input("Atualizar nome da turma  ")
                    if atualizar in turmas:
                        turmas.remove(atualizar)
                        print(turmas)
                        print("Renomear")
                        turmas_novos = input("Novo nome  ")
                        turmas.append(turmas_novos)
                        print(turmas)
                        print('-' * 42)
                    elif turmas:
                        print("Não é um professor!")
                elif escolha_quarta == 3:
                    turmas_novos = []
                    for i in range(1):
                        turmas_novos = input("Nome do professor(a) ")
                        turmas.append(turmas_novos)
                        print("Você adicionou", turmas_novos)
                        print("A lista é",turmas)
                        print('-' * 42)
                elif escolha_quarta == 4:
                    print("Remover turma")
                    print(turmas)
                    remover_turmas = input("Nome da turma  ")
                    if remover_turmas in turmas:
                        turmas.remove(remover_turmas)
                        print("Turma deletada")
                        print(turmas)
                        print('-' * 42)
                    else:
                        print("Esta turma não está no sistema")
                        print('-' * 42)
                elif escolha_quarta == 0:
                    print("Você está voltando ao menu principal")
                elif escolha_quarta >= 5:
                    print("Essa não é uma opção válida")
                    print("Voltando ao menu principal")
                    print('-*42')

            elif escolha == 5:
                print("Matrículas")
            #Matrículas

                # Menu02
                print("-" * 42)
                print("Menu [Matrículas]")
                print("-" * 42)
                print("[1] Listar")
                print("[2] Atualizar")
                print("[3] Criar")
                print("[4] Excluir")
                print("[0] Voltar")
                print("-" * 42)
                # opção 002
                opcao_hexa = int(input("Escolha uma opção válida  "))
                print("-" * 42)
                # Programação menu 027
                if opcao_hexa == 1 or opcao_hexa == 2 or opcao_hexa == 3 or opcao_hexa == 4 or opcao_hexa == 0 or opcao_hexa ==5:
                    print("Opção válida")
                    print("~" * 42)
                    # Escolha
                    escolha_penta = opcao_hexa - 0
                if escolha_penta == 1:
                    print("Listar")
                    print(matriculas)
                    print('-' * 42)
                    if len(matriculas) == 0:
                        print("Não temos matrículas cadastrados")
                        print('-' * 42)
                elif escolha_penta == 2:
                    print("Atualizar")
                    print(matriculas)
                    print(len(matriculas))
                    atualizar = input("Atualizar matrículas  ")
                    if atualizar in matriculas:
                        matriculas.remove(atualizar)
                        print(matriculas)
                        print("Renomear")
                        matriculas_novos = input("Novo nome  ")
                        matriculas.append(matriculas_novos)
                        print(matriculas)
                        print('-' * 42)
                    elif matriculas:
                        print("Não tem matrícula!")
                elif escolha_penta == 3:
                    matriculas_novos = []
                    for i in range(1):
                        matriculas_novos = input("Sua matrícula ")
                        matriculas.append(matriculas_novos)
                        print("Você adicionou", matriculas_novos)
                        print("A lista é",matriculas)
                        print('-' * 42)
                elif escolha_penta == 4:
                    print("Remover matrícula")
                    print(matriculas)
                    remover_matricula = input("Número da matrícula ")
                    if remover_matricula in matriculas:
                        matriculas.remove(remover_matricula)
                        print("Matrícula deletada")
                        print(matriculas)
                        print('-' * 42)
                    else:
                        print("Esta matrícula não está no sistema")
                        print('-' * 42)
                elif escolha_penta == 0:
                    print("Você está voltando ao menu principal")
                    print('-'*42)
                elif escolha_penta >= 5:
                    print("Essa não é uma opção válida")
                    print("Voltando ao menu principal")
                    print('-*42')
        elif opcao == 0:
            print("Você está saindo")
            break
        elif opcao >= 5:
            print("Essa não é uma opção válida")
            print('-' * 42)






