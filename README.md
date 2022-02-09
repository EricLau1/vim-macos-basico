# VIM MACOS

- <a href="#open-file">Abrir um arquivo</a>
- <a href="#open-dir">Abrir um diretório</a>
- <a href="#open-vtab">Abrir uma aba vertical</a>
- <a href="#show-tree-dir">Mostrar árvore de diretório</a>
- <a href="#switch-tab">Trocar de aba</a>
- <a href="#cursor-eol">Colocar cursor no final da linha</a>
- <a href="#cursor-bol">Colocar cursor no começo da linha</a>
- <a href="#insert-i">Inserir atrás do cursor</a>
- <a href="#insert-a">Inserir na frente do cursor</a>
- <a href="#insert-o">Inserir na linha de baixo</a>
- <a href="#insert-above-line">Inserir na linha de cima</a>
- <a href="#copy-line">Copiar linha</a>
- <a href="#paste">Colar</a>
- <a href="#delete-line">Deletar linha</a>
- <a href="#delete-word">Deletar palavra</a>
- <a href="#delete-letter">Deletar letra</a>
- <a href="#eof">Ir para o final do arquivo</a>
- <a href="#gg">Ir para o começo do arquivo</a>
- <a href="#go-line">Ir para uma linha do arquivo</a>
- <a href="#undo">Desfazer uma alteração</a>
- <a href="#save">Salvar</a>
- <a href="#save-exit">Salvar e sair</a>
- <a href="#exit">Sair sem salvar</a>
- <a href="#noh">Remover highlight(destaque em textos)</a>

## Comandos Básicos

- <span id="open-file"> Abrir um arquivo </span>

```bash
vim file.txt
```

- <span id="open-dir"> Abrir um diretório </span>

```bash
vim .
```

> O vim inicia no modo normal. Para sair do modo Inserir e voltar para o Normal basta pressionar [ ESC ]

- <span id="search-text"> Procurar um texto </span>

[Modo Normal]

```bash
?qualquer texto após a interrogação + [ ENTER ]
```

- <span id="open-vtab"> Abrir uma nova aba vertical </span>

[Modo Normal]

```bash
:vsplit + [ ENTER ]
```

- <span id="show-tree-dir"> Mostrar árvore de diretório </span>

[Modo Normal]

```bash
:e . + [ ENTER ]
```

- <span id="switch-tab"> Trocar de aba </span>

[Modo Normal]

[ CTRL ] + ([ W ] * 2)

- <span id="cursor-eol"> Colocar cursor no final da linha </span>

[Modo Normal]

[ SHIFT ] + [ $ ]

- <span id="cursor-bol"> Colocar cursor no início da linha </span>

[Modo Normal]

[ SHIFT ] + [ ˆ ] + [ SPACE ]

- <span id="insert-i"> Inserir atrás do cursor </span>

[Modo Normal]

[ i ]

- <span id="insert-a"> Inserir na frente do cursor </span>

[Modo Normal]

[ a ]

- <span id="insert-o"> Inserir na linha de abaixo </span>

[Modo Normal]

[ o ]


- <span id="insert-above-line"> Inserir na linha de cima </span>

[Modo Normal]

[ SHIFT ] + [ o ]

- <span id="copy-line"> Copiar linha </span>

[Modo Normal]

[ Y ] * 2

- <span id="copy-line"> Copiar linha </span>

[Modo Normal]

[ Y ] * 2


- <span id="paste"> Colar </span>

[Modo Normal]

[ p ]

- <span id="delete-line"> Deletar linha </span>

[Modo Normal]

[ d ] * 2

- <span id="delete-word"> Deletar palavra </span>

[Modo Normal]

[ d ] [ $ ]

- <span id="delete-letter"> Deletar letra </span>

[Modo Normal]

[ x ]

- <span id="eof"> Ir para o final do arquivo </span>

[Modo Normal]

[ SHIFT ] + [ g ]

- <span id="gg"> Ir para o começo do arquivo </span>

[Modo Normal]

[ g ] * 2

- <span id="go-line"> Ir para uma linha do arquivo </span>

[Modo Normal]

```bash
:numero da linha + [ ENTER ]
```

- <span id="undo"> Desfazer uma alteração </span>

[Modo Normal]

[ u ]

- <span id="save"> Salvar </span>

[Modo Normal]

```bash
:w + [ ENTER ]
```

- <span id="save-exit"> Salvar e sair</span>

[Modo Normal]

```bash
:wq + [ ENTER ]

# variação
:x + [ ENTER ]
```

- <span id="exit"> Sair sem salvar</span>

[Modo Normal]

```bash
:!q + [ ENTER ]
```

- <span id="noh"> Remover highlight(destaque em textos)</span>

[Modo Normal]

```bash
:noh
```