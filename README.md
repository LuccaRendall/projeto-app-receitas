## [Taste & Travel](https://projeto-app-receitas-sigma.vercel.app/)
Esta foi uma aplicação incrível que tive a oportunidade de desenvolver durante o módulo de Front end na Trybe.

O objetivo do projeto era desenvolver um app de receitas, e para isto utilizamos React Hooks e Context API.

Acesse o app Taste & Travel pelo link:
https://projeto-app-receitas-sigma.vercel.app/

## Layout Mobile First

A aplicação foi pensada para ser usada na versão mobile. Pensando nisso, para melhor visualização utilize a resolução 360 x 650 pixel

## Bibliotecas / API
* React
	 * React Router
	 * React Hooks
	 * React Context API
* Usamos o método `fetch` para chamar a API.
* As APIs utilizadas no projeto foram:    
[The Meal DB](http://themealdb.com/) e [The CocktailDB](https://www.thecocktaildb.com/api.php)

* A estilização foi feita inteiramente usando CSS puro

## Fluxo
![paginação](https://i.ibb.co/NsTJWr6/Sem-nome-1441-800-px.png)

1. **Login**
> O e-mail é verificado usando regex, assim como a senha. A senha deve ter mais de 6 caracteres. Só então o botão de login é habilitado.
> 
> Quando isso acontece, um localStorage é configurado com a chave "email" e valor como o e-mail que o usuário digitou.

2. **Explorar**
> Aqui a pessoa usuária tema opção de explorar receitas filtrando por ingredientes, nacionalidade da receita ou uma opção aleatória chamada "Me surpreenda!"

3. **Pagina principal de receitas**
> A pessoa usuária pode pesquisar por uma refeição específica ou listar por categorias.
No rodapé, você tem a opção de navegar para as páginas exclusivas de comidas ou bebidas ou ainda para a aba explorar.

4. **Perfil**
> Na pagina de perfil, a pessoa usuária pode ver as receitas que ela já finalizou, receitas favoritadas e fazer logout.

5. **Exemplo de receita em progresso**
> Exemplo de uma pagina de receita em progresso, ao marcar todos os ingredientes como concluídos o botão de finalizar receita é habilitado e ao clicar nele a receita é adicionada a aba de receitas prontas

## Autores
<img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" width=15> [Helio Siqueira](https://github.com/Helio-Siqueira)

<img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" width=15> [João Carlos Vieira Filho](https://github.com/jvieyrah)

<img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" width=15> [Lucca Rendall](https://github.com/LuccaRendall)

<img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" width=15> [Luiz Tharik Lemos](https://github.com/Thariklz)

<img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" width=15> [Ronan Salvador](https://github.com/ronansalvador)

## Executar localmente
1) Clonar o repositório
2) Instalar dependências com `npm install`
3) Entre na pasta do projeto e execute `npm start`
4) Pronto, projeto rodando em: `http://localhost:3000/`

## UI/UX
Protótipo desenvolvido pelo [Luiz Tharik](https://github.com/Thariklz) e utilizado como base para a estilização original do projeto:
[Imagem - protótipo](https://xd.adobe.com/view/104becd5-1277-4374-bfbd-fc29ec292846-4518/screen/78c81353-87c6-4250-a779-c2c38d1cc539/)

