One of the main advantages of free and open-source projects is the possibility of working together with people outside the core development team. However, this repository in its current state (1) is difficult to be found (2) hasn't many resources to outsiders to join our community and make contributions.

## Issue #1: Tainacan's visibility on GitHub needs to be improved

### Discoverability
A person looking for Tainacan on GitHub will stumble upon [medialab-ufg/tainacan](https://github.com/medialab-ufg/tainacan) first and [tainacan/tainacan](https://github.com/tainacan/tainacan) next. Such ranking is caused by the difference in stats between those two ([medialab-ufg/tainacan](https://github.com/medialab-ufg/tainacan) has more stars and forks, but less people watching the repository when compared to [tainacan/tainacan](https://github.com/tainacan/tainacan)). While [tainacan/tainacan](https://github.com/tainacan/tainacan) explicitly states this is the development repo, [medialab-ufg/tainacan](https://github.com/medialab-ufg/tainacan) has no mention of such dynamic—which may confuse newcomers.

Both repositories also don't have any attributed topics to make them easier to discover by people looking for projects using a particular technology. Take [tootsuite/mastodon](https://github.com/tootsuite/mastodon) as an example: it lists topics such as ```gnu-social```, ```microblog``` and ```activitypub``` and it is well ranked in them. We could list ```wordpress```, ```wordpress-plugin``` and ```wordpress-theme``` among the topics of interest in our repositories to insert Tainacan in a well-known ecosystem on GitHub and make it more visible for those interested.

#### Questions
- Keeping [medialab-ufg/tainacan](https://github.com/medialab-ufg/tainacan) as the home of a stable version of Tainacan is being considered a long-term strategy or could this change in the future?

#### Good references
- [GitHub's own documentation on topics](https://help.github.com/articles/about-topics/). "Helpful topics to classify a repository include the repository's intended purpose, subject area, community, or language."

#### Improvements to be done
- List topics of interest related to all of Tainacan's repositories: [tainacan/tainacan-theme](https://github.com/tainacan/tainacan-theme), [tainacan/tainacan](https://github.com/tainacan/tainacan), [tainacan/wiki-theme](https://github.com/tainacan/wiki-theme), [tainacan/tainacan-icons](https://github.com/tainacan/tainacan-icons), [tainacan/tainacan-docker](https://github.com/tainacan/tainacan-docker) and [tainacan/tainacan-extra-views-mode](https://github.com/tainacan/tainacan-extra-viewmodes).
- As [tainacan/tainacan](https://github.com/tainacan/tainacan) is considered to be the main repository, its README should include links to all other repositories along with a short description about the role which one has in this project. Their README files should also include a link to repositories directly related to them. If [medialab-ufg/tainacan](https://github.com/medialab-ufg/tainacan) continues to host the most stable version of Tainacan, it should be mentioned on [tainacan/tainacan](https://github.com/tainacan/tainacan) and [medialab-ufg/tainacan](https://github.com/medialab-ufg/tainacan) must mention [tainacan/tainacan](https://github.com/tainacan/tainacan) as the development repository.

## Issue #2: The project should be appropriately presented on the README file

#### Improvements to be done
- Our README should contain:
  + A brief description of what is Tainacan. **Example:** Tainacan is a WordPress plug-in designed to build, manage and publish digital repositories of any kind. It is especially developed to accommodate the needs of, but not limited to, cultural institutions such as galleries, libraries, archives and museums (also known as GLAMs).
  + A statement about the team that is developing Tainacan. **Example:** Current development efforts are leaded by a team of developers at the Laboratory of Public Policies (L3P), currently based at the Laboratory of Interactive Media (MediaLab) of the Federal University of Goiás (UFG). This team is composed of `$NAME` (`$GITHUBUSERNAME`), `$ATTRIBUTION`; `$NAME` (`$GITHUBUSERNAME`), `$ATTRIBUTION`; `$NAME` (`$GITHUBUSERNAME`), `$ATTRIBUTION`; etc.
  + Present Tainacan's contribution and participation guidelines (which includes the adoption of a Code of Conduct).
  + Explictly mention community forums and other means of contact with the Tainacan community.

## Issue #3: Contribution standards and procedures aren't explicitly stated on the repository
Expansion of point #3 from issue #2.

Every project that expects contributions from people outside the core development should provide them a guide on which code standards are followed, how this project is organized and how to contact current developers to claim an issue or discuss proposed solutions. The development team started this with a document on [key concepts](https://github.com/tainacan/tainacan/blob/develop/docs/key-concepts.md) and another on [setting up an envinroment locally, along with orienting the reader on how to run tests](https://github.com/tainacan/tainacan/blob/develop/docs/setup-local.md). Those efforts should be resumed.

***

Uma das maiores vantagens de projetos de software livre é a possibilidade de trabalhar junto a pessoas que não pertencem à equipe central de desenvolvimento. Entretanto, este repositório em seu estado atual (1) é difícil de ser encontrado (2) não contém muitos recursos para pessoas de fora se juntarem à nossa comunidade e fazer contribuições.

## Issue #1: A visibilidade do Tainacan no GitHub precisa ser aprimorada

### Descoberta
Uma pessoa procurando pelo Tainacan no GitHub vai encontrar [medialab-ufg/tainacan](https://github.com/medialab-ufg/tainacan) primeiro e [tainacan/tainacan](https://github.com/tainacan/tainacan) depois. Tal classificação é ocasionada pela diferenças de estatísticas entre os dois ([medialab-ufg/tainacan](https://github.com/medialab-ufg/tainacan) possui mais estrelas e forks, mas menos pessoas observando o repositório que [tainacan/tainacan](https://github.com/tainacan/tainacan)). Enquanto [tainacan/tainacan](https://github.com/tainacan/tainacan) explicitamente diz que é um repositório voltado ao desenvolvimento, [medialab-ufg/tainacan](https://github.com/medialab-ufg/tainacan) não menciona tal dinâmica—o que pode confundir iniciantes.

Ambos repositórios também não possuem tópicos atribuídos para fazê-los mais fáceis de se encontrar por pessoas à procura de projetos usando alguma tecnologia em particular. Usemos [tootsuite/mastodon](https://github.com/tootsuite/mastodon) como exemplo: ele lista tópicos como ```gnu-social```, ```microblog``` e ```activitypub``` e é bem classificado neles. Poderíamos listar  ```wordpress```, ```wordpress-plugin``` e ```wordpress-theme``` entre os tópicos de interesse de nossos repositórios para inserir o Tainacan em um ecossistema conhecido no GitHub e torná-lo mais visível para aqueles interessados.

#### Perguntas
- Manter o [medialab-ufg/tainacan](https://github.com/medialab-ufg/tainacan) como lar da versão mais estável é considerada uma estratégia de longo prazo ou isso pode mudar no futuro?

#### Boas referências
- [A documentação do GitHub sobre tópicos](https://help.github.com/articles/about-topics/). "Tópicos úteis para classificar um repositório incluem o propósito dele, tema, comunidade ou linguagem."

#### Melhoramentos a serem feitos
- Listar os tópicos de interesse relacionados a todos os repositórios do Tainacan: [tainacan/tainacan-theme](https://github.com/tainacan/tainacan-theme), [tainacan/tainacan](https://github.com/tainacan/tainacan), [tainacan/wiki-theme](https://github.com/tainacan/wiki-theme), [tainacan/tainacan-icons](https://github.com/tainacan/tainacan-icons), [tainacan/tainacan-docker](https://github.com/tainacan/tainacan-docker) e [tainacan/tainacan-extra-views-mode](https://github.com/tainacan/tainacan-extra-viewmodes).
- Como o [tainacan/tainacan](https://github.com/tainacan/tainacan) é considerado o repositório principal, o seu README deve incluir menções a todos os outros repositórios junto a uma curta descrição de seus papéis neste projeto. Seus arquivos de README também devem mencionar repositórios diretamente relacionados. Se o [medialab-ufg/tainacan](https://github.com/medialab-ufg/tainacan) continuar a hospedar a versão mais estável do Tainacan, [tainacan/tainacan](https://github.com/tainacan/tainacan) deve conter menções a ele e o [medialab-ufg/tainacan](https://github.com/medialab-ufg/tainacan) deve mencionar [tainacan/tainacan](https://github.com/tainacan/tainacan) como o repositório de desenvolvimento.
