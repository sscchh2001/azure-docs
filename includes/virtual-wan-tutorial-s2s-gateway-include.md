---
 title: include file
 description: include file
 services: virtual-wan
 author: cherylmc
 ms.service: virtual-wan
 ms.topic: include
 ms.date: 06/23/2021
 ms.author: cherylmc
 ms.custom: include file
---
1. On the **Create virtual hub** page, click **Site to site** to open the **Site to site** tab.

   :::image type="content" source="./media/virtual-wan-tutorial-hub-include/site-to-site.png" alt-text="Screenshot shows the Create virtual hub pane with Site to site selected." border="false":::

1. On the **Site to site** tab, complete the following fields:

   * Select **Yes** to create a Site-to-site VPN.
   * The AS Number field cannot be edited.
   * Select the **Gateway scale units** value from the dropdown. The scale unit lets you pick the aggregate throughput of the VPN gateway being created in the virtual hub to connect sites to. If you pick 1 scale unit = 500 Mbps, it implies that two instances for redundancy will be created, each having a maximum throughput of 500 Mbps. For example, if you had five branches, each doing 10 Mbps at the branch, you will need an aggregate of 50 Mbps at the head end. Planning for aggregate capacity of the Azure VPN gateway should be done after assessing the capacity needed to support the number of branches to the hub.
1. Select **Review + Create** to validate.
1. Select **Create** to create the hub. Creating a VPN gateway may take up to 30 minutes. After 30 minutes, **Refresh** to view the hub on the **Hubs** page. Select **Go to resource** to navigate to the resource.