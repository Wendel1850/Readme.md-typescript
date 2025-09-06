# Readme.md-typescript

// Definindo uma interface para um usuário
interface Usuario {
  nome: string;
  idade: number;
}

// Criando uma classe que implementa a interface Usuario
class Pessoa implements Usuario {
  nome: string;
  idade: number;

  constructor(nome: string, idade: number) {
    this.nome = nome;
    this.idade = idade;
  }

  // Método para imprimir informações do usuário
  imprimirInfo(): void {
    console.log(`Nome: ${this.nome}, Idade: ${this.idade}`);
  }
}

// Criando uma instância da classe Pessoa
const
