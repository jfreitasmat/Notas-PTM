Notas-PTM
=========

Neste repositório encontra-se os rascunhos das notas de aula do curso de Probabilidade e Teoria da Medida.
Rode PDFLaTex no arquivo notas.tex para compilar o texto. Cada aula é adicionada em um arquivo separado
que deve ser colocado na pasta Aulas. Use a pasta de Figuras caso queira inserir alguma figura no texto
de preferência em formato PDF. 
*Exsitem problemas de compilação deste arquivo com Texlive 2011. As principais fontes de problema 
são: a fonte DejaVuSerif e o pacote imakeidx. A remoção de ambos não deve causar nenhum problema 
grave e o arquivo deve funcionar normalmente nas versões anteriores a de 2013 do Texlive.*

Abrimos mão de usar a fonte DejaVuSerif e também do pacote imakeidx.
Assim para que você obtenha o indíce remissívo no final do arquivo 
deve descomentar a linha referente ao comando printindex que se encontra
nos notas.tex e rodar o makeindex manualmente. 
