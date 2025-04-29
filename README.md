
# A3 Media - Web Designer Teste

Este repositório contém a solução do desafio técnico para a vaga de Web Designer da A3 Media.  
O objetivo principal é clonar duas páginas de concorrentes, transformá-las em templates no Astro, integrá-las ao TinaCMS e gerar 1000 variações únicas de cada página.

## 🛠 Tecnologias Utilizadas

- [Astro](https://astro.build/) - Framework de construção de sites rápidos.
- [TinaCMS](https://tina.io/) - CMS headless para edição de conteúdo.
- [faker-js](https://fakerjs.dev/) - Geração de conteúdo fake para testes.

## 🚀 Funcionalidades

- Clonagem fiel de duas páginas de exemplo.
- Criação de templates reutilizáveis com Astro.
- Integração com TinaCMS para gerenciamento dinâmico do conteúdo.
- Geração automática de 1000 páginas por template com dados únicos.
- URLs dinâmicas no formato:
  - `/paginatemplate1/1` até `/paginatemplate1/1000`
  - `/paginatemplate2/1` até `/paginatemplate2/1000`

## 🧪 Como executar localmente

### 1. Clone o repositório:

```bash
git clone https://github.com/fernando-c-lima/a3media-landing-generator.git
cd a3media-landing-generator
```

### 2. Instale as dependências:

Se estiver usando **npm**:
```bash
npm install
```

Ou, se preferir usar **yarn**:
```bash
yarn install
```

### 3. Inicie o projeto localmente:

```bash
npm run dev
```

### 4. Acesse no navegador:

```
http://localhost:4321
```

## ✍️ Observações

- O conteúdo gerado usa o `faker-js` para garantir que cada página tenha texto único.
- Todas as edições feitas pelo TinaCMS são refletidas diretamente no site.
- O projeto foi desenvolvido com foco em performance, organização e legibilidade do código.

## 📸 Demonstração

_(Adicione aqui prints ou um vídeo curto da navegação entre as páginas geradas, se possível)_

## 📩 Contato

- Desenvolvido por **Fernando Caetano**
- GitHub: [fernando-c-lima](https://github.com/fernando-c-lima)
- Email: **fernandocaetano001@gmail.com**
