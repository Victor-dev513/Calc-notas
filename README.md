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
