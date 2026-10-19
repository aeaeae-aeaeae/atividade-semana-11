# atividade-semana-11

Aluna: Ana Paula Ferreira Eler
Matrícula: 935840

## DESKTOP

<img width="1903" height="1079" alt="homepagedesktop" src="https://github.com/user-attachments/assets/0a8e2aff-7dd1-47fc-9d8e-6840b7cde0a1" />
<img width="1919" height="1079" alt="minecraftdesktop" src="https://github.com/user-attachments/assets/6cdcf97a-3ff0-4802-8bbe-3caa75347118" />
<img width="1919" height="1079" alt="stardewdesktop" src="https://github.com/user-attachments/assets/2ceb9b04-824f-4929-bd1f-c2c87f4873f8" />


## MOBILE

<img width="480" height="940" alt="homepagemobile" src="https://github.com/user-attachments/assets/03cd0f1f-4515-4d70-b697-d0ce3364e3a9" />
<img width="496" height="925" alt="minecraftmobile" src="https://github.com/user-attachments/assets/0827ce53-8644-4976-a759-b6d095ff60c7" />

## DADOS JSON

<details>
<summary>Clique aqui para visualizar os dados</summary>

```javascript
const jogos = [
    {
        "id": 1,
        "nome": "Minecraft",
        "descricao": "Um jogo de mundo aberto em que você explora, coleta recursos, constrói estruturas e enfrenta criaturas. Sua criatividade é o limite.",
        "genero": "Sandbox",
        "avaliacao": 4.5,
        "desenvolvedor": "Mojang Studios",
        "lancamento": "18/11/2011",
        "imagem": "imagens/minecraft.jpg",
        "lojas": [
            {
            "nome": "Nintendo Switch",
            "icone": "imagens/icones/nintendo.png",
            "url": "https://www.nintendo.com/us/store/products/minecraft-106679/?utm_source=mcnet_nintendo_pdp_mcov"
            },
            {
            "nome": "PlayStation",
            "icone": "imagens/icones/ps.png",
            "url": "https://store.playstation.com/pt-br/product/UP4433-PPSA17221_00-MINECRAFTPS50000"
            },
            {
            "nome": "Xbox",
            "icone": "imagens/icones/xbox.jpg",
            "url": "https://www.xbox.com/pt-BR/games/store/minecraft/9MVXMVT8ZKWC?cid=mcnet_xbox_pdp_mcov"
            },
            {
            "nome": "Minecraft",
            "icone": "imagens/icones/minenet.jpg",
            "url": "https://www.minecraft.net/pt-br/store/minecraft-deluxe-collection-pc?tabs=%7B%22details%22%3A0%7D"
            },
            {
            "nome": "Play Store",
            "icone": "imagens/icones/googleplay.jpg",
            "url": "https://play.google.com/store/apps/details?id=com.mojang.minecraftpe&utm_source=mcnet_android_pdp_mcov"
            }
        ]
    },

    {
        "id": 2,
        "nome": "Stardew Valley",
        "descricao": "Herde uma antiga fazenda e transforme-a em um novo lar. Plante, crie animais, explore cavernas, faça amizades e vire parte de uma pequena comunidade.",
        "genero": "RPG / Simulação",
        "avaliacao": 4.6,
        "desenvolvedor": "ConcernedApe",
        "lancamento": "26/02/2016",
        "imagem": "imagens/stardew.jpg",
        "lojas": [
            {
            "nome": "Nintendo Switch",
            "icone": "imagens/icones/nintendo.png",
            "url": "https://www.nintendo.com/us/store/products/stardew-valley-switch/"
            },
            {
            "nome": "PlayStation",
            "icone": "imagens/icones/ps.png",
            "url": "https://www.playstation.com/pt-br/games/stardew-valley/"
            },
            {
            "nome": "Xbox",
            "icone": "imagens/icones/xbox.jpg",
            "url": "https://www.xbox.com/pt-BR/games/store/stardew-valley/c3d891z6tnqm"
            },
            {
            "nome": "Steam",
            "icone": "imagens/icones/steam.jpg",
            "url": "https://store.steampowered.com/app/413150/Stardew_Valley/"
            },
            {
            "nome": "Play Store",
            "icone": "imagens/icones/googleplay.jpg",
            "url": "https://play.google.com/store/apps/details?id=com.chucklefish.stardewvalley&hl=pt_BR"
            }
        ]
    },

    {
        "id": 3,
        "nome": "Bendy and the Ink Machine",
        "descricao": "Um animador retorna a um antigo estúdio de desenhos e encontra um lugar tomado por mistérios. Explore cenários sombrios, resolva enigmas e sobreviva a criaturas de tinta.",
        "genero": "Terror / Puzzle",
        "avaliacao": 4.5,
        "desenvolvedor": "Joey Drew Studios Inc.",
        "lancamento": "10/02/2017",
        "imagem": "imagens/bendy.jpg",
        "lojas": [
            {
            "nome": "Nintendo Switch",
            "icone": "imagens/icones/nintendo.png",
            "url": "https://www.nintendo.com/pt-br/store/products/bendy-and-the-ink-machine-switch/"
            },
            {
            "nome": "PlayStation",
            "icone": "imagens/icones/ps.png",
            "url": "https://store.playstation.com/pt-br/product/UP2344-CUSA13637_00-MDKRTGAMES4BATIM/"
            },
            {
            "nome": "Xbox",
            "icone": "imagens/icones/xbox.jpg",
            "url": "https://www.xbox.com/pt-BR/games/store/bendy-and-the-ink-machine/btq96qtq58f3"
            },
            {
            "nome": "Steam",
            "icone": "imagens/icones/steam.jpg",
            "url": "https://store.steampowered.com/app/622650/Bendy_and_the_Ink_Machine/"
            }
        ]
    },

    {
        "id": 4,
        "nome": "Sally Face",
        "descricao": "Acompanhe Sal Fisher, um garoto que usa uma prótese facial, enquanto investiga acontecimentos estranhos no prédio onde vive. Uma aventura narrativa de mistério e terror.",
        "genero": "Terror / Aventura",
        "avaliacao": 4.7,
        "desenvolvedor": "Portable Moose",
        "lancamento": "16/08/2016",
        "imagem": "imagens/sallyface.jpg",
        "lojas": [
            {
            "nome": "Nintendo Switch",
            "icone": "imagens/icones/nintendo.png",
            "url": "https://www.nintendo.com/pt-br/store/products/sally-face-switch/"
            },
            {
            "nome": "PlayStation",
            "icone": "imagens/icones/ps.png",
            "url": "https://store.playstation.com/pt-br/product/UP7083-CUSA28680_00-9473825684854058"
            },
            {
            "nome": "Xbox",
            "icone": "imagens/icones/xbox.jpg",
            "url": "https://www.xbox.com/pt-BR/games/store/sally-face/9n1c74g2jxhm"
            },
            {
            "nome": "Steam",
            "icone": "imagens/icones/steam.jpg",
            "url": "https://store.steampowered.com/app/541570/Sally_Face__Episode_One/"
            }
        ]
    },

    {
        "id": 5,
        "nome": "Hollow Knight",
        "descricao": "Explore as ruínas de Hallownest, um reino subterrâneo repleto de insetos misteriosos. Enfrente inimigos, descubra áreas escondidas e desvende os segredos de uma civilização esquecida.",
        "genero": "Aventura",
        "avaliacao": 4.8,
        "desenvolvedor": "Team Cherry",
        "lancamento": "24/02/2017",
        "imagem": "imagens/hollowknight.jpg",
        "lojas": [
            {
            "nome": "Nintendo Switch",
            "icone": "imagens/icones/nintendo.png",
            "url": "https://www.nintendo.com/pt-br/store/products/hollow-knight-switch/"
            },
            {
            "nome": "PlayStation",
            "icone": "imagens/icones/ps.png",
            "url": "https://store.playstation.com/pt-br/product/UP1822-PPSA34970_00-HOLLOWKNIGHTPS50"
            },
            {
            "nome": "Xbox",
            "icone": "imagens/icones/xbox.jpg",
            "url": "https://www.xbox.com/pt-br/games/store/hollow-knight-edi%C3%A7%C3%A3o-cora%C3%A7%C3%A3o-vazio/9mw9469v91lm"
            },
            {
            "nome": "Steam",
            "icone": "imagens/icones/steam.jpg",
            "url": "https://store.steampowered.com/app/367520/Hollow_Knight/"
            }
        ]
    },

    {
        "id": 6,
        "nome": "Undertale",
        "descricao": "Uma criança cai em um mundo subterrâneo habitado por monstros e precisa encontrar um caminho de volta para casa. Suas escolhas importam.",
        "genero": "RPG",
        "avaliacao": 4.8,
        "desenvolvedor": "Toby Fox",
        "lancamento": "15/09/2015",
        "imagem": "imagens/Undertale.jpg",
        "lojas": [
            {
            "nome": "Nintendo Switch",
            "icone": "imagens/icones/nintendo.png",
            "url": "https://www.nintendo.com/pt-br/store/products/undertale-switch/"
            },
            {
            "nome": "PlayStation",
            "icone": "imagens/icones/ps.png",
            "url": "https://store.playstation.com/pt-br/product/UP3893-CUSA08801_00-TFSHVCUTPS400084"
            },
            {
            "nome": "Xbox",
            "icone": "imagens/icones/xbox.jpg",
            "url": "https://www.xbox.com/pt-BR/games/store/undertale/9pjggx9xjxpb"
            },
            {
            "nome": "Steam",
            "icone": "imagens/icones/steam.jpg",
            "url": "https://store.steampowered.com/app/391540/Undertale/"
            }
        ]
    },

    {
        "id": 7,
        "nome": "Cuphead",
        "descricao": "Embarque em uma aventura inspirada nos desenhos animados dos anos 1930. Controle Cuphead ou Mugman, enfrente chefes e lute para pagar uma dívida feita com o Diabo.",
        "genero": "Plataforma / Ação",
        "avaliacao": 4.7,
        "desenvolvedor": "Studio MDHR",
        "lancamento": "29/09/2017",
        "imagem": "imagens/cuphead.jpg",
        "lojas": [
            {
            "nome": "Nintendo Switch",
            "icone": "imagens/icones/nintendo.png",
            "url": "https://www.nintendo.com/pt-br/store/products/cuphead-switch/"
            },
            {
            "nome": "PlayStation",
            "icone": "imagens/icones/ps.png",
            "url": "https://store.playstation.com/pt-br/product/UP8062-CUSA20499_00-CUPHEAD000000000"
            },
            {
            "nome": "Xbox",
            "icone": "imagens/icones/xbox.jpg",
            "url": "https://www.xbox.com/pt-BR/games/store/cuphead/9njrx71m5x9p"
            },
            {
            "nome": "Steam",
            "icone": "imagens/icones/steam.jpg",
            "url": "https://store.steampowered.com/app/268910/Cuphead/"
            }
        ]
    },

    {
        "id": 8,
        "nome": "Danganronpa 2: Goodbye Despair",
        "descricao": "Um grupo de estudantes chega a uma ilha tropical que logo se transforma em palco de um jogo mortal. Investigue assassinatos, reúna pistas e enfrente julgamentos para descobrir a verdade.",
        "genero": "Visual Novel / Detetive",
        "avaliacao": 4.7,
        "desenvolvedor": "Spike Chunsoft",
        "lancamento": "26/07/2012",
        "imagem": "imagens/danganronpa2.jpg",
        "lojas": [
            {
            "nome": "Nintendo Switch",
            "icone": "imagens/icones/nintendo.png",
            "url": "https://www.nintendo.com/pt-br/store/products/danganronpa-2-goodbye-despair-anniversary-edition-switch/"
            },
            {
            "nome": "PlayStation",
            "icone": "imagens/icones/ps.png",
            "url": "https://store.playstation.com/pt-br/product/UP1063-CUSA06808_00-DANGANRONPARLDUS"
            },
            {
            "nome": "Xbox",
            "icone": "imagens/icones/xbox.jpg",
            "url": "https://www.xbox.com/pt-BR/games/store/danganronpa-2-goodbye-despair-anniversary-edition/9n27nm3bt3ml"
            },
            {
            "nome": "Steam",
            "icone": "imagens/icones/steam.jpg",
            "url": "https://store.steampowered.com/app/413420/Danganronpa_2_Goodbye_Despair/"
            },
            {
            "nome": "Play Store",
            "icone": "imagens/icones/googleplay.jpg",
            "url": "https://play.google.com/store/apps/details?id=jp.co.spike_chunsoft.DR2"
            }
        ]
    }
]
```
</details>


