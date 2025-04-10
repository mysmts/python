📚 SCRIPT: scraping_books.py

🧠 O QUE ELE FAZ:
Esse script acessa o site "Books to Scrape" (http://books.toscrape.com/), que é uma página pública de teste para scraping, e coleta informações de diversos livros listados no site.

🔎 INFORMAÇÕES COLETADAS:
- Título do livro
- Preço
- Quantidade de estrelas (rating)

🚀 COMO FUNCIONA:
1. Usa a biblioteca `aiohttp` para fazer múltiplas requisições ao mesmo tempo (assíncronas), tornando o processo mais rápido.
2. A biblioteca `BeautifulSoup` é usada para analisar o conteúdo HTML da página.
3. O script percorre todas as páginas do site de livros e exibe as informações no terminal (pode ser adaptado para salvar em arquivo também).

🛠 BIBLIOTECAS NECESSÁRIAS:
- aiohttp
- asyncio
- BeautifulSoup4

✅ COMO RODAR:
1. Instale as bibliotecas se ainda não tiver:
