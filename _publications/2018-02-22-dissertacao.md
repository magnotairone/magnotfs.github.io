---
title: "Extending JAGS for spatial data"
collection: publications
permalink: /publication/2018-02-22-dissertacao
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2018-02-22
venue: 'Repositório Institucional UFMG'
paperurl: 'https://repositorio.ufmg.br/bitstream/1843/BUOS-AZGNHV/1/dissertacao_magno_t_f_severino.pdf'
citation: 'Severino, Magno TF. (2018). &quot;Extending JAGS for spatial data.&quot; <i>Dissertação de Mestrado</i>.'
---

A modelagem hierarquica Bayesiana para dados espaciais pode ser bastante desaadora para prossionais de áreas para além da estatística. Do ponto de vista técnico, a parte mais simples do processo é denir o modelo e as distribuições a priori. A diculdade está no cálculo das distribuições condicionais completas a posteriori e na implementação do algoritmo amostrador de Gibbs. A família de softwares estatísticos BUGS (acrônimo para inferência Bayesiana usando o amostrador de Gibbs, em tradução literal) reduz oesforço de modelagem, uma vez que o usuário deve indicar apenas as distribuições a priori e a verossimilhança dos dados. Entretanto, em geral tais softwares não permitem análises mais complexas de dados espaciais, embora usuários do WinBUGS e do OpenBUGS podemusar o módulo espacial GeoBUGS. JAGS (apenas outro amostrador de Gibbs, em tradução literal), é uma alternativa á famlia BUGS, desenvolvida em C++ com código aberto, não contém nenhuma função ou distribuição disponível que simplique a modelagem de da dos espaciais. O objetivo fundamental deste trabalho é suprir essa falta, implementando um módulo para o software JAGS que permita aos usuários de diferentes áreas realizar modelagem e análise de dados espacias de maneira simples

[Baixe a dissertação aqui](https://repositorio.ufmg.br/bitstream/1843/BUOS-AZGNHV/1/dissertacao_magno_t_f_severino.pdf)