---
title: Cor
linktitle: Cor
toc: true
type: docs
date: "2020-11-06"
draft: false
menu:
  variable:
    parent: Variáveis
    weight: 2
# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
# weight: 2
---

## Definições básicas

## Fontes adicionais de variação

## Padronização

O esquema padronizado de identificação e descrição de métodos de determinação da cor de materiais do solo utilizado no FEBR é apresentado na tabela abaixo. São considerados dois materiais de solo (matriz e manchas), dois estados de umidade (úmido e seco) e duas condições mecânicas (amassada e triturada).

| Código de identificação        | Descrição mínima sugerida |
| ------------------------------ | ------------------------- |
| `cor_matriz_umido_munsell`     | Notação da cor de material de solo [`cor`]. Determinada na matriz do solo [`matriz`]. Amostra em estado de umidade úmido [`umido`]. Expressa utilizando a notação de Munsell® (matiz valor/croma) [`munsell`]. {A DETERMINAÇÃO FOI FEITA NO CAMPO OU EM LABORATÓRIO?} |
| `cor_matriz_seco_munsell`      | Notação da cor de material de solo [`cor`]. Determinada na matriz do solo [`matriz`]. Amostra em estado de umidade seco [seco]. Expressa utilizando a notação de Munsell® (matiz valor/croma) [`munsell`]. {ESPECIFICAR SE A DETERMINAÇÃO FOI FEITA NO CAMPO OU EM LABORATÓRIO} |
| `cor_matriz_amassada_munsell`  | Notação da cor de material de solo [`cor`]. Determinada na matriz do solo [`matriz`]. Amostra em estado de umidade úmido e condição mecânica amassada [`amassada`]. Expressa utilizando a notação de Munsell® (matiz valor/croma) [`munsell`]. {ESPECIFICAR SE A DETERMINAÇÃO FOI FEITA NO CAMPO OU EM LABORATÓRIO} |
| `cor_matriz_triturada_munsell` | Notação da cor de material de solo [`cor`]. Determinada na matriz do solo [`matriz`]. Amostra em estado de umidade seco e condição mecânica triturada [`triturada`]. Expressa utilizando a notação de Munsell® (matiz valor/croma) [`munsell`]. {ESPECIFICAR SE A DETERMINAÇÃO FOI FEITA NO CAMPO OU EM LABORATÓRIO} |
| `cor_mancha_umido_munsell`     | Notação da cor de material de solo [`cor`]. Determinada na mancha do solo [`mancha`]. Amostra em estado de umidade úmido [`umido`]. Expressa utilizando a notação de Munsell® (matiz valor/croma) [`munsell`]. {ESPECIFICAR SE A DETERMINAÇÃO FOI FEITA NO CAMPO OU EM LABORATÓRIO} |

## Exemplo

A tabela a seguir apresenta um exemplo de organização tabular de dados de cor da matriz e manchas de um perfil de solo. Os dados são reais e foram obtidos da descrição morfológica de um perfil de solo classificado como Planossolo Nátrico Órtico vertissólico, localizado no município de Pacaraima, Roraima[^@OliveiraEtAl2018b]. A tabela está transposta, com as observações nas colunas e as variáveis nas linhas, para facilitar a visualização e comparação dos códigos de identificação da cores da matriz e machas do perfil de solo.

Dentre os oito horizontes, quatro possuem matriz com duas ou mais cores (Btgn, Btgnv1, Btgnv2 e 2Cgn). Nestes, as cores da matriz ocupam áreas superficiais aproximadamente similares, com distribuição espacial muito complexa, que dificulta a identificação visual de uma cor dominante com credibilidade. Trata-se do padrão multicolorido intricado conhecido como variegado.

|                              | An       | En       | EBn       | Btn       | Btgn      | Btgnv1    | Btgnv2    | 2Cgn     |
| ---------------------------- | -------- | -------- | --------- | --------- | --------- | --------- | --------- | -------- |
| `cor_matriz_umido_munsell_1` | 10YR 5/1 | 10YR 5/1 | 10YR 6/2  | 7,5YR 5/2 | 7,5YR 6/2 | 10YR 4/1  | 10YR 4/1  | 10YR 6/2 |
| `cor_matriz_umido_munsell_2` | -        | -        | -         | -         | 7,5YR 5/2 | 10YR 5/2  | 10YR 5/2  | 10YR 7/2 |
| `cor_matriz_umido_munsell_3` | -        | -        | -         | -         | -         | 10YR 6/2  | 10YR 4/2  | -        |
| `cor_matriz_umido_munsell_4` | -        | -        | -         | -         | -         | 7,5YR 5/8 | 7,5YR 5/6 | -        |
| `cor_matriz_seco_munsell`    | 10YR 6/2 | 10YR 6/1 | -         | -         | -         | -         | -         | -        |
| `cor_mancha_umido_munsell_1` | -        | -        | 7,5YR 5/8 | 7,5YR 5/8 | -         | -         | -         | 10YR 6/8 |
| `cor_mancha_umido_munsell_2` | -        | -        | -         | 7,5YR 4/1 | -         | -         | -         | -        |
| `cor_mancha_umido_munsell_3` | -        | -        | -         | 7,5YR 7/2 | -         | -         | -         | -        |

[^@OliveiraEtAl2018b]: Oliveira VÁ de, Vale Júnior JF do, Schaefer CEGR, Lumbreras JF, Coelho MR, Melo VF, Campos MCC, Corrêa GR, Calderano SB, Ker JC. Capítulo 2. Solos da XI Reunião Brasileira de Classificação e Correlação de Solos (RCC de Roraima). Guia de Campo da XI Reunião Brasileira de Classificação e Correlação de Solos: RCC de Roraima. 1. ed. Brasília, DF: EMBRAPA; 2018. p. 12-29.