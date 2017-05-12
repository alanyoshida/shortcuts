# BASH
## Lista numero de linhas
wc -l

## Recorta 90 caracteres do começo da linha
cut -c90-

## Substituicao com regex
sed -e "s/^SeuTexto/Substituicao/g"

## Pega duas linhas antes do grep desejado
grep -B2

## Pega segunda coluna com separador espaço vazio
cut -d' ' -f2

## Remove ultima linha
head -n -1

## Remove primeira linha ( output starts at line 2)
tail -n +2

## Redireciona saida para arquivo
ls -l > filename
## Redireciona saida para arquivo mas mostra na tela
ls -l  | tee filename

## Redirect standard error to standard output
2>&1

## Para cada resposta do find execute o grep
find . -name '*.java' | xargs grep 'billing-info'
