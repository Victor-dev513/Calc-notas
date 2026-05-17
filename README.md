# Calculadora de Média

Projeto Python que calcula a média ponderada de um aluno e determina sua situação (aprovado, recuperação ou reprovado).

## Funcionalidades

- **Cálculo de Média Ponderada**: A terceira nota tem peso 2x
- **Validação de Notas**: Apenas notas entre 0.0 e 10.0 são aceitas
- **Classificação**: Retorna "aprovado", "recuperacao" ou "reprovado"

## Critérios

- **Aprovado**: Média >= 7.0
- **Recuperação**: Média entre 4.0 e 6.9
- **Reprovado**: Média < 4.0

## Arquivos

- `calculadora.py` - Funções principais do projeto
- `test_calculadora.py` - Testes unitários com pytest
- `README.md` - Documentação do projeto

## Como executar os testes

```bash
pytest -v
```

Todos os testes devem passar com sucesso.

## Comandos utilizados

```powershell
cd e:\Calc-notas

gh repo create Victor-dev513/Calc-notas --public --source=. --remote=origin --push

git checkout -b feature/testes
# faça alterações e commits claros
git add .
git commit -m "chore: criar estrutura inicial"
git commit -m "feat: implementar função calcula_media"
git commit -m "feat: implementar função situacao"
git commit -m "test: adicionar testes unitários"
git commit -m "ci: adicionar workflow de testes GitHub Actions"

git checkout master
git merge feature/testes
git push origin master

gh repo clone Victor-dev513/Calc-notas teste-clone
cd teste-clone
pytest -v
```
## Exemplo de uso
python calculadora.py

Esses são os comandos que foram usados para criar o repositório, fazer branch e merge, e testar em outra pasta.