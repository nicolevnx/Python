from dataclasses import dataclass
from datetime import datetime
class Cliente:
    nome:str
    email:str
    telefone:str
 
listaA = [] 
listaB = []

def cadastrar_cliente():
    nome = input ("Qual o seu nome:")
    email = input ("Qual o seu email:")
    telefone= input ("Qual o seu telefone:")
    cliente_cadastrado = Cliente(nome,email,telefone)
    listaA.append(cliente_cadastrado)
    print("Cliente cadastrado com sucesso")
    
class Barbeiro:
    nome1:str
    nome2:str
    nome3:str
    
def cadastrar_barbeiro ():
    nome1 = input ("Nome do barbeiro")
    barbeiro_cadastrado = Barbeiro(nome)
    listaB.append(barbeiro_cadastrado)
    print("Barbeiro cadastrado com sucesso!\n")
 
def listar_clientes():
    if not listaA: 
        print("Nenhum cliente cadastrado.")
    else:
        print("\n--- Lista de Clientes ---")
        for cliente in listaA:
            print(cliente) 
              
def listar_barbeiros():   
    if not listaB:
        print("Nenhum barbeiro cadastrado ainda.")
    else:
        print("\n--- Lista de Barbeiros ---")
        for barbeiro in listaB:
            print(barbeiro)
            
def menu():
    while True:
        print("\n--- Sistema de Cadastro ---")
        print("1 - Cadastrar Cliente")
        print("2 - Cadastrar Barbeiro")
        print("3 - Listar Clientes")
        print("4 - Listar Barbeiros") 
        print("0 - Sair")
         
        opcao = input("Escolha uma opcao:")
         
        if opcao == "1":
             cadastrar_cliente()
        elif opcao == "2":
            cadastrar_barbeiro()
        elif opcao == "3":
            listar_clientes()
        elif opcao == "4":
            listar_barbeiros()
        elif opcao == "0":
            print("Saindo do sistema...")
            break
        else:
            print("Opcao iválida, tente novamente!")
            
         
menu() 
