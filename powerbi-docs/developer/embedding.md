---
title: Inserção com o Power BI
description: O Power BI oferece APIs para inserir seus dashboards e relatórios em aplicativos.
author: markingmyname
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.component: powerbi-developer
ms.topic: conceptual
ms.date: 06/22/2018
ms.author: maghan
ms.openlocfilehash: 82a4c9c58567f5ace943363b7bed59fa744e85a5
ms.sourcegitcommit: 2a7bbb1fa24a49d2278a90cb0c4be543d7267bda
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/26/2018
ms.locfileid: "36944090"
---
# <a name="embedding-with-power-bi"></a>Inserção com o Power BI
O Power BI oferece APIs para inserir seus dashboards e relatórios em aplicativos. As APIs do Power BI oferecem um conjunto consistente de funcionalidades e acesso aos recursos mais recentes do Power BI, tais como painéis, gateways e espaços de trabalho de aplicativo, ao inserir conteúdo.

## <a name="a-single-api"></a>Uma única API
Há dois cenários principais ao inserir conteúdo do Power BI.  Inserir para usuários em sua organização (que têm a licença para o Power BI) e inserir para seus usuários e clientes sem que estes precisem ter licenças do Power BI. A API REST do Power BI permite os dois cenários. 

Para clientes e usuários sem licenças do Power BI, você pode inserir painéis e relatórios em seu aplicativo personalizado, usando a mesma API para atender a organização ou os clientes. Os clientes veem os dados que são gerenciados pelo aplicativo. E para usuários do Power BI em sua organização, eles possuem as opções adicionais para exibir *seus próprios dados* diretamente no Power BI ou no contexto do aplicativo inserido. Você pode se beneficiar das APIs REST e do JavaScript para suas necessidades de inserção.

Para exibir uma amostra de como a inserção funciona, consulte a [amostra de inserção do JavaScript](https://microsoft.github.io/PowerBI-JavaScript/demo/).

## <a name="embedding-for-your-organization"></a>Inserção para a organização
A inserção para a organização permite que você estenda o serviço do Power BI. Isso exige que os usuários do seu aplicativo façam logon no serviço do Power BI quando desejarem exibir os seus respectivos conteúdos. Depois que alguém na organização conectar-se, este usuário só terá acesso aos painéis e relatórios dos quais ele é proprietário ou que foram compartilhados com ele no serviço do Power BI. 

*Exemplos de inserção para a organização incluem o aplicativo Web interno, a Web Part do SharePoint Online e a [integração do Microsoft Teams (você tem direitos de administrador)](https://powerbi.microsoft.com/en-us/blog/power-bi-teams-up-with-microsoft-teams/).*

Para inserir para a organização, consulte o seguinte:

* [Integrar um relatório em um aplicativo](integrate-report.md)
* [Integrar um painel em um aplicativo](integrate-dashboard.md)
* [Integrar um bloco em um aplicativo](integrate-tile.md)

Recursos de autoatendimento, como editar, salvar e muito mais, estão disponíveis por meio de [API JavaScript](https://github.com/Microsoft/PowerBI-JavaScript) ao inserir para usuários do Power BI.

Você pode examinar a [Ferramenta de experiência de integração para inserção para a organização](https://aka.ms/embedsetup/UserOwnsData) para iniciar rapidamente e baixar um aplicativo de exemplo que explica como integrar um relatório para a organização.

## <a name="embedding-for-your-customers"></a>Inserção para os clientes
A inserção para os clientes fornece a capacidade de inserir os painéis e relatórios para usuários que não possuem uma conta do Power BI. Os clientes não precisam saber nada sobre o Power BI. Pelo menos uma conta do Power BI Pro é necessária para criar um aplicativo inserido. Essa conta do Power BI Pro atua como uma conta mestre do seu aplicativo. Pense nisso como uma conta de proxy. A conta do Power BI Pro também permite a geração de tokens de inserção que fornecem acesso a painéis e relatórios no serviço do Power BI que são de propriedade/gerenciados pelo seu aplicativo. 

*Um exemplo de inserção para os clientes é um aplicativo de ISV sendo vendido para outras empresas.*

![Fluxo de inserção ao inserir para os clientes](media/embedding/powerbi-embed-flow.png)

Para inserir dashboards, relatórios e blocos, você usaria as mesmas APIs que usaria para inserir para a organização.

> [!IMPORTANT]
> Embora a inserção seja dependente do serviço do Power BI, não há uma dependência do Power BI para os clientes. Eles não precisa inscrever-se no Power BI para exibir o conteúdo inserido em seu aplicativo.
> 

Quando você estiver pronto para passar para a produção, seu espaço de trabalho do aplicativo deverá ser atribuído a uma capacidade. O Power BI Embedded, no Microsoft Azure, oferece a capacidade para usar com seus aplicativos.

Para obter detalhes sobre como inserir, consulte [Como inserir seus dashboards, relatórios e blocos do Power BI](embedding-content.md).

Você pode examinar a [Ferramenta de experiência de integração para inserção para clientes](https://aka.ms/embedsetup/AppOwnsData) para iniciar rapidamente e baixar um aplicativo de exemplo que explica como integrar um relatório no aplicativo.

Se você estiver usando o serviço de Coleção de Espaços de Trabalho do Power BI no Azure, consulte [Migrar o conteúdo do serviço de Coleção de Espaços de Trabalho do Power BI do Azure](migrate-from-powerbi-embedded.md) para obter informações sobre como migrar o conteúdo.

## <a name="next-steps"></a>Próximas etapas
[Como inserir seus dashboards, relatórios e blocos do Power BI](embedding-content.md)  
[Como migrar o conteúdo da coleção do espaço de trabalho do Power BI Embedded para o Power BI](migrate-from-powerbi-embedded.md)  
[Power BI Premium – o que é?](../service-premium.md)  
[Repositório Git de API do JavaScript](https://github.com/Microsoft/PowerBI-JavaScript)  
[Repositório Git de C# do Power BI](https://github.com/Microsoft/PowerBI-CSharp)  
[Exemplo inserido do JavaScript](https://microsoft.github.io/PowerBI-JavaScript/demo/)  
[White paper de planejamento de capacidade de análise inserida](https://aka.ms/pbiewhitepaper)  
[White paper do Power BI Premium](https://aka.ms/pbipremiumwhitepaper)  

Mais perguntas? [Experimente perguntar à Comunidade do Power BI](http://community.powerbi.com/)

