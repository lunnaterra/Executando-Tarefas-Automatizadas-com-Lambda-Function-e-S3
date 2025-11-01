# Desafio AWS Lambda + S3 - DIO

## Descrição do Projeto
Este projeto foi criado como parte do desafio DIO para demonstrar a integração entre AWS Lambda e S3, automatizando tarefas de armazenamento de arquivos na nuvem.

## Objetivos
- Aplicar conceitos de automação usando AWS Lambda.
- Enviar arquivos automaticamente para um bucket S3.
- Documentar o processo para referência futura e estudo.

## Estrutura do Repositório
- `lambda/` → Contém o código da função Lambda (`minha_lambda.py`).
- `README.md` → Documentação detalhada do projeto.

## Funcionamento
A função Lambda:
1. Conecta ao bucket S3 especificado.
2. Cria um arquivo de exemplo (`exemploteste.txt`).
3. Insere o conteúdo no bucket automaticamente.

## Passos para Deploy
1. Criar ou identificar um bucket S3 na AWS.
2. Criar uma função Lambda no console AWS.
3. Copiar o código `minha_lambda.py` para a função Lambda.
4. Configurar permissões adequadas (policy permitindo `s3:PutObject`).
5. Executar a função e verificar se o arquivo foi criado no bucket S3.

## Aprendizados
- Criação e execução de funções Lambda.
- Integração de Lambda com S3.
- Prática de automação de tarefas na AWS.
- Organização de repositório para documentação técnica.

