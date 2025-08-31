# Sistema de Cálculo de Impostos em C#

## Introdução
Este projeto demonstra a aplicação prática dos conceitos de **Programação Orientada a Objetos (POO)** em C#, por meio de um sistema que calcula impostos de clientes do tipo **Pessoa Física** e **Pessoa Jurídica**.

---

## Conceitos Aplicados
- **Abstração**: classe genérica `Clientes`.  
- **Herança**: especialização em `Pessoa_Fisica` e `Pessoa_Juridica`.  
- **Polimorfismo**: sobrescrita do método `Pagar_Imposto`.  
- **Encapsulamento**: uso de modificadores de acesso adequados.  

---

## Funcionamento
1. O usuário informa o tipo de cliente no console.  
2. São solicitados os dados básicos e específicos (CPF/RG ou CNPJ/IE).  
3. O sistema calcula o imposto:  
   - **Pessoa Física** → 10%  
   - **Pessoa Jurídica** → 20%  
4. O resultado é exibido em tela (valor, imposto e total).  

---
