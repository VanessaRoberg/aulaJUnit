# Aula JUnit — projeto original para a turma

Projeto mínimo com classe Calculadora e seis testes JUnit 5. Os arquivos de código e configuração foram escritos para esta aula, sem copiar repositórios de terceiros.

## Executar no navegador

1. Crie um repositório privado vazio no GitHub.
2. Descompacte o ZIP e envie os arquivos e pastas ao repositório, incluindo a pasta oculta `.devcontainer`. Confira se ela foi enviada.
3. Abra **Code > Codespaces > Create codespace on main**.
4. Aguarde o ambiente ficar pronto e execute `mvn test` no terminal.
5. Resultado esperado: `Tests run: 6, Failures: 0, Errors: 0`.

Para demonstrar uma falha, troque `return a+b;` por `return a-b;` em Calculadora.java e execute `mvn test`. Depois, restaure.

## Dependências e segurança

Não há scripts de terceiros copiados nem credenciais. Contudo, a execução exige componentes externos: imagem Eclipse Temurin, pacote Maven, JUnit e plugins Maven. Não é possível executar JUnit real sem utilizar essas dependências. O serviço Codespaces requer conta, internet e cota disponível. Faça um teste antes da aula.
