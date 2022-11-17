---
title: Настройка GitHub Copilot в интегрированной среде разработки JetBrains
intro: 'Вы можете включить, настроить и отключить {% data variables.product.prodname_copilot %} в интегрированной среде разработки JetBrains.'
product: '{% data reusables.gated-features.copilot %}'
topics:
  - Copilot
versions:
  feature: copilot
shortTitle: JetBrains
ms.openlocfilehash: 845f9306f519391f165dd00d3eefebed67bd409a
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/05/2022
ms.locfileid: '147080670'
---
## Сведения о{% data variables.product.prodname_copilot %} в интегрированной среде разработки JetBrains

Если вы используете интегрированную среду разработки Jetbrains, {% data variables.product.prodname_copilot %} может автоматически завершать код по мере ввода. После установки можно включить или отключить {% data variables.product.prodname_copilot %}, а также настроить дополнительные параметры в интегрированной среде разработки или на {% data variables.product.prodname_dotcom_the_website %}.

## Предварительные требования

Чтобы настроить {% data variables.product.prodname_copilot %} в интегрированной среде разработки JetBrains, установите подключаемый модуль {% data variables.product.prodname_copilot %}. Дополнительные сведения см. в статье [Начало работы с {% data variables.product.prodname_copilot %} в интегрированной среде разработки JetBrains](/copilot/getting-started-with-github-copilot/getting-started-with-github-copilot-in-a-jetbrains-ide).

## Сочетания клавиш для {% data variables.product.prodname_copilot %}

Сочетания клавиш по умолчанию можно использовать для встроенных предложений в интегрированной среде разработки JetBrains при использовании {% data variables.product.prodname_copilot %}. Кроме того, можно повторно указать предпочитаемые сочетания клавиш для каждой конкретной команды. Дополнительные сведения о повторной привязке сочетаний клавиш в интегрированной среде разработки JetBrains см. в документации по JetBrains. Например, можно просмотреть документацию по [IntelliJ IDEA](https://www.jetbrains.com/help/idea/mastering-keyboard-shortcuts.html#choose-keymap).

{% mac %}

| Действие | Сочетание клавиш |
|:---|:---|
|Принять встроенное предложение|<kbd>Вкладка</kbd>|
|Отклонить встроенное предложение|<kbd>ESC</kbd>|
|Показать следующее встроенное предложение|<kbd>Option (⌥) или ALT</kbd>+<kbd>]</kbd>|
|Показать предыдущее встроенное предложение|<kbd>Option (⌥) или ALT</kbd>+<kbd>[</kbd>|
|Активировать встроенное предложение|<kbd>Option (⌥)</kbd>+<kbd>\</kbd>|
|Открыть {% data variables.product.prodname_copilot %} (additional suggestions in separate pane)|<kbd>Option (⌥) или ALT</kbd>+<kbd>Return</kbd> |

{% endmac %}

{% windows %}

| Действие | Сочетание клавиш |
|:---|:---|
|Принять встроенное предложение|<kbd>Вкладка</kbd>|
|Отклонить встроенное предложение|<kbd>ESC</kbd>|
|Показать следующее встроенное предложение|<kbd>ALT</kbd>+<kbd>]</kbd>|
|Показать предыдущее встроенное предложение|<kbd>ALT</kbd>+<kbd>[</kbd>|
|Активировать встроенное предложение|<kbd>ALT</kbd>+<kbd>\</kbd>|
|Открыть {% data variables.product.prodname_copilot %} (additional suggestions in separate pane)|<kbd>ALT</kbd>+<kbd>ВВОД</kbd> |

{% endwindows %}

{% linux %}

| Действие | Сочетание клавиш |
|:---|:---|
|Принять встроенное предложение|<kbd>Вкладка</kbd>|
|Отклонить встроенное предложение|<kbd>ESC</kbd>|
|Показать следующее встроенное предложение|<kbd>ALT</kbd>+<kbd>]</kbd>|
|Показать предыдущее встроенное предложение|<kbd>ALT</kbd>+<kbd>[</kbd>|
|Активировать встроенное предложение|<kbd>ALT</kbd>+<kbd>\</kbd>|
|Открыть {% data variables.product.prodname_copilot %} (additional suggestions in separate pane)|<kbd>ALT</kbd>+<kbd>ВВОД</kbd> |

{% endlinux %}

## Включение или отключение {% data variables.product.prodname_copilot %}

Вы можете включить или отключить {% data variables.product.prodname_copilot %} в интегрированной среде разработки JetBrains. Значок состояния {% data variables.product.prodname_copilot %} на нижней панели окна JetBrains указывает, включен или отключен параметр {% data variables.product.prodname_copilot %}. Если этот параметр включен, значок выделен. Если он отключен, значок неактивен.

1. Чтобы включить или отключить {% data variables.product.prodname_copilot %}, щелкните значок состояния на нижней панели окна JetBrains.
   ![Значок состояния в JetBrains](/assets/images/help/copilot/status-icon-jetbrains.png)
2. Если вы отключаете {% data variables.product.prodname_copilot %}, появится запрос, следует ли отключить их глобально или для языка файла, который вы редактируете. Для глобального отключения нажмите кнопку **Отключить завершения**. Или щелкните кнопку для конкретного языка, чтобы отключить {% data variables.product.prodname_copilot %} только для него.
   ![Отключить {% data variables.product.prodname_copilot %} глобально или для текущего языка](/assets/images/help/copilot/disable-copilot-global-or-langugage-jetbrains.png)

## Настройка дополнительных параметров для {% data variables.product.prodname_copilot %}

Вы можете управлять расширенными параметрами для {% data variables.product.prodname_copilot %} в интегрированной среде разработки JetBrains, например, как в интегрированной среде разработки отображается завершения кода и какие языки вы хотите включить или отключить для {% data variables.product.prodname_copilot %}.

1. В интегрированной среде разработки JetBrains откройте меню **Файл** и выберите пункт **Параметры**.
1. В разделе **Языки и платформы** щелкните **{% data variables.product.prodname_copilot %}** .
1. Измените параметры в соответствии с вашими предпочтениями.
   - Чтобы настроить поведение и внешний вид предложений по коду и указать, следует ли автоматически проверять наличие обновлений, поставьте или снимите соответствующие флажки.
   - Если вы решили получать автоматические обновления, вы можете выбрать, следует ли получать стабильные обновления, но редко, или каждую ночь, но менее стабильные. Щелкните раскрывающийся список **Канал обновления** и выберите **Стабильные** или **Каждую ночь**.
   - В разделе "Отключенные языки" установите флажки для выбора или отмены выбора языков, для которых требуется отключить {% data variables.product.prodname_copilot %}.

{% data reusables.copilot.dotcom-settings %}