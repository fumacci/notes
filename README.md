## Anotações

Esse repositório é dedicado ao armazenamento de anotações de matérias do meu curso de Engenharia Elétrica feitas em ``LaTeX``. Isso inclui tanto o source em ``.tex`` das páginas como também os arquivos já compilados em ``.pdf`` para rápido acesso em ambientes que não dispõe dos pacotes ``texlive-*``.

#### Organização

As pastas foram nomeadas de forma simplificada para serem acessíveis sem muito esforço para digitar

- ``mat/`` refere-se à matemática
- ``chm/`` refere-se à química 
- ``fis/`` refere-se à física

Dentro delas, há um arquivo principal chamado ``preamble.tex``, onde este inclui as configurações gerais da matéria, com os pacotes que mais utilizo durante a escrita das anotações, abaixo uma representação do esquema de pastas.

```
├── chm
├── fis
└── mat
    ├── calc1
    │   ├── content
    │   │   └── limites.tex
    │   ├── main.pdf
    │   ├── main.tex
    └── preamble.tex
```

Dentro das pastas de matéria, há o arquivo ``main.tex``, responsável por agregar todas as configurações (incluíndo o ``preamble.tex``). A pasta ``content/`` e ``content/images/`` incluem o conteúdo geral do arquivo ``main.tex``. Todas as pastas de assunto contém o ``main.pdf`` armazenado para rápida consulta
