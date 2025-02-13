# Comandos Batch
![Comandos](https://tm.ibxk.com.br/2017/07/28/28181329421599.jpg?ims=1200x675)
## O que é?
 É uma forma de programação de computador que permite *automatizar tarefas repetitivas* no sistema operacional Windows. Ou seja, com ele, é possível criar scripts que executam uma série de comandos em sequência, sem a necessidade de interação manual do usuário.
 
## Como funciona?
 Funciona interpretando comandos contidos em arquivos **.bat** pelo interpretador de comandos do Windows. Quando o arquivo é executado, o interpretador processa cada linha e executa os comandos correspondentes. Esses comandos são semelhantes aos usados no *prompt de comando do Windows* e permitem realizar tarefas como **criar pastas, copiar arquivos, executar programas e configurar variáveis de ambiente.**

![Comandos](https://blog.betrybe.com/wp-content/uploads/2021/06/comandos-bat.jpg)
## Lista de Comandos;

### ECHO:
O comando *echo* é utilizado para **exibir** mensagens ou valores no terminal ou na tela durante a execução de um script. Ele também pode ser usado para **criar arquivos e diretórios, testar e depurar scripts e comandos, formatar e exibir mensagens e gerar saída para outros comandos ou programas.**

#### Exemplo;
Você pode redirecionar a saída do comando echo para um arquivo usando o operador **“>”.** Quando você usa esse operador junto com o comando *echo*, ele **cria um arquivo novo** (caso o arquivo não exista) ou **sobrescreve** o conteúdo de um arquivo já existente.
```markdown
echo "Hello, World!" > hello.txt
```
#### Outro exemplo;
```markdown
echo [mensagem] >> arquivo.txt (Adiciona uma mensagem a um arquivo existente.)
```
O operador **">>"** é utilizado para adicionar a saída de um comando ao final de um arquivo, **sem sobrescrevê-lo.** Ou seja, ele *preserva* o conteúdo anterior do arquivo e apenas adiciona a nova mensagem ao final.



### CLS:
O comando *cls* é utilizado para **limpar** a tela do prompt do Windows.
#### Exemplo:
```markdown
C:\>CLS <enter>
```


### MOVE;
O comando *move* é utilizado para **movimentar um arquivo** de uma pasta a outra. Na prática, ele funciona como o comando *recortar e colar*, pois ele copia para a pasta de destino e exclui da pasta original.
#### Exemplo;
```markdown
move C:\Arquivos\documento.txt C:\Backup\
```
O arquivo *documento.txt* que está localizado em C:\Arquivos\ será **movido** para a pasta C:\Backup\.
Após a execução do comando, o arquivo será **removido** da pasta Arquivos e estará **disponível** apenas em Backup.

### DEL:
O comando *"del"* é utilizado para **excluir arquivos**. Você pode especificar o nome do arquivo a ser excluído, como "del 
arquivo.txt".

#### Exemplo;
```markdown
del [caminho]\nome_do_arquivo
```



### MKDIR;
Com o comando *"mkdir"* (Make Directory), você pode criar um **novo diretório.**

Exemplo: 
```markdown
"mkdir C:\NovaPasta" criará uma nova pasta chamada "NovaPasta" no disco C.

```
### CD;
 É usado para **navegar** entre diretórios no sistema de arquivos
#### Exemplo:
 
```markdown
"cd C:\Pasta" leva você para a pasta chamada "Pasta" localizada no disco C. 
Você também pode usar ".." para retornar um nível acima no diretório atual
```
### DIR;
É usado para **listar o conteúdo** de um diretório. Se o caminho não for especificado, o comando listará o conteúdo do diretório atual. 
#### Exemplo:
```markdown
dir C:\Arquivos
```
Neste exemplo, ele listará o conteúdo da pasta **Arquivos** no diretório C:\.

### TYPE;
O comando é usado para **exibir** o conteúdo de arquivos de texto diretamente no prompt de comando. 
Por exemplo, você pode usar "type arquivo.txt" para exibir o conteúdo do arquivo de texto chamado "arquivo.txt".

```markdown
C:\>TYPE C:\windows\directx.txt
C:\>TYPE C:\texto.txt
```
### RMDIR;
É usado para remover diretórios vazios. O qual deve estar vazio antes de ser excluído.
#### Exemplo:
```markdown
rmdir [nome_do_diretorio]
```


##### Remover um diretório e seu conteúdo (usando a opção /s): 
Se o diretório contiver arquivos ou subpastas, você pode usar a opção /s para excluir o diretório e todo o seu conteúdo.

```markdown
rmdir /s pasta_com_conteudo
```

### RENAME
O comando *rename* **renomeia** o arquivo ou o diretório.
#### Exemplo: 
```markdown
rename [caminho]\nome_antigo nome_novo
```

**[caminho]**: O diretório onde o arquivo está localizado (opcional, pode ser deixado de fora se o arquivo estiver no diretório atual).

**nome_antigo**: O nome atual do arquivo ou pasta.

**nome_novo:** O novo nome desejado para o arquivo ou pasta.
