# Relatório de Teste - mobapps.com.br

> Projeto: Testes Manuais de Interface e Usabilidade
> Site testado: mobapps.com.br
> Tipo de teste: Manual
> Status geral: Falhas pontuais identificadas


---

# Sumário Executivo

Este relatório documenta as falhas encontradas durante a execução de testes manuais no Site da Mobapps

Foram executados cenários de teste cobrindo:

- Cadastro
- Navegação
- Responsividade

---

## Métricas 

| Métrica | Valor |
|----------|----------|
| Casos com falha | 2 |
| Severidade Média | 1 |
| Severidade Baixa | 1 |

# 🐛 Falhas Encontradas

CT-01 – Validação do campo Nome no formulário de interesse
| Campo | Detalhe |
|--------|---------|
| ID | CT-01 |
| Módulo | Formulário |
| Severidade | Baixa |
| Prioridade | Média |
| Ambiente | Chrome 137 |

### Passos para reproduzir

1. Acesse a home
2. Clique em "Falar com especialista"
3. Digitar numerais no campo de Nome

### Resultado esperado 

O sistema deve exibir uma mensagem de resposta inválida.

## Resultado obtido

O formulário é aceito e confirmado o envio.

## CT 02 - Botão de "Seja um caso de sucesso" embaixo do vídeo do Vale driver
| Campo | Botão | 
| ---------| -------|
| ID | CT - 02 |
| Módulo | Botão |
| Gravidade | Baixa |
| Ambiente | Chrome |

### Passos para reproduzir

1. Acesse a home
2. Navegue até a parte do vídeo do Vale Driver
3. Clique no botão " Seja um caso de sucesso"

## Resultado esperado

Abertura do formulário para preenchimento com as informações do usuário.

## Resultado obtido

Nenhuma ação é reproduzida ao clicar no botão.

# 📌 Conclusão

Foram identificados 2 defeitos durante os testes de interface e usabilidade realizados no site da MobApps.

Os problemas encontrados não impedem a navegação do usuário, porém impactam a experiência e a consistência do sistema.

Recomenda-se a correção dos itens reportados antes de futuras atualizações do portal.
