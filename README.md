# locale-pt-BR

Este repositório contém os arquivos em Português (Brasil) para o _State de JS/CSS/_ etc. São pesquisas que servem como base para traduzir todos os outros idiomas. Você pode visualizar uma lista de [todas as localidades aqui](https://github.com/stateofjs/?q=locale-&type=&language=&sort=).

![State of JS pt-BR translation](https://state-of-js-translation-status.vercel.app/api?locale=pt-BR)

## Como ajudar

#### 1. Tornando-se um tradutor

Para começar a ajudar a traduzir a pesquisa, você deve [entrar no Discord](https://discord.com/invite/zrdb35jfrt) e me mandar uma mensagem privada (`SachaG`) com seu nome de usuário do github, junto com o código de localidade (`pt-BR`).

Em seguida, vou lhe dar direitos de mantenedor em um repositório contendo todos os arquivos `yaml` de tradução, e a partir de agora você pode gerenciá-lo junto com outros membros da equipe de tradução.

#### 2. Encontrando coisas para traduzir

Para encontrar arquivos ainda não traduzidos você pode navegar pelos resultados de pesquisa do site ou usar o aplicativo de levantamento e encontrar _strings_ não traduzidas. Você também pode usar nossa _API_ para obter dados extras, como a porcentagem de conclusão para uma localidade ou uma lista de todas as _strings_ não traduzidas:

- https://graphiql.stateofjs.com/

Aqui está um exemplo de consulta: 

```graphql
query GetLocaleData {
  locale(localeId: "ru-RU") {
    completion
    totalCount
    translatedCount
    translators
    untranslatedKeys
  }
}
```

#### 3. Recebendo os créditos

Todo tradutor será creditado em qualquer site que faça uso das traduções, começando com o aplicativo de levantamento. Embora isso eventualmente seja automatizado através da _API_ do _GitHub_, por enquanto você pode adicionar seu nome aqui:

- https://github.com/StateOfJS/Monorepo/blob/main/api-internal/src/data/locales.yml

#### 4. Empurrando suas mudanças ao vivo

Atualmente, não há nenhum _hook_ automatizado para atualizar os aplicativos de produção quando uma tradução é atualizada, portanto, por enquanto a melhor maneira é me enviar mensagem no _Discord_ para me avisar quando terminar.

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

## Juntando-se às equipes de tradução

É recomendável que você participe da [equipe de tradução](https://github.com/orgs/stateofjs/teams/translators/teams) para o idioma que deseja traduzir.

## Desenvolvimento Local

Atualmente não há maneira fácil de ver suas _strings_ em andamento durante o desenvolvimento local. Estamos trabalhando nisso.

## Conseguindo ajuda

Entre no [nosso _Discord_](https://discord.gg/2GYXsG5BxK).
