<h1 align="center"> Anotações Python </h1>

## Menu

- [Strings](#strings)

<br>


### Características do python
- Linguagem versátil;
- Tipagem dinâmica e forte;
- Toda variável é um objeto.

### Modo interativo
- chamando interpretador python: escrever python no terminal+enter, para sair desse modo escrever exit()+enter;
- executar o script com a flag -i(python -i nomedoarquivo.py).

### função dir() e help(), usados no modo interativo
- dir(): retorna uma lista de atributos válidos para o objeto, ex: dir(100) traz todos os métodos q tem dentro da classe int.
- help(): mostra os métodos q da pra utilizar na classe, um google, informação da implementação.

### Boas práticas
- O padrão de nomes deve ser snake case (usar _ como espaço, exemplo: preco_total);
- nome de constantes todo em maiúsculo.

<br>

| Tipos | |
|-------|-|
|numérico| int, float, complex |
| sequência | list, tuple, range |
| mapa | dict |
| coleção | set, frozenset |
| booleano | bool(true, false) |
| binário | byter, bytearray, memoryview |

# Declaração de variáveis e constantes

```python
   
    AMOUNT = 30.2
    nome = 'Maria'
    idade = 50
    peso = 50.5
    print(nome, idade, peso)
    #Maria 50 50.5

    numero = input('Digite o primeiro número: ')
    numero = int(numero) # convertendo para um número inteiro

    print(f"meu nome é {nome} e eu tenho {idade} anos de idade")

```

# Strings
```python
    print('Olá',6)
    #Olá 6
    print('8'+'9')
    #89
```
