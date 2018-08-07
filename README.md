# template-study-group

-- [DAQUI] --

> Template para a criação de repositórios de grupos de estudos

## Como utilizar este template

Deve existir um repositório `xxx-study-group` que foi criado pela administração do projeto grupos de estudos para que você continue o processo de criação do grupo.

Caso este repo não exista, comente em uma [issue no repositório do grupos de estudos](https://github.com/training-center/study-groups/issues).

Você deverá clonar o repositório do seu grupo de estudos para a sua máquina e em seguida clonar este projeto inteiro para dentro do repositório.

Para isso vá até o repositório xxx-study-group (onde xxx é o nome da área ou técnologia que vocês irão estudar juntos) e clique em clone. Copie o link via SSH ou HTTP conforme a sua maneira de usar Git.

![Imgur](https://i.imgur.com/HJERYKc.png)

Em seguida baixe este repositório dentro do seu com o seguinte procedimento:

1. Abre o terminal.
2. Faz um clone com `--bare`.

```bash
$ git clone --bare https://github.com/seuUsuario/old-repository.git
```
3. Espelhe o repositório.
```bash
$ cd old-repository.git
$ git push --mirror https://github.com/seuUsuario/new-repository.git
```
4. Remova o git que você clonou no primeiro passo.
```bash
$ cd ..
$ rm -rf old-repository.git
```

## Alterando a documentação do repositório

Agora basta alterar este documento para adicionar suas informações.

No título do documento (template-study-group), mude de template para o tema do grupo.

Onde estiver [xxx] em todo o repositório, mude para o tema do seu grupo. Como, por exemplo, `Repositório do grupo de estudos sobre Clojure do [Training Center](https://training-center.github.io).`

Exemplo de repositório: [clojure-study-group](https://github.com/training-center/clojure-study-group).

Com tudo alterado, basta fazer o push.

Caso você tenha qualquer dúvida sobre o processo de criação do grupo de estudos, abra uma issue em [study-group](https://github.com/training-center/study-groups).

Apague tudo o que estiver entre -- [DAQUI] -- e -- [ATÉ AQUI] --.

---

-- [ATÉ AQUI] --

Repositório do grupo de estudos sobre [xxx] do [Training Center](https://training-center.github.io).

<p align="center">
  <img src="assets/training-center-logo.svg" alt="Logo do Training Center">
</p>

## Como funciona

Este grupo se destina ao estudo de [xxx].

Conforme [outros grupos de estudos](https://github.com/training-center/study-groups) da comunidade Training Center, nós temos um [roadmap](material/roadmap.md) de tópicos para estudar juntos e fazemos reuniões semanais sobre o assunto que são gravados e disponibilizados no YouTube, no [canal do Training Center](https://www.youtube.com/c/TrainingCenterChannel).

## Como participar

Basta responder [este formulário]() para sabermos seu nível de conhecimento, entrar no [Slack do Training Center](https://github.com/training-center/slack) e entrar no canal **#[xxx]-studies**.

## Reuniões

- [pauta](/material/agenda)
- [ata](material/minutes)

## Material de apoio ao grupo de estudos

- [trilha de estudos](material/roadmap.md)
- [livros](material/dir/books.md)
- [comunidades](material/dir/communities.md)
- [cursos](material/dir/courses.md)
- [eventos](material/dir/events.md)
- [newsletters](material/dir/newsletters.md)
- [sites](material/dir/sites.md)

## Responsáveis

Caso você precise entrar em contato com as pessoas responsáveis por este grupo de estudos, pode chamar por `@xxx` no Slack do Training Center.
