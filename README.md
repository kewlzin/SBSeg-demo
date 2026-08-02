# SBSeg-demo-Ataques-de-Canais-Laterais-Eletromagn-ticos
Artefatos necessários à reprodução dos resultados do artigo curto [1], bem como de resultados não reportados no artigo por limitações de espaço. Os resultados demonstram como reproduzir ataques TEMPEST em um dispositivo gráfico HDMI ou VGA exibindo a tela de uma Urna Eletrônica Brasileira (UEB). Umva versão completa do artigo está em elaboração

[1] BRITO, Lucas; TEODORO, Leonardo; TOMAZ, Pedro; ISALUSKI, Alyson; HYEDA, Leandro; OLIVEIRA-JR, Antonio; QUEIROZ, Saulo. Ataques de Canais Laterais Eletromagnéticos Ameaçam Seções Eleitorais Eletrônicas? Cenários e Recomendações. In: SIMPÓSIO BRASILEIRO DE SEGURANÇA DA INFORMAÇÃO E DE SISTEMAS COMPUTACIONAIS (SBSeg), 2026.

Síntese dos Resultados
| Resolução | Distância do alvo (metros) | Interface de vídeo | Resultado | Obs. |
|:----------:|:--------------------------:|:------------------:|:---------:|:-----:|
|1280x768@60| 0.5 metros                 |    VGA/HDMI        |Ataque bem sucedido| Com/Sem obstáculo |
|1280x768@60|  1 metro                   |    VGA/HDMI        |Ataque bem sucedido| Com/Sem obstáculo |
|1920x1080@60| 0.5 metros                |    VGA/HDMI        |Ataque bem sucedido| Com/Sem obstáculo |
|1920x1080@60|  1 metro                  |    VGA/HDMI        |Ataque bem sucedido| Com/Sem obstáculo |


Para distâncias iguais ou superiores a dois metros, não foi poossível obter imagens legíveis no nosso cenário
---
Este experimento foi conduzido utilizando o módulo grtempest para o gnuradio, compilado em Linux Mint 20
Para instalação do ambiente, refira-se à [esse guia](https://github.com/kewlzin/SBSeg-demo-Ataques-de-Canais-Laterais-Eletromagn-ticos/blob/main/Etapas%20da%20instala%C3%A7%C3%A3o)
