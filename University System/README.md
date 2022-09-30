# SistemaUniversidade

## Pessoa
- Atributos: String cpf; String nome; int idade;

## Estudante (Herança de Pessoa)
- Atributos: int matricula;

## Professor (Herança de Pessoa)
- Atributos: Double salario;

## Universidade
- Atributos: String nome; String endereco; ArrayList<Curso> listaCursos;

## Curso
- Atributos: String nome; ArrayList<Disciplina> listaDisciplina;

## Disciplina
- Atributos: String nome; ArrayList<Estudante> listaEstudantes; Professor professor; 
  
Construa um menu inicial para a criação de uma Universidade. Deverá criar obrigatoriamente todos os dados da universidade por Scanner.
  
No menu, deverá ter as seguintes opções:
- Cadastrar Universidade
- Cadastrar Estudante
- Cadastrar Professor
- Cadastrar Curso
- Cadastrar Disciplina
- Mostrar todos os dados da Universidade
- Sair
  
Uma Universidade deve ter uma lista de cursos, que consequentemente, tem uma lista de disciplinas, que por sua vez, tem uma lista de estudantes e um professor.
Todos estes dados devem ser mostrados na opção "Mostrar todos os dados da Universidade” do menu.
