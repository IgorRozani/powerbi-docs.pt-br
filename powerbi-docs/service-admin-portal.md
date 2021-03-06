---
title: Portal de administração do Power BI
description: O portal de administração permite o gerenciamento de locatário do Power BI em sua organização. Inclui itens como métricas de uso, o acesso ao centro de administração do Office 365 e configurações.
author: mgblythe
manager: kfile
ms.reviewer: ''
ms.service: powerbi
ms.component: powerbi-admin
ms.topic: conceptual
ms.date: 06/28/2017
ms.author: mblythe
LocalizationGroup: Administration
ms.openlocfilehash: 334bffeabbf5342c21424fa5d9907eba7e71fd4e
ms.sourcegitcommit: 52ac456bf2ac025b22ea634c28482f22e1cc19ac
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 10/10/2018
ms.locfileid: "48909028"
---
# <a name="power-bi-admin-portal"></a>Portal de administração do Power BI

O portal de administração permite o gerenciamento de locatário do Power BI em sua organização. Inclui itens como métricas de uso, o acesso ao centro de administração do Office 365 e configurações.

O Gerenciamento de locatário do Power BI para sua empresa é feito por meio do portal de administração do Power BI. O portal de administração é acessível a todos os usuários que são administradores globais no Office 365 ou que receberam a função de administrador de serviços do Power BI. Para obter mais informações sobre a função de administrador de serviços do Power BI, consulte [Noções básicas sobre a função de administrador do Power BI](service-admin-role.md).

Todos os usuários verão **Portal de administração** sob o ícone de engrenagem. Se não forem administradores, eles verão apenas a seção **Configurações Premium** e somente as capacidades que têm direitos para gerenciar.

## <a name="how-to-get-to-the-admin-portal"></a>Como obter o portal de administração

Sua conta deve ser marcada como **Administrador Global** no Office 365 ou no Azure Active Directory ou ter recebido a função de administrador de serviços do Power BI, para obter acesso ao portal de administração do Power BI. Para obter mais informações sobre a função de administrador de serviços do Power BI, consulte [Noções básicas sobre a função de administrador do Power BI](service-admin-role.md). Para acessar o portal de administração do Power BI, faça o seguinte:

1. Selecione a engrenagem de configurações na parte superior direita do serviço do Power BI.
2. Selecione **Portal de Administração**.

![](media/service-admin-portal/powerbi-admin-settings.png)

No portal, há seis guias. Elas estão descritas abaixo.

