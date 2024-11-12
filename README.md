

## Introdução

Este projeto implementa um sistema de visualização de dados financeiros, apresentando uma página de login e uma página de painel de controle (dashboard). A solução é desenvolvida com Next.js e TypeScript, e estilizada com Tailwind CSS, além de incluir filtros dinâmicos e persistência de sessão.

---

## Requisitos do Projeto

1. **Página de Login e Dashboard**: 
   - Criação de uma página de login para autenticação do usuário.
   - Implementação de uma página de dashboard protegida pelo login, acessível apenas a usuários autenticados.

2. **Filtros Dinâmicos e Globais**:
   - Filtros dinâmicos que atualizam o conteúdo da página conforme o filtro é aplicado.
   - Atualização de dados exibidos em tempo real, refletindo seleções de filtros como datas, contas, categorias e estado.

3. **Cards Resumo**:
   - Exibição de cards para resumo de dados, mostrando informações como receitas, despesas, transações pendentes e saldo total.

4. **Visualização de Dados com Gráficos**:
   - Implementação de gráficos de barras empilhadas e gráficos de linhas para visualização das transações.
   - Flexibilidade na definição dos dados a serem exibidos nos gráficos.

5. **Barra Lateral**:
   - Criação de uma barra lateral exclusiva na página de dashboard, contendo botões de Logout e Home para navegação.

6. **Persistência da Sessão e Filtros**:
   - Implementação de persistência de sessão do usuário e do estado dos filtros, sem necessidade de banco de dados.

7. **Design Responsivo e Interativo**:
   - Interface responsiva e amigável para dispositivos móveis e desktops.

8. **Tecnologias Utilizadas**:
   - Desenvolvimento com Next.js e TypeScript.
   - Estilização com Tailwind CSS.

---

## Dados do Projeto

Para os dados financeiros, utilize o arquivo de transações fornecido. As informações de cada transação são representadas pelos metadados a seguir:

- **"date"**: Data da transação ISO 8601.
- **"amount"**: Valor da transação, sem separador decimal (ex: "5565" representa R$ 55,65).
- **"transaction_type"**: Tipo de transação ("deposit" para entrada ou "withdraw" para saída).
- **"currency"**: Moeda da transação.
- **"account"**: Conta de origem ou destino da transação.
- **"industry"**: Categoria da empresa associada à transação.
- **"state"**: Estado de registro da empresa.

---

## Recomendações Opcionais

Para aprimorar o projeto, as seguintes recomendações podem ser seguidas:

- **Deploy**: Fazer o deploy do projeto em uma plataforma como Vercel, proporcionando um link público de acesso ao sistema.
- **Bibliotecas de Componentes e Gráficos**: Uso de bibliotecas de componentes (MUI, Chakra) e bibliotecas de gráficos (Highcharts, Chart.js) para melhor visualização dos dados.
- **Testes Unitários**: Implementar testes unitários para garantir a confiabilidade do sistema.
- **Cache do Next.js**: Utilização do cache do Next.js para otimização de performance.

---

