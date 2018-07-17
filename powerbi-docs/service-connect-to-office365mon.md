---
title: Conectar-se ao Office365Mon com o Power BI
description: Office365Mon para o Power BI
author: SarinaJoan
manager: kfile
ms.reviewer: maggiesMSFT
ms.service: powerbi
ms.component: powerbi-service
ms.topic: conceptual
ms.date: 10/16/2017
ms.author: sarinas
LocalizationGroup: Connect to services
ms.openlocfilehash: 16c8aba0d33fe9464aa55bfd55564babe282876c
ms.sourcegitcommit: e8d924ca25e060f2e1bc753e8e762b88066a0344
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 06/29/2018
ms.locfileid: "37135733"
---
# <a name="connect-to-office365mon-with-power-bi"></a>Conectar-se ao Office365Mon com o Power BI
Analisar seus dados de desempenho de integridade e interrupções do Office 365 é fácil com o Power BI e o pacote de conteúdo Office365Mon. O Power BI recupera seus dados, incluindo investigações de integridade e interrupções e, em seguida, compila um painel e relatórios prontos para uso com base em tais dados.

Conectar-se ao [pacote de conteúdo Office365Mon](https://app.powerbi.com/groups/me/getdata/services/office365mon) para Power BI.

>[!NOTE]
>Uma conta de administrador do Office365Mon é necessária para conectar e carregar o pacote de conteúdo do Power BI.

## <a name="how-to-connect"></a>Como se conectar
1. Selecione **Obter Dados** na parte inferior do painel de navegação esquerdo.
   
   ![](media/service-connect-to-office365mon/pbi_getdata.png)
2. Na caixa **Serviços** , selecione **Obter**.
   
   ![](media/service-connect-to-office365mon/pbi_getservices.png) 
3. Selecione **Office365Mon** \> **Obter**.
   
   ![](media/service-connect-to-office365mon/o365mon.png)
4. Para o Método de Autenticação, selecione **oAuth2** \> **Entrar**.
   
   Quando solicitado, insira suas credenciais de administrador do Office365Mon e siga o processo de autenticação.
   
   ![](media/service-connect-to-office365mon/creds.png)
   
   ![](media/service-connect-to-office365mon/creds2.png)
5. Após o Power BI importar os dados, você verá novos elementos (painel, relatório e conjunto de dados) no painel de navegação esquerdo. Novos itens são marcados com um asterisco amarelo \*; selecione a entrada do Office365Mon.
   
   ![](media/service-connect-to-office365mon/dashboard4.png)

**E agora?**

* Tente [fazer uma pergunta na caixa de P e R](power-bi-q-and-a.md) na parte superior do dashboard
* [Altere os blocos](service-dashboard-edit-tile.md) no dashboard.
* [Selecione um bloco](service-dashboard-tiles.md) para abrir o relatório subjacente.
* Enquanto seu conjunto de dados será agendado para ser atualizado diariamente, você pode alterar o agendamento de atualização ou tentar atualizá-lo sob demanda usando **Atualizar Agora**

## <a name="troubleshooting"></a>Solução de problemas
Se você receber um erro **"falha no logon"** depois de usar suas credenciais de assinatura do Office365Mon para fazer logon, a conta sendo usada não tem permissões para recuperar os dados do Office365Mon de sua conta. Verifique se que ela é uma conta de administrador e tente novamente.

## <a name="next-steps"></a>Próximas etapas
[O que é o Power BI?](power-bi-overview.md)

[Obter dados para o Power BI](service-get-data.md)