* [Métricas de uso](#usage-metrics)
* [Usuários](#users)
* [Logs de auditoria](#audit-logs)
* [Configurações de locatário](#tenant-settings)
* [Configurações Premium](#premium-settings)
* [Códigos de inserção](#embed-codes)
* [Elementos visuais da organização](#Organization-visuals)

![](media/service-admin-portal/powerbi-admin-landing-page.png)

## <a name="usage-metrics"></a>Métricas de uso
A primeira guia, no portal de administração, é **Métricas de uso**. O relatório de métricas de uso permite monitorar o uso no Power BI para sua organização. Ele também fornece a capacidade de ver quais usuários e grupos são mais ativos no Power BI para sua organização.

> [!NOTE]
> Na primeira vez que acessar o dashboard ou depois de visitar novamente após um longo período de não exibição do dashboard, você provavelmente encontrará uma tela de carregamento enquanto carregamos o dashboard.

Quando o painel for carregado, você verá duas seções de blocos. A primeira seção inclui dados de uso para usuários individuais e a segunda seção tem informações semelhantes para grupos em sua organização.

Aqui está uma análise do que você verá em cada bloco:

* Contagem distinta de todos os painéis, relatórios e conjuntos de dados no espaço de trabalho do usuário
  
    ![](media/service-admin-portal/powerbi-admin-usage-metrics-number-tiles.png)

* Painel mais consumido pelo número de usuários que podem acessá-lo. Por exemplo, se você tem um painel que compartilhou com 3 usuários e também o adiciona a um pacote de conteúdo com dois usuários conectados a ele, sua contagem é 6 (1 + 3 + 2)
  
    ![](media/service-admin-portal/powerbi-admin-usage-metrics-top-dashboards.png)

* Os conteúdo mais populares aos quais os usuários estão conectados. Isso pode ser qualquer coisa que os usuários podem acessar através do processo Obter Dados, portanto, pacotes de conteúdo SaaS, pacotes de conteúdo organizacional, arquivos ou bancos de dados de conteúdo.
  
    ![](media/service-admin-portal/powerbi-admin-usage-metrics-top-connections.png)

* Uma exibição de seus principais usuários sobre quantos painéis eles têm, incluindo painéis criados por eles mesmos e painéis compartilhados com eles.
  
    ![](media/service-admin-portal/powerbi-admin-usage-metrics-top-users-dashboards.png)

* Uma exibição de seus principais usuários com base em quantos relatórios eles têm
  
    ![](media/service-admin-portal/powerbi-admin-usage-metrics-top-users-reports.png)

A segunda seção mostra o mesmo tipo de informação, mas com base em grupos. Isso permite que você veja quais grupos em sua organização são mais ativos e quais tipos de informações eles estão usando.

Com essas informações, você poderá obter informações reais de como as pessoas estão usando o Power BI em toda a organização e ser capaz de reconhecer esses usuários e grupos, que são muito ativos na sua organização.

## <a name="users"></a>Usuários

A segunda guia, no portal de administração, **Gerenciar usuários**. Gerenciamento de usuário, para o Power BI, é feito no centro de administração do Office 365, esta seção permite que você chegue rapidamente à área para gerenciar usuários, administradores e grupos no Office 365.

![](media/service-admin-portal/powerbi-admin-manage-users.png)

Quando você clicar em **Ir para o Centro de Administração do O365**, vá diretamente para a página de aterrissagem do centro de administração do Office 365 para gerenciar os usuários do seu locatário.

![](media/service-admin-portal/powerbi-admin-o365-admin-center.png)

## <a name="audit-logs"></a>Logs de auditoria

A terceira guia, no portal de administração, é **Logs de auditoria**. Os logs estão localizados no Centro de Conformidade e Segurança do Office 365. Esta seção permite acessar rapidamente essa área no Office 365.

Para obter mais informações sobre logs de auditoria, consulte [Auditoria do Power BI em sua organização](service-admin-auditing.md)

## <a name="tenant-settings"></a>Configurações de locatário

A terceira guia, no portal de administração, é **Configurações de locatário**. As configurações de locatário oferecem mais controle sobre quais recursos são disponibilizados para sua organização. Se você tiver dúvidas relacionadas a dados confidenciais, alguns dos nossos recursos poderão não ser adequados para sua organização, ou talvez você queira apenas que um determinado recurso esteja disponível para um grupo específico. Se esse for o caso, você pode desativá-lo em seu locatário.

![](media/service-admin-portal/powerbi-admin-tenant-settings.png)

> [!NOTE]
> Pode levar até 10 minutos para que a configuração entre em vigor para todos em seu locatário.

As configurações podem ter três estados:

* **Desabilitado para toda a organização**: você pode desabilitar um recurso e fazer com que os usuários não o possam usar.

    ![](media/service-admin-portal/powerbi-admin-tenant-settings-disabled.png)

* **Habilitado para toda a organização**: você pode habilitar um recurso para toda a organização, permitindo que todos os usuários tenham acesso a esse recurso.

    ![](media/service-admin-portal/powerbi-admin-tenant-settings-enabled.png)

* **Habilitado para um subconjunto da organização**: você também pode habilitar um recurso para uma parte da organização. Isso pode ocorrer de algumas formas diferentes. Você pode habilitá-lo para toda a organização, exceto para um grupo específico de usuários.

    ![](media/service-admin-portal/powerbi-admin-tenant-settings-enabled-except.png)

    Você também pode habilitar o recurso apenas para um grupo específico de usuários e também desabilitá-lo para um grupo de usuários. Isso garantiria que determinados usuários não tivessem acesso ao recurso, mesmo se estivessem no grupo permitido.

    ![](media/service-admin-portal/powerbi-admin-tenant-settings-enabled-except2.png)

As próximas seções fornecem uma visão geral dos diferentes tipos de configurações de locatário.

## <a name="workspace-settings"></a>Configurações de espaço de trabalho

### <a name="create-workspaces-preview"></a>Criar espaços de trabalho (versão prévia)
Os usuários na organização podem criar espaços de trabalho de aplicativo para colaborar em dashboards, relatórios e outros tipos de conteúdo.

Para obter mais informações, confira [Criar os novos espaços de trabalho](service-create-the-new-workspaces.md).

## <a name="export-and-sharing-settings"></a>Configurações de exportação e compartilhamento

### <a name="share-content-to-external-users"></a>Compartilhar conteúdo com usuários externos

Os usuários da organização podem compartilhar dashboards com usuários fora da organização.

![](media/service-admin-portal/powerbi-admin-sharing-external-02.png)

Esta é a mensagem que é exibida quando você compartilha com um usuário externo.

![](media/service-admin-portal/powerbi-admin-sharing-external.png)

### <a name="publish-to-web"></a>Publicar na Web

Os usuários na organização podem publicar relatórios na Web. [Saiba mais](service-publish-to-web.md)

![](media/service-admin-portal/powerbi-admin-publish-to-web.png)

Os usuários podem ver diferentes opções na interface do usuário, conforme a configuração de Publicar na Web.

|Recurso |Habilitado para toda a organização |Desabilitado para toda a organização |Especificar grupos de segurança   |
|---------|---------|---------|---------|
|**Publicar na Web** no menu **Arquivo** do relatório.|Habilitado para todos|Não visível para todos|Visível somente para usuários ou grupos autorizados.|
|**Gerenciar códigos de inserção** em **Configurações**|Habilitado para todos|Habilitado para todos|Habilitado para todos<br><br>Opção * **Excluir** somente para usuários ou grupos autorizados.<br>* **Obter códigos** habilitados para todos.|
|**Códigos de inserção** no portal de administração|O status refletirá uma das seguintes opções:<br>* Ativo<br>* Sem suporte<br>* Bloqueado|O status é exibido como **desabilitado**|O status refletirá uma das seguintes opções:<br>* Ativo<br>* Sem suporte<br>* Bloqueado<br><br>Se um usuário não estiver autorizado conforme a configuração do locatário, o status exibirá **violado**.|
|Relatórios publicados existentes|Tudo habilitado|Tudo desabilitado|Os relatórios continuam a ser renderizados para todos.|

### <a name="export-data"></a>Exportar dados

Os usuários na organização podem exportar dados de um bloco ou visualização. [Saiba mais](consumer/end-user-export-data.md)

![](media/service-admin-portal/powerbi-admin-export-data.png)

> [!NOTE]
> Desabilitar a opção **Exportar dados** também impede os usuários de usar o recurso **Analisar no Excel**, bem como de usar a conexão dinâmica do serviço do Power BI.

### <a name="export-reports-as-powerpoint-presentations"></a>Exportar relatórios como apresentações do PowerPoint

Os usuários na organização podem exportar relatórios do Power BI como arquivos do PowerPoint. [Saiba mais](consumer/end-user-powerpoint.md)

![](media/service-admin-portal/powerbi-admin-powerpoint.png)

### <a name="print-dashboards-and-reports"></a>Imprimir dashboards e relatórios

Os usuários na organização podem imprimir dashboards e relatórios. [Saiba mais](consumer/end-user-print.md)

![](media/service-admin-portal/powerbi-admin-print-dashboard.png)

![](media/service-admin-portal/powerbi-admin-print-report.png)

## <a name="content-pack-settings"></a>Configurações do pacote de conteúdo

### <a name="publish-content-packs-to-the-entire-organization"></a>Publicar pacotes de conteúdo em toda a organização

Os usuários na organização podem publicar pacotes de conteúdo em toda a organização.

![](media/service-admin-portal/powerbi-admin-publish-entire-org.png)

### <a name="create-template-organizational-content-packs"></a>Criar pacotes de conteúdos organizacionais de modelo

Os usuários na organização podem criar pacotes de conteúdo de modelo que usam conjuntos de dados criados em uma fonte de dados no Power BI Desktop.

### <a name="push-apps-to-end-users"></a>Enviar aplicativos por push para usuários finais

Seu administrador de locatário habilita a capacidade de enviar aplicativos por push em **Configurações de locatário**.

   ![Habilitar envio de aplicativos por push](media/service-create-distribute-apps/power-bi-apps-pushapps01.png)

É possível mudar a configuração para **Habilitado** e, em seguida, especificar quem obtém esse recurso (organização inteira ou grupos de segurança específicos).

> [!NOTE]
> Lembre-se de que as alterações na configuração de locatário podem levar algum tempo para entrar em vigor.

Acesse aqui para saber mais sobre [Enviar aplicativos por push](service-create-distribute-apps.md).

## <a name="integration-settings"></a>Configurações de integração

### <a name="ask-questions-about-data-using-cortana"></a>Faça perguntas sobre dados usando a Cortana

Os usuários na organização podem fazer perguntas sobre seus dados usando a Cortana.

> [!NOTE]
> Essa configuração se aplica a toda a organização e não pode ser limitada a grupos específicos.

### <a name="use-analyze-in-excel-with-on-premises-datasets"></a>Usar a opção Analisar no Excel com conjuntos de dados locais

Os usuários na organização podem usar o Excel para exibir e interagir com conjuntos de dados locais do Power BI. [Saiba mais](service-analyze-in-excel.md)

> [!NOTE]
> Desabilitar a opção **Exportar Dados** também impede os usuários de usar o recurso **Analisar no Excel**.

### <a name="use-arcgis-maps-for-power-bi"></a>Usar o ArcGIS Maps for Power BI

Os usuários na organização podem usar a visualização do ArcGIS Maps for Power BI, fornecida pela Esri. [Saiba mais](power-bi-visualization-arcgis.md)

### <a name="use-global-search-for-power-bi-preview"></a>Usar a pesquisa global para o Power BI (versão prévia)

Os usuários na organização podem usar recursos de pesquisa externos que se baseiam no Azure Search. Por exemplo, eles podem usar a Cortana para recuperar informações importantes diretamente dos relatórios e dashboards do Power BI. [Saiba mais](service-cortana-intro.md)

## <a name="custom-visuals-settings"></a>Configurações visuais personalizadas

### <a name="enable-custom-visuals-for-the-entire-organization"></a>Habilitar visuais personalizados para toda a organização

Os usuários na organização podem interagir com e compartilhar elementos visuais personalizados. [Saiba mais](power-bi-custom-visuals.md)

> [!NOTE]
> Essa configuração se aplica a toda a organização e não pode ser limitada a grupos específicos.

## <a name="r-visuals-settings"></a>Configurações de elementos visuais do R

### <a name="interact-with-and-share-r-visuals"></a>Interagir e compartilhar visuais do R

Os usuários na organização podem interagir e compartilhar elementos visuais criados com scripts do R. [Saiba mais](visuals/service-r-visuals.md)

> [!NOTE]
> Essa configuração se aplica a toda a organização e não pode ser limitada a grupos específicos.

## <a name="audit-and-usage-settings"></a>Configurações de auditoria e de uso

### <a name="create-audit-logs-for-internal-activity-auditing-and-compliance"></a>Criar logs de auditoria para conformidade e auditoria de atividade interna

Os usuários na organização podem usar a auditoria para monitorar as ações executadas no Power BI por outros usuários na organização. [Saiba mais](service-admin-auditing.md)

Essa configuração deve ser habilitada para que as entradas de log de auditoria sejam registradas. Pode haver um atraso de até 48 horas entre a habilitação da auditoria e a possibilidade de exibir dados de auditoria. Se os dados não forem exibidos imediatamente, verifique os logs de auditoria mais tarde. Pode haver um atraso semelhante entre a obtenção da permissão para exibir os logs de auditoria e a possibilidade de acessá-los.

> [!NOTE]
> Essa configuração se aplica a toda a organização e não pode ser limitada a grupos específicos.

### <a name="usage-metrics-for-content-creators"></a>Métricas de uso para criadores de conteúdo
Os usuários na organização podem ver métricas de uso para dashboards e relatórios que eles criaram. [Saiba mais](service-usage-metrics.md).

Você pode mudar a configuração para **Habilitado** e, em seguida, especificar quem pode ver as métricas de uso (organização inteira ou grupos de segurança específicos).

> [!NOTE]
> Lembre-se de que as alterações na configuração de locatário podem levar algum tempo para entrar em vigor.

### <a name="per-user-data-in-usage-metrics-for-content-creators"></a>Dados por usuário em métricas de uso para criadores de conteúdo
As métricas de uso para criadores de conteúdo expõem os nomes de exibição e os endereços de email dos usuários que estão acessando o conteúdo. [Saiba mais](service-usage-metrics.md).

Você pode mudar a configuração para **Habilitado** e, em seguida, especificar quem pode ver os nomes de exibição e os endereços de email nas métricas de uso (organização inteira ou grupos de segurança específicos).

Os dados por usuário são habilitados para as métricas de uso, por padrão, e as informações de conta do criador do conteúdo estão incluídas no relatório de métricas. Se você não quiser incluir essa informação para alguns ou todos os usuários, desabilite o recurso para grupos de segurança especificados ou para toda a organização. Em seguida, as informações da conta serão mostradas no relatório como *Sem nome*.

> [!NOTE]
> Lembre-se de que as alterações na configuração de locatário podem levar algum tempo para entrar em vigor.


## <a name="dashboard-settings"></a>Configurações do dashboard

### <a name="data-classification-for-dashboards"></a>Classificação de dados para dashboards

Os usuários na organização podem marcar dashboards com classificações indicando os níveis de segurança do dashboard. [Saiba mais](service-data-classification.md)

> [!NOTE]
> Essa configuração se aplica a toda a organização e não pode ser limitada a grupos específicos.

## <a name="developer-settings"></a>Configurações do desenvolvedor

### <a name="embed-content-in-apps"></a>Inserir conteúdo em aplicativos

Usuários da organização podem inserir relatórios e dashboards do Power BI em aplicativos de SaaS (software como serviço). Desabilitar essa configuração impede os usuários de usar as APIs REST para inserir conteúdo do Power BI em seus aplicativos.

## <a name="capacity-settings"></a>Configurações de Capacidade

### <a name="premium-settings"></a>Configurações Premium

A guia Configurações Premium permite que você gerencie qualquer capacidade do Power BI Premium (SKU Em ou P) que tenha sido comprada para sua organização. Todos os usuários na organização podem ver a guia de Configurações Premium, mas só verão conteúdo nela se forem atribuídos como **Administradores de capacidade** ou se forem um usuário com permissões de atribuição. Se um usuário não tiver nenhuma permissão, a mensagem de erro a seguir será exibida.

![Configurações de administração do Power BI Premium](media/service-admin-portal/premium-settings-no-access.png "Sem acesso às configurações Premium")

Para saber mais sobre como gerenciar as configurações Premium, confira [Gerenciar o Power BI Premium](service-admin-premium-manage.md).

### <a name="power-bi-embedded-settings"></a>Configurações do Power BI Embedded

A guia de configurações do Power BI Embedded permite que você exiba suas capacidades do Power BI Embedded (SKU A) que comprou para o cliente. Como você só pode comprar SKUs A do Azure, pode [gerenciar capacidades incorporadas no Azure](developer/azure-pbie-create-capacity.md) do **Portal do Azure**.

![Configurações de administração do Power BI Embedded](media/service-admin-portal/manage-pbie-capacities-01.png)

![Detalhes de configurações de administração do Power BI Embedded](media/service-admin-portal/manage-pbie-capacities-02.png)

Para saber mais sobre como gerenciar as configurações do Power BI Embedded (SKU A), confira [O que é o Power BI Embedded](developer/azure-pbie-what-is-power-bi-embedded.md).

## <a name="embed-codes"></a>Códigos de inserção

![Códigos de inserção dentro do portal de administração do Power BI](media/service-admin-portal/embed-codes.png)

Como administrador, você pode exibir os códigos de inserção que são gerados para seu locatário. Você possui as ações de exibir o relatório e excluir o código de inserção para revogá-lo.

## <a name="organization-visuals"></a>Visuais da organização

A guia de elementos visuais da organização permite implantar e gerenciar elementos visuais personalizados dentro da sua organização, para que você possa implantar facilmente os elementos visuais personalizados proprietários na organização, para que os autores de relatório consigam descobrir e importar esses visuais diretamente do Power BI Desktop em seus relatórios.

A página mostra todos os elementos visuais personalizados que estão implantados no momento no repositório da organização.

![Visual de administrador da organização](media/service-admin-portal/power-bi-custom-visuals-organizational-admin-01.png)

### <a name="add-a-new-custom-visual"></a>Adicionar um novo elemento visual personalizado

Para adicionar um novo elemento visual personalizado à lista, selecione **Adicionar um elemento visual personalizado**

![](media/service-admin-portal/power-bi-custom-visuals-organizational-admin-02.png)

> [!WARNING]
> Um elemento visual personalizado pode conter código com riscos de segurança ou privacidade; verifique se você confia no autor e a fonte do visual personalizado antes de implantá-lo no relatório de origem.

Preencha os campos:

* Escolha um arquivo .pbiviz (obrigatório): selecione um arquivo de elemento visual personalizado para carregar. Apenas os elementos visuais personalizados da API com controle de versão têm suporte (leia aqui o que isso significa).

Antes de carregar um elemento visual personalizado, você deve examinar tal elemento visual em relação à segurança e à privacidade, para verificar se ele se ajusta aos padrões da sua organização. Leia sobre a segurança dos elementos visuais personalizados.

* Nomeie os elementos visuais personalizados (obrigatório): dê um título curto para o elemento visual para que os usuários do Power BI Desktop compreendam facilmente o que ele faz

* Ícone (obrigatório): o arquivo de ícone que é mostrado na interface do usuário do Power BI Desktop.

* Descrição: uma breve descrição do elemento visual para fornecer mais contexto e treinamento para o usuário

Selecione "Aplicar" para iniciar a solicitação de carregamento. Se for bem-sucedido, você poderá ver o novo item na lista. Se falhar, você poderá receber uma mensagem de erro apropriada

### <a name="delete-a-custom-visual-from-the-list"></a>Exclua um visual personalizado da lista

Selecione o ícone de lixeira para excluir permanentemente o visual do repositório.
Importante: a exclusão é irreversível. Depois de excluído, o elemento visual interrompe imediatamente a renderização em relatórios existentes. Mesmo se você carregar o mesmo elemento visual novamente, ele não substituirá o anterior que foi excluído. Os usuários podem reimportar o novo elemento visual e substituir a instância que têm em seus relatórios.

### <a name="disable-a-custom-visual-in-the-list"></a>Desabilitar um visual personalizado na lista

Para desabilitar o visual do repositório organizacional, selecione o ícone de engrenagem. Na seção **Acesso**, desabilite o visual personalizado.

Depois que você desabilitar o visual, ele não será renderizado em relatórios existentes e exibirá a mensagem de erro abaixo.

*Este visual personalizado não está mais disponível. Entre em contato com o administrador para obter detalhes.*

No entanto, os elementos visuais marcados com um indicador ainda funcionam.

Após qualquer alteração de atualização ou de administrador, os usuários do Power BI Desktop devem reiniciar o aplicativo ou atualizar o navegador no serviço do Power BI para ver as atualizações.

### <a name="how-to-update-a-visual"></a>Como atualizar um elemento visual

Se você quiser atualizar um visual no repositório devido à existência de uma nova versão do visual (por exemplo, correções de bug, nova funcionalidade, etc.), selecione o ícone **Atualizar** e carregue o novo arquivo. Verifique se a ID do Visual permanece inalterada. O novo arquivo substitui o arquivo anterior em todos os relatórios de toda a organização. No entanto, se a nova versão do visual prejudicar qualquer estrutura de dados de uso da versão anterior do visual, não substitua a versão anterior. Em vez disso, crie uma nova lista para a nova versão do visual. Por exemplo, adicione um novo número de versão (versão X.X) ao título do novo visual listado. Desse modo, fica claro que é o mesmo visual, apenas com um número de versão atualizada, assim os relatórios existentes não prejudicam a funcionalidade. Novamente, verifique se a ID do Visual permanece inalterada. Assim, na próxima vez que os usuários inserirem o repositório da organização do Power BI Desktop, poderão importar a nova versão, que pedirá que substituam a versão atual que têm no relatório.

## <a name="next-steps"></a>Próximas etapas

[Noções básicas sobre a função de administrador do Power BI](service-admin-role.md)  
[Auditoria do Power BI em sua organização](service-admin-auditing.md)  
[Gerenciar o Power BI Premium](service-admin-premium-manage.md)  
[Administração do Power BI em sua organização](service-admin-administering-power-bi-in-your-organization.md)  

Mais perguntas? [Experimente perguntar à Comunidade do Power BI](http://community.powerbi.com/)
