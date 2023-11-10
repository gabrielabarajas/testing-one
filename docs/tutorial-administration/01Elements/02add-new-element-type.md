---
sidebar_position: 2
---

# Add a new Element Type

This guide will help you add a new **Element Type**.

## **Prerequisites**
1.	**User ID** and **Password** to access APXGIS programme.
2.	**Admin Role** assigned to the User ID.

------------

**Version**: 00
**Date**: October-2023

------------
## **Step by Step**

1\. Navigate to [https://app.apx-gis.net/#/](https://app.apx-gis.net/#/)


2\. Click "**Administration**" menu.

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-02.png)

3\. Click "**Element types**" option.

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-03.png)

4\. Click "**Add**" button.

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-04.png)

5\. Click "**Name**" text field and type the name of the new element. This name will be asigned internally in the data base.

For this example "**Test-element**" was typed.

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-05.png)

6\. Click "**Type**" dropdown.

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-06.png)

**Tip**: APXGIS recognises three types of elements:

- **Node** \-element serving as a connector of two links, usually represented by a square object.
- **Link** \- element that is represented by a line, usually  represents cables and overlying elements such as subducts and ducts.
- **Polygon** \- can contain within itself nodes and links.


7\. Select the type of element for the new one. For this example "**Link**" was selected .

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-07.png)

8\. Click "**Title**" text field and type a title for the element. This title is the identifier under which the element will appear in **APX-GIS**. 

When you want to add such an element to a project, the title will allow you to identify the new element.

For this example, it was typed "**Test-element**".

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-08.png)

9\. Click "**Descriptive Icon**" to select an icon for the new element.

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-09.png)

10\. **APXGIS** will show the icons avalible. To upload more icons, go trough the menu **Administration &gt;Icons&gt;+Choose**

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-10.png)

11\. Click the icon that suits better the new element. For this example the first icon was selected.

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-11.png)

12\. Click "**Map options**" dropdown.


![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-12.png)

13\. Click "**Show in map**" option. This setting will allow the icon to be displayed on the map. If not selected, the new element will not be visible.

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-13.png)

14\. Assign a Style to "**default**" Theme by:

**(1)** clicking under "**Style**" field and writing the style's name, for this example "**canalization-new**".

**(2)** -Click "**the pencil**" and a new window will open.

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-14.png)

**Important**: Depending on the Type of element:

**Node** - it is possible to asign an icon to be shown on the default Theme.
**Link** - no icon could be assign, but rathe a color and a thikness.

15\. Configure the style of the new element by filling in the following fields.

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-15.png)

16\. Click "**Apply**" button.

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-16.png)

17\. The name of the style will be dispalyed under style tag.

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-17.png)

18\. Click "**Add/Edit**" dropdown.

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-18.png)

19\. Click all the options available:

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-19.png)
- **"from menu".** This option will allow the new element to be added by following the menu: **Operations &gt; New "new-element"**
- **"from map"**. This option will allow the new element to be added by by right cliking on the map.
- **"Display type in map selector"**  option to show or not show the element in the top right menu, in the "Types" drop-down menu. .
- "**Display in popup**" option allows right-clicking on the map to display the element. .

20\. Click "**Apply**" button.

![](/img/MNG-LMT-CRE-01/MNG-LMT-CRE-01-STP-20.png)


21\. **APXGIS**  will update the tables in the database. It will display a message, cick "**Close**" button.


**Outcome**: Element type created.

