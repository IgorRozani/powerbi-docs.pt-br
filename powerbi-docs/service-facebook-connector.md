---
title: 'Serviço terceirizados: conector do Facebook para o Power BI Desktop'
description: 'Serviço terceirizados: conector do Facebook para o Power BI Desktop'
author: davidiseminger
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.component: powerbi-desktop
ms.topic: conceptual
ms.date: 07/27/2018
ms.author: davidi
LocalizationGroup: Connect to data
ms.openlocfilehash: 48009ea065909c75d4629f9c669d1bfa6d88646d
ms.sourcegitcommit: f01a88e583889bd77b712f11da4a379c88a22b76
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 07/27/2018
ms.locfileid: "39330433"
---
# <a name="facebook-connector-for-power-bi-desktop"></a>Conector do Facebook para Power BI Desktop
O conector do Facebook no **Power BI Desktop** depende da API do Graph do Facebook. Como tal, recursos e disponibilidade podem variar ao longo do tempo.

Você pode ver um [tutorial sobre o Conector do Facebook para o Power BI Desktop](desktop-tutorial-facebook-analytics.md).

Em 30 de abril<sup>de</sup> 2015, o Facebook expirou a v1.0 de sua Graph API. O Power BI usa a Graph API nos bastidores para o conector do Facebook, permitindo que você se conecte aos seus dados e os analise.

Consultas que foram criadas antes de 30 de maio<sup> </sup>de 2015 podem não funcionar ou retornar menos dados. Após 30 de abril<sup> </sup>de 2015, o Power BI usa a v2.8 em todas as chamadas para a API do Facebook. Se a consulta foi criada antes de 30 de abril de 2015 e você não a usou, provavelmente precisará autenticar novamente para aprovar o novo conjunto de permissões que solicitaremos.

Podemos tentar lançar atualizações de acordo com as alterações, o API pode ser alterado de forma que afeta os resultados das consultas que gerarmos. Em alguns casos, determinadas consultas podem não ter mais suporte. Devido a essa dependência não podemos garantir os resultados de suas consultas ao usar esse conector.

Mais detalhes sobre a alteração na API do Facebook estão disponíveis [aqui](https://developers.facebook.com/docs/apps/changelog#v2_0).

