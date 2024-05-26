# DIO_POO_iPhone

# Desafio POO iPhone

---
title: iPhone
---

classDiagram
    class ReprodutorMusical {
    +tocar()
    +pausar()
    +selecionarMusica(String nome)
    }
    
    class AparelhoTelefonico {
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }
    
    class NavegadorInternet {
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina
    }
    
    class iPhone {
    }
    
    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
