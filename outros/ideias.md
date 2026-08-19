# Ideias de Funcionalidades para o Tchê Musics

## 📌 1. Contador de músicas
Quando a página carregar:

```text
Total de músicas: 43
```

Você pode contar automaticamente quantos cards existem.

```javascript
const musicas = document.querySelectorAll(".card-musica");
contador.textContent = musicas.length;
```

---

## 📌 2. Mostrar o ano atual automaticamente

Em vez de escrever:

```text
© 2026
```

Use:

```javascript
const ano = new Date().getFullYear();
```

---

## 📌 3. Saudação

Dependendo da hora do dia:

```text
Bom dia!

Boa tarde!

Boa noite!
```

---

## 📌 4. Botão "Voltar ao topo"

Quando o usuário descer bastante a página, aparece:

```text
⬆ Voltar ao topo
```

```javascript
window.scrollTo({
    top: 0,
    behavior: "smooth"
});
```

---

## 📌 5. Contador de caracteres

Nos campos `<textarea>`.

Enquanto escreve:

```text
123/300 caracteres
```

---

## 📌 6. Limpar formulário

Criar um botão:

```text
Limpar formulário
```

Utilizando:

```javascript
form.reset();
```

---

## 📌 7. Confirmar antes de limpar

Antes de limpar o formulário:

```text
Tem certeza?

Sim
Cancelar
```

Utilizando:

```javascript
confirm();
```

---

## 📌 8. Confirmar saída da página

Caso o usuário tenha começado a preencher o formulário:

```text
Você realmente deseja sair?
```

---

## 📌 9. Destacar o menu atual

Quando estiver na página:

```text
🏠 Início
```

fica destacado.

Quando estiver em:

```text
📖 Biografias
```

o destaque muda automaticamente.

---

## 📌 10. Mudar a cor de um botão quando clicado

Exemplo:

```text
Curtir
```

Cinza →

Verde.

---

## 📌 11. Mostrar quantidade de respostas do formulário

Depois do envio:

```text
Você respondeu 18 perguntas.
```

---

## 📌 12. Mostrar quantas opções foram marcadas

Nos checkboxes:

```text
Aspectos escolhidos

3 selecionados
```

---

## 📌 13. Mostrar mensagens abaixo dos campos

Ao invés de usar:

```javascript
alert("Nome inválido");
```

Mostrar:

```text
Nome
________________

⚠ Informe um nome válido.
```

---

## 📌 14. Data da última atualização

Exemplo:

```text
Última atualização:

11/07/2026
```

---

## 📌 15. Contador de visitas (LocalStorage)

Primeira visita:

```text
Bem-vindo!
```

Demais visitas:

```text
Você já visitou este site 12 vezes.
```

---

## 📌 16. Salvar o nome do visitante (LocalStorage)

Primeira visita:

```text
Gabriel
```

Na próxima:

```text
Olá novamente, Gabriel!
```

---

## 📌 17. Lembrar o tema escolhido

Mesmo fechando o navegador.

---

## 📌 18. Pesquisa ignorando maiúsculas e minúsculas

Pesquisar:

```text
os monarcas
```

Encontrar:

```text
Os Monarcas
```

---

## 📌 19. Mostrar quantos resultados foram encontrados

Pesquisar:

```text
Gaúcho
```

Resultado:

```text
7 músicas encontradas.
```

---

## 📌 20. Botão "Mostrar mais"

Ao invés de carregar todas as músicas.

Inicialmente:

```text
10 músicas
```

Depois:

```text
Mostrar mais
```

Mostra mais 10.

---

# 🔍 Pesquisa

## Pesquisa enquanto digita

Sem precisar apertar Enter.

---

## Destacar o texto encontrado

Pesquisar:

```text
Monarcas
```

Resultado:

```html
Os <mark>Monarcas</mark>
```

---

## Mensagem quando não encontrar

```text
Nenhuma música encontrada.
```

---

# 📄 Formulário

## Barra de progresso

```text
██████░░░░ 60%
```

Conforme o usuário responde.

---

## Contador de perguntas respondidas

```text
5 de 12 perguntas respondidas.
```

---

## Mostrar força da senha (caso exista login)

```text
Senha

Fraca
Média
Forte
```

---

## Mostrar o e-mail em verde quando válido

Enquanto o usuário digita.

---

## Mostrar mensagens abaixo dos campos

Ao invés de usar `alert()`.

---

# 🎨 Interface

## Alterar tamanho da fonte

```text
A-
A+
```

---

## Alterar espaçamento

```text
Compacto

Normal

Grande
```

---

## Trocar a cor principal

Sem usar LocalStorage.

---

## Mostrar um loading

Enquanto a página carrega.

```text
Carregando...
```

---

# 📱 Responsividade

## Menu hambúrguer

Mostrar automaticamente em telas pequenas.

---

# ⌨️ Atalhos

## Pesquisa

Pressionar:

```text
/
```

Abre a pesquisa.

---

## Fechar menus

Pressionar:

```text
ESC
```

Fecha menus ou pop-ups.

---

# 🎲 Recursos aleatórios

## Música aleatória

Botão:

```text
🎲 Surpreenda-me
```

Escolhe uma música aleatória.

---

## Curiosidade aleatória

Exemplo:

```text
Curiosidade do dia:

O acordeão é um dos instrumentos mais marcantes da música gaúcha.
```

---

# 📊 Informações

Mostrar automaticamente:

```text
Total de artistas: 27

Total de músicas: 158

Total de biografias: 31
```

---

# ♿ Acessibilidade

## Destacar foco usando TAB

Mostrar um contorno visível.

---

## Permitir fechar pop-ups com ESC

---

## Link oculto

```text
Ir para o conteúdo principal
```

---

# 🛠️ Recursos do JavaScript

## Mostrar a data atual

```text
Hoje é

14/07/2026
```

---

## Mostrar a hora em tempo real

```text
21:43:10
```

---

## Mostrar quanto tempo o usuário ficou na página

Exemplo:

```text
Você está neste site há:

12 minutos
```

---

## Detectar quando a internet caiu

```text
⚠ Você está offline.
```

Quando voltar:

```text
✔ Conexão restabelecida.
```

# SEO

## Meta Description

Utilizada pelos mecanismos de busca para exibir um pequeno resumo da página nos resultados de pesquisa.

```html
<meta
    name="description"
    content="Biblioteca de músicas gaúchas, artistas, biografias e cultura tradicionalista.">
```

---

## Meta Keywords (Opcional)

Atualmente possui pouca influência no SEO, mas ainda pode ser utilizada para documentar palavras-chave relacionadas ao conteúdo da página.

```html
<meta
    name="keywords"
    content="música gaúcha, CTG, tradicionalismo, artistas">
```

---

## Meta Author

Informa quem é o autor ou responsável pelo desenvolvimento da página.

```html
<meta
    name="author"
    content="Gabriel Passos">
```