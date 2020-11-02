# Como é organizado um código JavaScript em sua forma mais básica?

Pensando sobre a sua forma mais básica de organização, o JavaScript é organizado em **linhas de código**(ou sentença de código) e em **blocos de código**(agrupamento de sentença de código).

```javascript
console.log("ISSO É UMA LINHA DE CÓDIGO EM JS/Sentença de código")
```
A sentença de código citada acima, **pode** também terminar com ; (ponto e virgula): 

```javascript
console.log("Sentença de código");
```

Por outro lado, o código em JS também pode ser organizado em bloco de código:

```javascript
{
    console.log("Hello")
    console.log("World!");
}
```
Nesse exemplo, acima pode-se perceber, que uma das sentenças (ao todo temos **duas sentenças de código**) no bloco de código, há ;, e é você quem decide, se usa ou não o ponto e virgula em seus códigos.

Outro exemplo de bloco:
```javascript
{
    {
        console.log("Hello")
        console.log("World!")
    }
}
```
Agora, temos dois blocos de código, um mais externo que contem outro bloco, e esse outro bloco interno, que contém nossas duas sentenças de código.

É importante destacar, que as chaves "{}" não alteram em nada o funcionamento desse código acima, nesse caso, foi usado só para explicação, sua função aí é só para indentação.

[Acesse o exemplo desse código](./organizacao.js)