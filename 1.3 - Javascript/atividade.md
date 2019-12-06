# Passo 3 - Javascript

1. Crie uma função chamada `getFavs`. Dentro, execute:
   alerta ('clicado')

2. Crie uma variável `button` e defina-a como uma referência ao nosso botão usando:
   document.querySelector ('botão')

3. Adicione um ouvinte de evento de clique ao botão que chama `getFavs`.
   Clique no botão e verifique se o alerta é exibido.

4. Substitua a chamada `alert` por uma nova variável `favList` definida como uma matriz vazia: []

5. Crie uma variável const `inputs` definida para todas as entradas na página.
   `querySelectorAll` ajudará aqui.

6. Repita todas as entradas usando:
   para (entrada constante de entradas) {}

7. Em cada iteração, use uma instrução `if` para verificar se`input.checked` é igual a true

8. Se os testes acima forem aprovados, envie o `input.parentNode.textContent` para o`favList`
   matriz passando o texto como um parâmetro para `favList.push ()`

   - `push` é um método de matriz embutido: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/push

9. Fora do loop for, use `document.querySelector ('. Favorites')` para direcionar o
   div na parte inferior da página. Defina o `textContent` da div como `favList.join ('')`.
   Isso unirá cada um dos alimentos em uma cadeia separada por um espaço.

```
<label><input type="checkbox" />Ice cream</label>
<label><input type="checkbox" />Pizza</label>
<label><input type="checkbox" />Tacos</label>
<label><input type="checkbox" />Meatloaf</label>
<label><input type="checkbox" />Brocolli</label>

<button>Display Your Favorites</button>

<div class="favorites"></div>
```

Dica: Cole o código acima no `HTML` de um codePen, e edite a aba `JS`. https://codepen.io/

HELP!! https://codepen.io/brunomarram/pen/WNbQRKm
