---
ms.openlocfilehash: 307a695e8a973c7b37a29ebbeb4606a8ed43d38d
ms.sourcegitcommit: fb047f9450b41b24afc43d9512a5db2a2b750a2a
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/11/2022
ms.locfileid: "145117811"
---
Если вы включаете уведомления о сообщениях электронной почты или веб-уведомления для {% data variables.product.prodname_actions %}, вы получите уведомление при завершении выполнения любого рабочего процесса, который был активирован. Уведомление будет содержать сведения о состоянии выполнения рабочего процесса (включая успешные, неудачные, нейтральные и отмененные выполнения). Вы также можете выбрать вариант, чтобы получать уведомление только в том случае, если выполнение рабочего процесса завершилось сбоем. Дополнительные сведения о включении или отключении уведомлений см. в статье [Сведения об уведомлениях](/account-and-profile/managing-subscriptions-and-notifications-on-github/setting-up-notifications/about-notifications).

Уведомления о запланированных рабочих процессах отправляются пользователю, который изначально создал рабочий процесс. Если другой пользователь обновляет синтаксис cron в файле рабочего процесса, последующие уведомления будут отправляться этому пользователю.{% ifversion fpt or ghes or ghec %} Если запланированный рабочий процесс был отключен, а затем включен снова, уведомления будут отправляться пользователю, который повторно включил рабочий процесс, а не пользователю, который в последний раз изменил синтаксис cron.{% endif %}

Состояние выполнения рабочего процесса также отображается на вкладке "Действия" репозитория. Дополнительные сведения см. в статье [Управление выполнением рабочего процесса](/actions/automating-your-workflow-with-github-actions/managing-a-workflow-run).