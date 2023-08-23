# locale-pt-BR

Este repositório contém os arquivos traduzidos em Português (Brasil) relacionados aos projetos _**State of JavaScript**_ e _**State of CSS**_, que são pesquisas de levantamento sobre essas tecnologias. Essa tradução é baseada (e ligeiramente adaptada) no repositóorio [locale-en-US](https://github.com/Devographics/locale-en-US). Você pode visualizar a lista de [todas as traduções aqui](https://github.com/orgs/Devographics/repositories?q=locale&type=all&language=&sort=).

## Como ajudar

#### 1. Tornando-se um tradutor

Para começar a ajudar a traduzir a pesquisa, você deve [entrar no Discord](https://discord.gg/662RhNRGsA) e mandar uma mensagem privada para o (`SachaG`) com seu nome de usuário do github, junto com o código de localidade (`pt-BR`).

Em seguida, vou lhe dar direitos de mantenedor em um repositório contendo todos os arquivos `yaml` de tradução, e a partir de agora você pode gerenciá-lo junto com outros membros da equipe de tradução.

#### 2. Encontrando coisas para traduzir

Para encontrar arquivos ainda não traduzidos você pode navegar pelos resultados de pesquisa do site ou usar o aplicativo de levantamento e encontrar _strings_ não traduzidas.

Você também pode acessar nosso [Projeto de Tradução](https://github.com/Devographics/locale-pt-BR/projects/1) e escolher alguma _issue_ em aberto. Por favor, siga esse fluxo e não faça _commits_ diretos na _main_. Opte sempre por abrir uma requisição (PR) quando outros contribuintes estiverem ativos. Caso seu PR não seja analisado no prazo de 10 dias, pode revisar e aceitar seu próprio PR.

#### 3. Recebendo os créditos

Todo tradutor será creditado em qualquer site que faça uso das traduções, começando com o aplicativo de levantamento. Embora isso eventualmente seja automatizado através da _API_ do _GitHub_, por enquanto você pode adicionar seu nome aqui:

- https://github.com/StateOfJS/Monorepo/blob/main/api-internal/src/data/locales.yml

#### 4. Enviando suas mudanças para produção

Atualmente, não há nenhum _hook_ automatizado para atualizar os aplicativos de produção quando uma tradução é atualizada, portanto, por enquanto a melhor maneira é enviar mensagem no _Discord_ para o `SachaG` e avisá-lo quando terminar.

## Arquivos de tradução

#### Aplicativo de levantamento

Essas _strings_ estão relacionadas ao aplicativo que você usa para preencher a pesquisa atual.

- `surveys.yml`
- `accounts.yml`
- `state_of_js_2020_survey.yml`

#### Aplicativo de resultados

Essas _strings_ aparecem apenas no site estático que exibe os resultados e as estatísticas da pesquisa.

- `results.yml`
- `state_of_css_2020.yml`
- `state_of_js_2020.yml`

#### Ambos

Essas _strings_ aparecem em ambos.

- `common.yml`
- `state_of_css.yml`
- `state_of_js.yml`

#### Outros

- `homepage.yml`

## Junte-se à equipe de tradução

É recomendável que você participe da nossa [equipe de tradução](https://github.com/orgs/Devographics/teams/pt-br).

## Desenvolvimento Local

Atualmente não há maneira fácil de ver suas _strings_ em andamento durante o desenvolvimento local. Estamos trabalhando nisso.

## Para receber ajuda

Entre no nosso [**_Discord_**](https://discord.gg/662RhNRGsA).
