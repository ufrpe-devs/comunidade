# Guia de Contribuição

> Baseado no Guia de primeiras contribuições do [firstcontributions/first-contributions](https://github.com/firstcontributions/first-contributions)

É difícil. É sempre difícil fazer algo pela primeira vez. Especialmente quando se está colaborando, cometer erros não é algo agradável. Mas *open source* (código aberto) se trata de colaboração e de trabalharmos juntos. Queremos simplificar a forma com que novos colaboradores *open source* aprendem e contribuem pela primeira vez.

Ler artigos e ver tutoriais pode ajudar, mas o que é melhor do que realmente pôr a mão na massa em um ambiente prático? Este projeto visa guiar e simplificar a forma com que os novatos fazem a sua primeira contribuição. Se quiser fazer a sua primeira contribuição, siga os passos abaixo.

**_Se você não se sente confortável com linha de comando, [aqui estão alguns tutoriais de ferramentas gráficas.](#Tutoriais-usando-outras-ferramentas)_**

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork deste repositório" />

Se não possui o git em sua máquina, [instale-o aqui](https://help.github.com/articles/set-up-git/).

## Faça um Fork deste repositório

Faça um Fork clicando no botão "Fork" no topo da página principal do repositório. Isto irá criar uma cópia deste repositório na sua conta.

## Clone o repositório

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clonar este repositório" />

Agora clone este repositório para a sua máquina. Clique no botão "Clone or download" e, em seguida, clique no ícone "Copy to clipboard" para copiar a URL.

Abra seu terminal e execute o seguinte comando do git:

```git
git clone "url que copiou"
```

onde "url que copiou" (sem as aspas) é a URL deste repositório. Consulte as etapas anteriores para obter a URL.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copiar URL" />

Por exemplo:

```git
git clone https://github.com/ufrpe-devs/comunidade.git
```

Aqui você está copiando o conteúdo do repositório **ufrpe-devs/comunidade** para o seu computador.

## Crie um Branch

Vá para o diretório do repositório no seu computador (caso você não esteja lá):

```bash
cd comunidade
```

Agora crie um Branch usando o comando `git checkout`:

```git
git checkout -b <nome da sua branch>
```

Por exemplo:

```git
git checkout -b add/steffano-pereira
```

Obs.: O nome do Branch não precisa ter a sigla "add", mas nesse caso é recomendável, porque a finalidade deste Branch é a de adicionar o seu nome à nossa lista de contribuidores.

## Efetue as alterações necessárias e faça um Commit

Agora abra o arquivo `Contributors.md` em seu editor de código, adicione o seu nome a ele e salve o arquivo.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

Se você for para o diretório do projeto e executar o comando `git status`, verá que há alterações. Adicione essas alterações ao Branch que você acabou de criar utilizando o comando `git add`:

```git
git add Contributors.md
```

Agora faça um Commit dessas alterações utilizando o comando `git commit`:

```git
git commit -m "Add <seu-nome> to Contributors list"
```

preenchendo `<seu-nome>` com o seu nome.

## Faça um Push das alterações para o GitHub

Faça um Push utilizando o comando `git push`:

```git
git push origin <add-seu-nome>
```

substituindo `<add-seu-nome>` pelo nome da Branch que você criou anteriormente.

## Envie suas alterações para serem revisadas

Se você for para o seu repositório no GitHub, verá um botão `Compare & pull request`. Clique nesse botão.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="Crie um Pull Request" />

Agora envie um Pull Request.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="Envie o Pull Request" />

Logo estarei mesclando ('mergeando') as suas mudanças no Branch principal (main) deste projeto. Você receberá um e-mail de notificação quando as alterações forem mescladas.

## Para onde ir a partir daqui?

Parabéns! Você completou o fluxo de trabalho básico _fork -> clone -> edit -> PR_ que você encontrará frequentemente como contribuidor!

Celebre sua contribuição e compartilhe com seus amigos!

Você também pode se juntar à nossa equipe no Discord caso precise de alguma ajuda ou tenha alguma dúvida. [Junte-se à nossa equipe no Discord!](https://discord.com/invite/xeEaKKG).

Agora você pode colaborar com outros projetos. Nós temos uma lista de projetos, inclusive com problemas simples, basta procurar a tag `good first issue` que você pode começar. Verifique [a lista de projetos no GitHub](https://github.com/orgs/ufrpe-devs/repositories).

### [Material adicional](https://github.com/firstcontributions/first-contributions/blob/41d31fc572cf921c8a48e067e3ce1414ba4c1de6/additional-material/translations/additional-material.pt_br.md)

## Tutoriais usando outras ferramentas

|<a href="../github-desktop-tutorial.md"><img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"></a>|<a href="../github-windows-vs2017-tutorial.md"><img alt="Visual Studio 2017" src="https://upload.wikimedia.org/wikipedia/commons/2/2d/Visual_Studio_Code_1.18_icon.svg" width="100"></a>|<a href="../gitkraken-tutorial.md"><img alt="GitKraken" src="https://firstcontributions.github.io/assets/Readme/gk-icon.png" width="100"></a>| <a href="github-windows-intellij-tutorial.md"><img alt="IntelliJ IDEA" src="https://upload.wikimedia.org/wikipedia/commons/9/9c/IntelliJ_IDEA_Icon.svg" width=100></a> |
|:---:|:---:|:---:|:---:|
|[GitHub Desktop](https://github.com/firstcontributions/first-contributions/blob/41d31fc572cf921c8a48e067e3ce1414ba4c1de6/gui-tool-tutorials/github-desktop-tutorial-ptBR.md)|[[EN] Visual Studio Code](https://github.com/firstcontributions/first-contributions/blob/41d31fc572cf921c8a48e067e3ce1414ba4c1de6/gui-tool-tutorials/github-windows-vs-code-tutorial.md)|[[EN] GitKraken](https://github.com/firstcontributions/first-contributions/blob/41d31fc572cf921c8a48e067e3ce1414ba4c1de6/gui-tool-tutorials/gitkraken-tutorial.md)|[IntelliJ IDEA](https://github.com/firstcontributions/first-contributions/blob/41d31fc572cf921c8a48e067e3ce1414ba4c1de6/gui-tool-tutorials/translations/github-windows-intellij-tutorial.pt_br.md)         |
