---
ms.openlocfilehash: 3557e85680e20919fbe049cfe30ccacc93d9c17c
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 09/05/2022
ms.locfileid: "145096146"
---
{% note %}

**Observação:** os detalhes do cartão de projeto já são mostrados nas respostas da API REST para eventos da linha do tempo e problemas relacionados ao projeto. Esse recurso agora está disponível para pré-visualização dos desenvolvedores. Para obter detalhes, confira esta [postagem no blog](https://developer.github.com/changes/2018-09-05-project-card-events).

Para receber o atributo `project_card`, os quadros de projetos precisam ser [habilitados](/articles/disabling-project-boards-in-a-repository) para um repositório, e você precisa fornecer um [tipo de mídia](/rest/overview/media-types) personalizado no cabeçalho `Accept`:

```
application/vnd.github.starfox-preview+json
```

{% endnote %}
