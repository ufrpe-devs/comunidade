# BSI Developers Group - Toda contribuição é válida :)

É sempre difícil fazer algo pela primeira vez, especialmente quando se está contribuindo, claro que é normal cometermos erros mas se você está aqui está disposto
a aprender e ceder conhecimento. Queremos trabalhar juntos para que possamos criar uma grande comunidade.

A teoria sempre ajuda, mas o que é melhor do que realmente pôr a mão na massa em um ambiente prático? Esta sessão visa direcionar aqueles que querem fazer sua primeira contribuição.

> Se não possui o git em sua máquina, [instale-o aqui]( https://help.github.com/articles/set-up-git/ ).

<img align="right" width="300" src="./src/imgs/fork.png" alt="fork deste repositório" />


## Faça um fork desse repositório

Faça um Fork clicando no botão "Fork" no topo desta página. Isto irá criar uma cópia deste repositório na sua conta.

## Clone o repositório

<img align="right" width="300" src="./src/imgs/clone.png" alt="clonar este repositório" />

Agora clone este repositório para a sua máquina. Clique no botão "Clone or download" e, em seguida, clique no ícone "Copy to clipboard" para copiar a URL.

Abra seu terminal e execute o seguinte comando do git:
```
git clone url
```
onde url é a URL deste repositório. Consulte as etapas anteriores para obter a URL.

<img align="right" width="300" src="./src/imgs/copy-to-clipboard.png" alt="copiar URL" />

Por exemplo:
```
git clone https://github.com/bsi-developers/comunidade.git
```
onde "seu-usuário" é o seu usuário do GitHub. Aqui você está copiando o conteúdo do repositório first-contributions para o seu computador.

## Crie um Branch

Ainda no git bash ou outro terminal de sua preferencia vá para o diretório do repositório no seu computador (caso você não esteja lá):
```
cd first-contributions
```

Agora crie um Branch usando o comando `git checkout`:
```
git checkout -b <add-seu-nome>
```

Por exemplo:
```
git checkout -b add-alonzo-church
```
Obs.: O nome do Branch não precisa ter a sigla "add", mas nesse caso é recomendável, porque a finalidade deste Branch é a de adicionar o seu nome a uma lista.

## Efetue as alterações necessárias e faça um Commit

Agora abra o arquivo `Contributors.md` em seu editor de código, adicione o seu nome a ele e salve o arquivo. 

<img align="right" width="450" src="./src/imgs/git-status.png" alt="git status" />

Se você for para o diretório do projeto e executar o comando `git status`, verá que há alterações. Adicione essas alterações ao Branch que você acabou de criar utilizando o comando `git add`:
```
git add Contributors.md
```
Agora faça um Commit dessas alterações utilizando o comando `git commit`:
```
git commit -m "Add <seu-nome> to Contributors list"
```
preenchendo `<seu-nome>` com o seu nome.

## Faça um Push das alterações para o GitHub

Faça um Push utilizando o comando `git push`:
```
git push origin <add-seu-nome>
```
substituindo `<add-seu-nome>` pelo nome do Branch que você criou anteriormente.

## Envie suas alterações para serem revisadas

Se você for para o seu repositório no GitHub, verá um botão `Compare & pull request`. Clique nesse botão.

<img style="float: right;" src="./src/imgs/compare-and-pull.png" alt="Crie um Pull Request" />

Agora envie um Pull Request.

<img style="float: right;" src="./src/imgs/submit-pull-request.png" alt="Envie o Pull Request" />

Logo estarei mesclando ('mergeando') as suas mudanças no Branch principal (master) deste projeto. Você receberá um e-mail de notificação quando as alterações forem mescladas.

## Para onde ir a partir daqui?

Parabéns! Você completou o fluxo de trabalho básico _fork -> clone -> edit -> PR_ que você encontrará frequentemente como contribuidor!

> *Imagens retiradas de https://github.com/firstcontributions/first-contributions/blob/master/translations/README.pt_br.md*