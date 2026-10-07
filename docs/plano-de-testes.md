# Plano de testes: Sauce Demo

| Campo | Valor |
|---|---|
| Versão do documento | 0.1 |
| Autor | |
| Data | |
| Aplicação | https://www.saucedemo.com |

## 1. Objetivo

<!-- O que este plano pretende verificar e qual decisão ele apoia. -->

## 2. Escopo

### 2.1 Funcionalidades incluídas

| Área | Incluída? | Prioridade | Justificativa |
|---|---|---|---|
| Login | | | |
| Listagem de produtos | | | |
| Ordenação de produtos | | | |
| Detalhe do produto | | | |
| Carrinho | | | |
| Checkout: informações | | | |
| Checkout: resumo | | | |
| Checkout: conclusão | | | |
| Menu lateral (logout, reset, about) | | | |

### 2.2 Fora do escopo

<!-- O que não será testado e por quê (ex.: desempenho, segurança, compatibilidade mobile). -->

-

## 3. Abordagem

<!-- Tipos de teste e técnicas usadas. -->

- **Teste exploratório:**
- **Teste funcional baseado em casos (Gherkin):**
- **Avaliação de usabilidade (heurísticas de Nielsen):**
- **Técnicas de projeto de teste:** <!-- ex.: partição de equivalência, valor limite -->

## 4. Ambiente

| Item | Valor |
|---|---|
| Navegador(es) e versão | |
| Sistema operacional | |
| Resolução | |

## 5. Usuários de teste

<!-- Liste os usuários exibidos na tela de login e o que você espera validar com cada um. -->

| Usuário | Finalidade no teste |
|---|---|
| | |

## 6. Critérios

### 6.1 Entrada

-

### 6.2 Saída

-

## 7. Severidade dos bugs

<!-- Critérios usados para classificar as Issues. Ajuste se necessário. -->

| Severidade | Critério |
|---|---|
| Crítica | Bloqueia um fluxo principal (ex.: impossível concluir login ou compra) sem contorno. |
| Alta | Funcionalidade importante com comportamento incorreto; existe contorno difícil. |
| Média | Comportamento incorreto em funcionalidade secundária ou com contorno simples. |
| Baixa | Problema visual, de texto ou cosmético, sem impacto na função. |

### 7.1 Prioridade dos bugs

<!-- Severidade mede o impacto; prioridade mede a urgência da correção. Um bug de severidade baixa pode ter prioridade alta (ex.: erro de texto na tela inicial). -->

| Prioridade | Critério |
|---|---|
| Alta | Corrigir antes da próxima entrega. |
| Média | Corrigir em uma das próximas entregas. |
| Baixa | Corrigir quando houver capacidade. |

## 8. Evidências

Arquivos salvos em [`docs/evidencias/`](evidencias/), nomeados pelo ID do caso ou do bug:

| Origem | Padrão | Exemplo |
|---|---|---|
| Caso de teste | `CT-<nº>_<descricao>.<ext>` | `CT-001_login-valido.png` |
| Bug | `BUG-<nº>_<descricao>.<ext>` | `BUG-01_imagem-produto.png` |
| Sessão exploratória | `SE-<nº>_<descricao>.<ext>` | `SE-01_menu-lateral.png` |

## 9. Riscos e premissas

| Risco / premissa | Impacto | Mitigação |
|---|---|---|
| | | |

## 10. Entregáveis

- [Sessão exploratória](sessao-exploratoria.md)
- [Casos de teste](casos-de-teste.md)
- [Avaliação de usabilidade](avaliacao-usabilidade.md)
- [Relatório de execução](relatorio-de-execucao.md)
- Bugs registrados no GitHub Issues

## 11. Cronograma

| Atividade | Data prevista | Status |
|---|---|---|
| Sessão exploratória | | |
| Escrita dos cenários e casos de teste | | |
| Execução e registro de bugs | | |
| Avaliação de usabilidade | | |
| Relatório de execução | | |
