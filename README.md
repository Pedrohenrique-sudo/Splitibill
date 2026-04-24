# SplitBill - Divisor de Contas

Uma aplicação web moderna e intuitiva para dividir contas e calcular gorjetas de forma rápida e sem complicações.

## 🎯 Funcionalidades

- **Cálculo Automático**: Divida o valor total entre quantas pessoas quiser
- **Gorjeta Inteligente**: Calcule gorjetas com percentuais pré-definidos (10%, 15%, 20%) ou personalizados
- **Gerenciamento de Pessoas**: Adicione ou remova participantes dinamicamente
- **Nomes Personalizados**: Identifique cada pessoa com um nome customizado
- **Resumo Detalhado**: Visualize o breakdown completo da conta e quanto cada pessoa deve pagar
- **Interface Responsiva**: Funciona perfeitamente em desktop, tablet e mobile

## 🎨 Design

O projeto foi desenvolvido com a filosofia de **Minimalismo Moderno com Foco em Usabilidade**, priorizando:

- **Clareza**: Cada elemento tem um propósito específico
- **Hierarquia Visual**: Tipografia forte (Poppins) combinada com corpo legível (Inter)
- **Cores Significativas**: Verde vibrante representa sucesso e transações bem-sucedidas
- **Interações Suaves**: Transições fluidas e feedback imediato ao usuário

## 🚀 Como Usar

### Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/splitbill.git
cd splitbill

# Instale as dependências
pnpm install

# Inicie o servidor de desenvolvimento
pnpm dev
```

A aplicação estará disponível em `http://localhost:3000`

### Uso

1. **Insira o valor total** da conta no campo "Valor Total da Conta"
2. **Escolha a gorjeta** clicando em um dos percentuais pré-definidos ou digitando um valor customizado
3. **Adicione participantes** usando o botão "Adicionar Pessoa"
4. **Visualize o resultado** no painel à direita com o valor que cada pessoa deve pagar

## 🛠️ Stack Tecnológico

- **Frontend**: React 19 + TypeScript
- **Estilização**: Tailwind CSS 4
- **Componentes**: shadcn/ui
- **Ícones**: Lucide React
- **Build**: Vite
- **Roteamento**: Wouter

## 📁 Estrutura do Projeto

```
splitbill/
├── client/
│   ├── public/              # Arquivos estáticos
│   ├── src/
│   │   ├── components/      # Componentes reutilizáveis
│   │   │   └── SplitBillCalculator.tsx
│   │   ├── pages/           # Páginas da aplicação
│   │   │   └── Home.tsx
│   │   ├── App.tsx          # Componente raiz
│   │   ├── main.tsx         # Entry point
│   │   └── index.css        # Estilos globais
│   └── index.html
├── server/                  # Placeholder para compatibilidade
├── package.json
└── README.md
```

## 🎨 Customização

### Alterar Cores

Edite o arquivo `client/src/index.css` e modifique as variáveis CSS no `:root`:

```css
:root {
  --primary: oklch(0.65 0.2 142); /* Verde vibrante */
  --background: oklch(0.98 0.001 0); /* Branco/cinza claro */
  /* ... outras variáveis */
}
```

### Alterar Tipografia

As fontes estão definidas em `client/index.html`. Para mudar, atualize o link do Google Fonts e os valores em `index.css`.

## 📦 Build para Produção

```bash
# Gere a build otimizada
pnpm build

# Visualize a build localmente
pnpm preview
```

## 🤝 Contribuições

Sugestões e melhorias são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

## 📄 Licença

Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para detalhes.

## 💡 Ideias Futuras

- Histórico de divisões anteriores
- Exportar resultado em PDF
- Modo escuro
- Suporte a múltiplas moedas
- Sincronização com contatos

---

Feito por Pedro Henrique ✅para simplificar a vida financeira do dia a dia.
