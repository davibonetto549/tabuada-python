# Tabuada em Python

Programa de linha de comando que lê um número inteiro e exibe sua tabuada de multiplicação de **1 a 10**. Este projeto utiliza o código-fonte disponibilizado pela **Neps Academy** para a atividade *README para seu Projeto*.

## Tecnologias e requisitos

- **Linguagem:** Python 3
- **Dependências externas:** nenhuma
- **Sistema:** qualquer ambiente com Python 3 instalado e acesso a um terminal

## Como executar

1. Baixe ou clone este repositório.
2. Abra um terminal na pasta que contém o arquivo `main.py`.
3. Execute:

   ```bash
   python main.py
   ```

   Em alguns sistemas, o comando correspondente é `python3 main.py` (ou `py main.py` no Windows).

4. **Digite um número inteiro de 0 a 1000 e pressione Enter.**

O programa aguarda a entrada **sem exibir uma mensagem antes**. Após receber o número, imprime dez linhas e termina. Para calcular outra tabuada, execute-o novamente.

## Exemplo de uso

Ao executar o programa e informar `2`, a saída produzida é:

```text
2 * 1 = 2
2 * 2 = 4
2 * 3 = 6
2 * 4 = 8
2 * 5 = 10
2 * 6 = 12
2 * 7 = 14
2 * 8 = 16
2 * 9 = 18
2 * 10 = 20
```

> **Observação:** o número `2` digitado pelo usuário não faz parte da saída impressa. O código original não valida automaticamente se a entrada está entre 0 e 1000; use um inteiro dentro dessa faixa, conforme a proposta da atividade. Entradas que não sejam números inteiros geram um erro de conversão.

## Estrutura dos arquivos

```text
.
├── README.md          # Apresentação e instruções de uso
├── main.py            # Código-fonte da tabuada
├── instructions.txt   # Instruções originais fornecidas pela Neps Academy
└── LICENSE            # Licença MIT original
```

## Licença e créditos

O código de `main.py`, o arquivo `instructions.txt` e a licença foram fornecidos pela **Neps Academy** e mantidos sem alterações. O programa é distribuído sob a **licença MIT**; consulte [`LICENSE`](LICENSE) para o texto e a atribuição originais.
