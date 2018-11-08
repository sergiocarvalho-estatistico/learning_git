# Ciclo de vida dos dos arquivos (status do git)

O git os arquivos passam por quatros estágios bem definidos.

	* Untracked   
	* Unmodified
	* modified 
	* staged

## Untracked

É o momento em que o arquivo acabou de ser adicionado no repositório, mas ainda não foi visto pelo git, ou seja, o git não reconhece em seu repositório em nenhuma versão a existência deste arquivo.

## Unmodified

Depois que um arquivo é adicionado ele passa a ser considerado como não modificado, ou seja, ele já existe no git mas ainda não sofreu modificações

## Modified

Após um arquivo ser reconhecido pelo git podemos então editá-lo e todo arquivo editado passa ao status de modificado

## Staged

Depois do arquivo ser modificado podemos colocá-lo em uma área onde será criada uma versão, a qual é chamada de staged

## Commit

Os arquivos comitados passam ao status de unmodified, pois uma vez que a versão de um arquivo foi criada e comentada nada foi alterado.   

## Teste do comando diff 


