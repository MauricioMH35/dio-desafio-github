# Notas de aprendizagem
Introdução ao Git e ao GitHub

## Comentários úteis
* Git bash é um terminal extendido para otmizar o uso do git por meio de linha de comando.

## Links úteis
(Download Git)[https://git-scm.com/downloads]

## Comando úteis para git

### Puxar repositório remoto para local/Clone
Esse comando clona o repositório remoto indicado pelo endereço após o comando 'clone' para o repositório local que deve ser indicado ao terminal antes de executar a "clonagem" do repositório. 
```
    git clone "endereço_do_repositório_no_github"
```

### Visualiza os status de modificação/Status
Para visualizar o estado ou 'status' que a modificação do projeto se encontra, pode ser utilizado o comando mostrado logo abaixo que mostra de forma descritiva as informações.
```
    git status
```

### Adicionar modificação/Add
Com este comando é possivel adicionar modificações do projeto ao 'stage' para "comitar" logo após a(s) modificação(ões) realizadas.
```
    git add .
```
Apesar de se utilizar o ponto '.', que indica para adicionar todas as modificações feitais ao 'stage', é possivel adicionar arquivos especificos, e ou até partes especificas de um arquivo.

### Comentando modificação/Commit
As modificações que estão no 'stage', esperando a "confirmação" por meio do 'commit' para dar uma especie de OKEY nas modificações realizadas. Isso faz com que as modificações entrem na 'branch' atual.
```
    git commit -m "comentário simples para especificar mudanças"
```

### Enviando modificações para o repositório remoto/Push
Para enviar as modificações realizadas ao repositório remoto, será necessário a execução do comando que especifica também de qual 'branch' está sendo enviada ao repositório remoto.
```
    git push origin main
```

