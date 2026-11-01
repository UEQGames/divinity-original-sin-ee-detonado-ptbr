# Divinity: Original Sin — Enhanced Edition | Detonado Interativo PT-BR

Detonado interativo em português para **Divinity: Original Sin — Enhanced Edition**, desenvolvido como um único arquivo HTML que funciona localmente no navegador e também pode ser publicado como site estático pelo GitHub Pages.

O projeto foi pensado para acompanhar uma campanha completa de forma prática, com navegação por etapas, objetivos, progresso, mapas contextuais, builds, conquistas, quests e ferramentas de acompanhamento.

## Principais recursos

- Detonado completo organizado em etapas e objetivos.
- **Modo Rota** para acompanhar somente a sequência prática do walkthrough.
- Progresso da campanha salvo no navegador.
- Botão para continuar de onde parou.
- Exportação e importação do save do detonado em JSON.
- Busca global dentro do guia.
- Acompanhamento de conquistas, quests, eventos, segredos e progressões longas.
- Configuração de grupo e builds.
- Mapas contextuais integrados.
- Interface responsiva para desktop e dispositivos móveis.
- Funcionamento offline depois de baixar o HTML.

## Usar online

Este repositório pode ser publicado diretamente pelo **GitHub Pages**.

Depois de ativar o Pages para a branch `main`, o arquivo `index.html` passa a funcionar como página inicial do detonado.

## Usar offline

Baixe a versão mais recente em **Releases** e abra:

```text
DETONADO_DOS1_EE_FINAL.html
```

em um navegador moderno.

Não é necessário instalar nenhum programa.

## Salvamento do progresso

O progresso é mantido pelo navegador.

O detonado também possui:

- **Exportar save**
- **Importar save**

Isso permite criar uma cópia manual do progresso em formato JSON e restaurá-la depois.

> Como o armazenamento local pertence ao navegador, limpar os dados do site/navegador pode apagar o progresso local. Use a exportação de save se quiser manter uma cópia de segurança.

## Compatibilidade

Projeto focado em:

**Divinity: Original Sin — Enhanced Edition**

O conteúdo foi estruturado especificamente para a Enhanced Edition e não deve ser tratado como um guia da versão Classic.

## Estrutura do projeto

O projeto é propositalmente simples:

```text
index.html
README.md
CHANGELOG.md
LICENSE_NOTICE.md
.nojekyll
```

Todo o aplicativo, estilos, conteúdo e lógica ficam incorporados no `index.html`.

## Integridade do release

Arquivo original distribuído:

```text
DETONADO_DOS1_EE_FINAL.html
```

Tamanho:

```text
6611684 bytes
```

SHA-256:

```text
3c005ec4dc8176bcaf31b4b08c7540a8186a03ca1dc9180ea94ecc4a2b3a0f1d
```

## Contribuições e correções

Se encontrar:

- rota incorreta;
- informação incompatível com a Enhanced Edition;
- erro de navegação;
- conquista com condição errada;
- mapa incorreto;
- problema visual ou funcional;

abra uma **Issue** descrevendo a etapa e o problema encontrado.

## Aviso

Este é um projeto de fã, não oficial.

**Divinity: Original Sin**, seus personagens, nomes, marcas e demais elementos pertencem aos respectivos detentores de direitos.

O projeto não distribui o jogo.
