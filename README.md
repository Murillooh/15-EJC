# Projeto Estoque

Aplicação simples de gestão de estoque em HTML/CSS/JavaScript.

## Arquivos principais
- `index.html` — página principal do sistema de estoque, com cadastro de produtos, carrinho, relatórios e exportação.
- `estoque_elegante.html` — outra versão de interface do estoque.

## Funcionalidades
- Visualização do inventário de produtos
- Ajuste de estoque (+ / -)
- Adição de itens ao carrinho
- Visualização de detalhes do produto em modal
- Registro de saídas de estoque
- Exportação de inventário, histórico de saídas e relatório completo em CSV

## Como usar a exportação de relatórios
1. Acesse a aba `Relatórios` no painel principal.
2. Clique em `Exportar relatório` para gerar um arquivo CSV completo.
3. O arquivo inclui:
   - resumo com total em estoque, saídas, itens e fornecedores
   - tabela de inventário com status de cada produto
   - tabela de histórico de saídas com datas e valores
4. Salve o arquivo no seu computador e abra com Excel, LibreOffice ou outro leitor de CSV.

## Como rodar
1. Abra o terminal na pasta do projeto:
   ```powershell
   cd "c:\Users\Murillo Silva\Documents\Projeto Estoque"
   ```
2. Inicie um servidor local:
   ```powershell
   python -m http.server 8000
   ```
3. Acesse no navegador:
   ```
   http://localhost:8000/index.html
   ```

## GitHub
- Branch atual: `15-EJC`
- Repositório remoto `ejc`: `git@github.com:Murillooh/15-EJC.git`

## Observações
- Nenhuma dependência externa é necessária para rodar o projeto localmente.
- O projeto funciona diretamente no navegador com o servidor local.
