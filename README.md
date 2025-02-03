


# :books: Atividades de Java - Linguagem de Programação

Bem-vindo ao repositório de atividades da disciplina **Linguagem de Programação**! Aqui você encontrará uma série de exercícios realizados em **Java**, organizados de forma didática para facilitar o acompanhamento e estudo.

---

## :rocket: Objetivo

Este repositório foi criado para organizar as atividades e projetos desenvolvidos ao longo da matéria de **Linguagem de Programação**. O foco principal é a prática de conceitos de programação utilizando a linguagem **Java**.

A ideia é armazenar as soluções para desafios propostos durante o curso, com explicações sobre cada tarefa e o código desenvolvido.

---

## :package: Estrutura do Repositório

A estrutura do repositório segue a organização das atividades feitas ao longo do curso. Veja um exemplo de como ela está organizada:

```
/
├── Atividade_1/
│   ├── README.md
│   ├── Atividade_1.java
│   └── Outros_arquivos/
│
├── Atividade_2/
│   ├── README.md
│   ├── Atividade_2.java
│   └── Outros_arquivos/
└── ...


Cada pasta contém o código-fonte em **Java**, explicações sobre a atividade, e outros arquivos relacionados.

---

## :computer: Como Utilizar

1. **Clone o repositório** para sua máquina local:

   ```bash
   git clone https://github.com/seu-usuario/atividade-java.git
   ```

2. **Acesse a pasta da atividade** que você deseja ver ou executar:

   ```bash
   cd Atividade_1
   ```

3. **Compile e execute o código** usando o terminal:

   ```bash
   javac NomeDoArquivo.java
   java NomeDoArquivo
   ```

---

## :memo: Exemplo de Atividade

### Atividade 1: "Cálculo da Soma de Dois Números"

Esta atividade consiste em escrever um programa que receba dois números inteiros e calcule a soma. O código abaixo exemplifica a solução proposta:

```java
import java.util.Scanner;

public class Soma {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Digite o primeiro número: ");
        int num1 = scanner.nextInt();
        System.out.print("Digite o segundo número: ");
        int num2 = scanner.nextInt();

        int soma = num1 + num2;
        System.out.println("A soma é: " + soma);
    }
}
```

---

## :bulb: Como Contribuir

Se você deseja contribuir com melhorias ou sugestões para este repositório, fique à vontade para:

- **Abrir uma issue** para discutir melhorias.
- **Enviar um pull request** com as suas contribuições.

Estamos sempre abertos a melhorias e a aprender com a comunidade!

---

## :page_facing_up: Licença

Este projeto é de uso educacional e pessoal, e está sob a [Licença MIT](https://opensource.org/licenses/MIT).

---

## :coffee: Tecnologias Usadas

- **Java** (JDK 8+)
- **Git** para controle de versão
- **GitHub** para hospedagem do repositório

---

## :sparkles: Contato

Se tiver dúvidas ou sugestões, entre em contato comigo:

- [Perfil no GitHub](https://github.com/seu-usuario)
- E-mail: seuemail@dominio.com

---

## :trophy: Agradecimentos

Agradeço ao professor e aos colegas de classe pelo apoio e pelos desafios que nos ajudaram a crescer como programadores! 🚀
```

Agora tudo está junto! O texto ficou mais estilizado com seções bem definidas e emojis para tornar a leitura mais agradável. O código de exemplo também foi mantido para ilustrar o funcionamento do repositório. Caso queira incluir imagens externas, você pode adicionar links com `![Descrição](URL)` no lugar dos emojis, caso deseje adicionar capturas de tela ou outros tipos de gráficos.
