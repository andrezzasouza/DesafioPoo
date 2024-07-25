# Desafio POO

## Modelagem e Diagramação de um Componente iPhone

```mermaid
classDiagram
    class ReprodutorMusical {
        #selecionarMusica(String musica)
        #tocar()
    }

    class AparelhoTelefonico {
        #ligar(String numero)
        #atender()
        #iniciarCorreioVoz()
    }

    class NavegadorInternet {
        #exibirPagina(String url)
        #adicionarNovaAba()
        #atualizarPagina()
    }

    class iPhone {
    }

    iPhone *--> ReprodutorMusical : 1..*
    iPhone *--> AparelhoTelefonico : 1.
    iPhone *--> NavegadorInternet : 1..*
```
