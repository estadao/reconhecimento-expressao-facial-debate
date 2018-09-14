# O que revela uma análise dos emoções dos candidatos durante o debate

Esse repositório contém o código que gerou [esta matéria](http://www.estadao.com.br/infograficos/politica,o-que-revela-uma-analise-dos-emocoes-dos-candidatos-durante-o-debate,923037).

Ele usa a [API de reconhecimento facial da Microsoft](https://azure.microsoft.com/pt-br/services/cognitive-services/face/) para analisar as emoções demonstradas pelos candidatos presentes no debate presidencial do dia 9 de setembro de 2018.

O programa está na pasta `code` e o output na pasta `data`.

Não fizemos upload dos vídeos, das imagens e dos arquivos .JSON individuais que geraram o material, mas o código deve funcionar com qualquer arquivo de vídeo que esteja nos paths adequados. Isso foi feito porque o GitHub não permite fazer upload de arquivos tão grandes. O resultado da análise, já concatenado, está disponível.

O arquivo `1-coleta-de-dados` mostra como foram feitas as requisições para a API.

O arquivo `2-agregacoes` salva os dados no formato necessário para gerar as visualizações de dados do material.