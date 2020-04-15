# DISTANCIA EM METROS

1 - COLETA DE COORDENADAS: no google maps procurar todas as estações de metro (linhas amarela, vermelha, verde, azul) e trem (dentro da área das marginais)
2 - MONTAR ARQUIVO CSV: com o seguinte cabeçalho "estacao;tipo;lat;lon" onde "tipo" significa metro ou trem
3 - ESTACAO MAIS PROXIMA: encontrar a estacão mais proxima de cada localidade em metros
4 - gravar o resultado em 1 arquivo no formato parquet na formatação gzip e snappy (comparando os tempos)
