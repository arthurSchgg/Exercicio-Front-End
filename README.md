# Portal do Curso – Técnico em Informática para Internet (MI81)

Site estático em HTML puro, desenvolvido como atividade prática da disciplina, com objetivo de apresentar o curso, professores e Unidades Curriculares (UCs) a futuros alunos.

## Estrutura do projeto

```
EX1/
│ index.html                  → Página inicial
│
├── paginas/
│     curso.html               → Sobre o Curso
│     professores.html         → Lista de professores
│     ucs.html                 → Lista de Unidades Curriculares
│
├── professores/
│     carlos.html
│     igor.html
│     lucas.html
│     valentim.html
│
├── Ucs/
│     arquitetura-de-redes.html
│     arquitetura-de-sistemas.html
│     automacao.html
│     banco-de-dados.html
│     industria-4.0.html
│     prototipacao.html
│     servico-de-redes.html
│
└── imagens/
      carlos.png, valentim.png, lucas.png, download.png, 1715885979432.png
```

**Total atual: 15 páginas HTML.**

## Navegação implementada

```
index.html
   ├─→ paginas/curso.html
   ├─→ paginas/professores.html
   │       ├─→ professores/carlos.html
   │       ├─→ professores/igor.html
   │       ├─→ professores/lucas.html
   │       └─→ professores/valentim.html
   └─→ paginas/ucs.html
           ├─→ Ucs/arquitetura-de-redes.html
           ├─→ Ucs/arquitetura-de-sistemas.html
           ├─→ Ucs/automacao.html
           ├─→ Ucs/banco-de-dados.html
           ├─→ Ucs/industria-4.0.html
           ├─→ Ucs/prototipacao.html
           └─→ Ucs/servico-de-redes.html
```

Cada página interna possui link de volta (`index.html` / página pai).
