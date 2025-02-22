---
title: 管理标记
intro: '您可以使用 {% data variables.product.prodname_desktop %} 创建、推送和查看标记。'
redirect_from:
  - /desktop/contributing-to-projects/managing-tags
  - /desktop/contributing-and-collaborating-using-github-desktop/managing-tags
versions:
  fpt: '*'
ms.openlocfilehash: 980e47f6e3300995f6312499b23768d6f0401f36
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 09/05/2022
ms.locfileid: '145085089'
---
## 关于 {% data variables.product.prodname_desktop %} 中的标记

{% data variables.product.prodname_desktop %} 可用于创建带注释的标记。 标记与提交相关，因此您可以使用标记在仓库的历史记录中标记单独的点，包括发行版的版本号。 有关版本标记的详细信息，请参阅“[关于版本](/github/administering-a-repository/about-releases)”。

{% data reusables.desktop.tags-push-with-commits %}

## 创建标记

{% data reusables.desktop.history-tab %} {% data reusables.desktop.create-tag %} {% data reusables.desktop.name-tag %} {% data reusables.desktop.confirm-tag %}

## 查看标记

{% data reusables.desktop.history-tab %}
2. 单击提交。
  {% note %}

  注意：如果标记未被推送至远程存储库，{% data variables.product.prodname_desktop %} 将显示箭头 {% octicon "arrow-up" aria-label="The up arrow icon" %}。

  {% endnote %}

  ![查看历史记录中的标记](/assets/images/help/desktop/viewing-tags-in-history.png)

3. 与提交相关的所有标记均在提交元数据中可见。
![查看提交中的标记](/assets/images/help/desktop/viewing-tags-in-commit.png)

## 删除标记

{% note %}

注意：你只能删除与尚未推送的提交关联的标记。

{% endnote %}

{% data reusables.desktop.history-tab %} {% data reusables.desktop.delete-tag %}

## 延伸阅读

- Git 文档中的“[Git 基础知识 - 标记](https://git-scm.com/book/en/v2/Git-Basics-Tagging)”
