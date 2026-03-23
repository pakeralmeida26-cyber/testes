# 🧪 Unit Testing Lab - JavaScript

Laboratório de Testes Unitários em JavaScript usando Jest.

## 📁 Estrutura do Projeto

```
unit-testing-lab-js-master/
├── 01-unit-test-basic/
│   └── src/
│       ├── discount.js      # Funções de desconto
│       ├── price.js         # Funções de preço
│       ├── product.js       # Funções de produto
│       └── shipping.js      # Funções de frete
│
├── 02-tdd-project/
│   ├── src/
│   │   ├── coreMath.js      # Operações matemáticas (calculadora)
│   │   └── businessLogic.js # Lógica de negócio
│   ├── tests/
│   │   ├── coreMath.test.js      # Testes de matemática
│   │   └── businessLogic.test.js # Testes de negócio
│   └── package.json
│
├── .gitignore
├── package.json
└── README.md
```

## 🚀 Como Executar

### Pré-requisitos
- Node.js instalado (v14+)
- npm ou yarn

### Instalação

```bash
# Entrar na pasta do projeto TDD
cd 02-tdd-project

# Instalar dependências
npm install
```

### Executar Testes

```bash
# Executar todos os testes
npm test

# Executar com watch mode (re-executa ao salvar)
npm run test:watch

# Executar com relatório de cobertura
npm run test:coverage
```

## 📦 Módulos

### 01-unit-test-basic/src/

| Arquivo | Descrição |
|---------|-----------|
| `discount.js` | Cálculo de descontos, desconto progressivo |
| `price.js` | Formatação, conversão e validação de preços |
| `product.js` | CRUD de produtos, estoque |
| `shipping.js` | Cálculo de frete por peso/distância |

### 02-tdd-project/src/

| Arquivo | Descrição |
|---------|-----------|
| `coreMath.js` | Calculadora com operações básicas e científicas |
| `businessLogic.js` | Lógica de carrinho, pedidos, parcelas |

## ✅ Funcionalidades Testadas

### Core Math (Calculadora)
- ✅ Soma, Subtração, Multiplicação, Divisão
- ✅ Raiz Quadrada, Potência
- ✅ Porcentagem, Módulo
- ✅ Fatorial, Valor Absoluto
- ✅ Logaritmos (natural e base 10)
- ✅ Trigonometria (seno, cosseno, tangente)

### Business Logic
- ✅ Cálculo de subtotal do carrinho
- ✅ Aplicação de cupons de desconto
- ✅ Cálculo de impostos
- ✅ Cálculo de parcelas (com/sem juros)
- ✅ Verificação de frete grátis
- ✅ Margem de lucro e markup

## 📊 Cobertura de Testes

Execute `npm run test:coverage` para ver o relatório completo.

## 👨‍🎓 Autor

Projeto desenvolvido para fins educacionais - Disciplina de Testes de Software.

## 📄 Licença

MIT License
