
# 📘 Exercícios Práticos — Roadmap Completo para Vue, JavaScript, POO e TypeScript

Este arquivo contém **exercícios progressivos** que cobrem todos os tópicos necessários antes e durante o aprendizado de Vue.

---

# 1️⃣ Fundamentos da Web

## 🌐 HTML — Exercícios
1. Crie uma página com:
   - título
   - parágrafo
   - imagem
   - link que abre em nova aba
2. Crie uma tabela com 4 linhas e 3 colunas.
3. Crie um formulário com:
   - input de texto
   - email
   - senha
   - checkbox
   - botão de submit

---

## 🎨 CSS — Exercícios
1. Estilize a página anterior:
   - Centralize o conteúdo na página.
   - Use `flexbox` para organizar os elementos.
2. Crie um layout com **duas colunas** usando CSS Grid.
3. Recrie a interface de um card de produto (imagem + título + preço + botão).

---

# 2️⃣ JavaScript Básico — Exercícios

1. Crie um script que:
   - peça o nome do usuário,
   - armazene em uma variável,
   - exiba uma saudação no console.
2. Dado um array de números, crie funções para:
   - retornar apenas os números pares,
   - retornar a soma total usando `reduce`.
3. Crie um cronômetro simples com:
   - Start
   - Pause
   - Reset
4. Manipulação do DOM:
   - Altere o texto de um parágrafo ao clicar em um botão.
   - Mostre/oculte um elemento.

---

# 3️⃣ Programação Orientada a Objetos (POO) — Exercícios

1. Crie uma classe `Pessoa` com:
   - nome,
   - idade,
   - método `apresentar()`.
2. Crie uma classe `Produto` com:
   - nome, preço, categoria
   - método `desconto(percentual)`.
3. Simule um mini-sistema:
   - Classe `Usuario`
   - Classe `ListaDeTarefas`
   - Métodos:
     - `adicionarTarefa()`
     - `removerTarefa()`
     - `listarTarefas()`

---

# 4️⃣ TypeScript — Exercícios

1. Tipar as variáveis:
   - nome (string)
   - idade (number)
   - ativo (boolean)
2. Criar uma **interface** `Produto` com:
   - id
   - nome
   - preco
   - categoria
3. Criar uma função genérica:
   ```ts
   function retornarItem<T>(item: T): T
   ```
4. Criar uma classe `ContaBancaria` com:
   - saldo (number)
   - depositar(valor: number)
   - sacar(valor: number)

---

# 5️⃣ Vue 3 — Fundamentos (Composition API)

## 🧩 Exercícios
1. Criar um projeto Vue e exibir:
   - a hora atual  
   - atualizar automaticamente a cada segundo  
2. Criar uma página com:
   - input + botão  
   - quando clicar, adicionar o texto a uma lista exibida na tela  
3. Refatorar usando:
   - `ref`
   - `reactive`
   - `computed` (ex.: total de itens na lista)

---

# 6️⃣ Componentização — Exercícios

1. Criar 3 componentes:
   - `Header.vue`
   - `ProdutoCard.vue`
   - `ListaProdutos.vue`
2. Passar dados via **props** para o card.
3. Emitir evento `adicionarAoCarrinho` do componente filho para o pai.

---

# 7️⃣ Vue Router — Exercícios

1. Criar 3 páginas:
   - Home
   - Produtos
   - Sobre
2. Criar rota dinâmica:
   - `/produto/:id`
3. Página de produto deve:
   - capturar o ID da URL
   - mostrar detalhes fictícios

---

# 8️⃣ Pinia — Exercícios

1. Criar uma store `useCarrinho` com:
   - lista de produtos
   - ação `adicionar`
   - ação `remover`
2. Persistir a store usando localStorage.
3. Exibir total de itens no header usando um getter.

---

# 9️⃣ Requisições HTTP — Exercícios

1. Criar composable `useApi()` com:
   - função `get`
   - função `post`
2. Consumir API Fake Store:
   - exibir lista de produtos
   - exibir detalhes individuais
3. Criar formulário que envia POST para uma API dummy (JSONPlaceholder).

---

# 🔟 Projeto Final

Crie um **E-commerce completo** com:

### ✔️ Funcionalidades obrigatórias:
- Catálogo com lista de produtos da API
- Página individual de produto
- Carrinho com Pinia
- Adicionar / remover itens
- Login fake
- Rotas protegidas
- Deploy em Netlify ou Vercel

### ✔️ Diferenciais:
- Filtros (categoria, preço)
- Dark mode
- Composables reutilizáveis

---

# 🏁 Conclusão

Com estes exercícios, você passa por **todo** o conteúdo necessário para dominar:
- HTML
- CSS
- JavaScript
- POO
- TypeScript
- Vue 3 (Composition API)
- Router
- Pinia
- APIs HTTP

Se quiser, posso criar:
- gabaritos,
- exercícios adicionais,
- uma versão em PDF,
- ou challenges semanais.
