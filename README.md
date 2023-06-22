public class Pessoa {
    private String nome;
    private String dataNascimento;
    
    public Pessoa(String nome, String dataNascimento) {
        this.nome = nome;
        this.dataNascimento = dataNascimento;
    }
    
    
    public String toString() {
        return "Nome: " + nome + "\nData de Nascimento: " + dataNascimento;
    }
}

public class Main {
    public static void main(String[] args) {
        Pessoa pessoa = new Pessoa("Nicole Araujo", "22/09/2000");
        System.out.println(pessoa.toString());
  }
}

Nome: Nicole Araujo
Data de Nascimento: 22/09/2000
}   
