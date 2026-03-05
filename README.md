# projeto1-soma-ci-cd
Primeiro teste usando o github e criando codificação Cobol

Nesse projeto inicial o Cobol foi criado na para interagir com o YAML via Github Actions.
Nele existem dois campos para interação que são utilizados para fazer a soma de ambos.
O projeto está composto da seguinte forma:

- O Cobol está localizado em: projeto1-soma-ci-cd/src/soma.cob
- O YAML está localizado em: projeto1-soma-ci-cd/.github/workflows/cobol-pipeline.yml

Para executar é necessário:

- Acessar a aba Actions;
- Clicar no Workflow COBOL CI/CD Pipeline;
- Clicar em Run workflow;
- Informar os dois valores e clicar novamente em Run workflow (botão verde)
- Aguardar a build-and-test finalizar e clicar nela;
- O resultado estará na aba "Executar valores customizados"

O programa vai:

- Executar o YAML;
- Montar uma máquina Linux para ser utilizada;
- Instalar o Cobol GNU (converte o fonte Cobol em C);
- Compilar o Cobol;
- Executar o Cobol que somará os valores e trará o resultado para o YAML.
