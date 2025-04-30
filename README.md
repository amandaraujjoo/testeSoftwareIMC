# testeSoftwareIMC

# Analisador de Dados Binários – Projeto de Teste de Software

Este projeto foi desenvolvido como parte da disciplina de **Teste de Software** no curso de **Ciência da Computação**. Ele tem como objetivo realizar a leitura de registros binários contendo dados pessoais de crianças, validar essas informações e calcular a classificação do IMC (Índice de Massa Corporal), com base na idade e no gênero.

## 📌 Funcionalidade

O programa realiza as seguintes tarefas:

- Lê um arquivo binário chamado `dados.bin` contendo registros de:
  - Nome (até 30 caracteres)
  - Data de nascimento (formato `YYYY-MM-DD`)
  - Gênero (`Masc` ou `Femi`)
  - Peso (em Kg)
  - Altura (em metros)
- Valida os dados lidos, verificando formato da data, valores numéricos e consistência de gênero.
- Calcula a idade com base na data de nascimento.
- Avalia o IMC da criança e determina a categoria:
  - Abaixo do peso
  - Peso normal
  - Sobrepeso
  - Obesidade
- Exibe as informações processadas no terminal.


## 🚀 Execução

Para rodar o programa, basta executar o arquivo principal:

```bash
python nome_do_arquivo.py
```

Certifique-se de que o arquivo `dados.bin` esteja no mesmo diretório do script.
