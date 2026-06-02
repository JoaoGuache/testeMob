
# Relatório de Teste - mobapps.com.br

> Projeto: Testes Manuais de Interface e Usabilidade
>
> Site testado: mobapps.com.br
>
> Tipo de teste: Manual
>
> Status geral: Falhas pontuais identificadas

---

# Sumário Executivo

Este relatório documenta as falhas encontradas durante a execução de testes manuais no Site da Mobapps.
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

# Falhas Encontradas

## CT-01 - Validacao do campo Nome no formulario de interesse

| Campo | Detalhe |
|--------|---------|
| ID | CT-01 |
| Modulo | Formulario |
| Severidade | Baixa |
| Prioridade | Media |
| Ambiente | Chrome 137 |

### Passos para reproduzir

1. Acesse a home
2. Clique em "Falar com especialista"
3. Digitar numerais no campo de Nome

**Resultado esperado**

O sistema deve exibir uma mensagem de resposta inválida.

**Resultado obtido**

O formulário é aceito e confirmado o envio.

---

## CT-02 - Botao "Seja um caso de sucesso" embaixo do video do Vale Driver

| Campo | Detalhe |
|---------|---------|
| ID | CT-02 |
| Modulo | Botao |
| Gravidade | Baixa |
| Ambiente | Chrome |

### Passos para reproduzir

1. Acesse a home
2. Navegue ate a parte do video do Vale Driver
3. Clique no botao "Seja um caso de sucesso"

### Resultado esperado

Abertura do formulario para preenchimento com as informacoes do usuario.

### Resultado obtido

Nenhuma acao e reproduzida ao clicar no botao.

---

# Conclusao

Foram identificados 2 defeitos durante os testes de interface e usabilidade realizados no site da MobApps.
Os problemas encontrados nao impedem a navegacao do usuario, porem impactam a experiencia e a consistencia do sistema.
Recomenda-se a correcao dos itens reportados antes de futuras atualizacoes do portal.
