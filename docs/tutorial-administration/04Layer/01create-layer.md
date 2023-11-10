---
sidebar_position: 2
---

# Create Layer

This guide will help you **create a layer** in the programme.

## **Prerequisites**
1.	**User ID** and **Password** to access APXGIS programme.
2.	Assigned **Admin Role** to the given user ID.


------------

**Version**: 00
**Date**: October-2023

------------
## **Step by Step**


1\. Click "**Administration**" dropdown menu.

![](/img/MNG-LAY-CRE-01/MNG-LAY-CRE-01-STP01.png)


2\. Click "**Admin Layers**" option.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/7ee70da1-5c6e-4ffb-a470-d38a0936f7ee/ascreenshot.jpeg?tl_px=0,34&br_px=825,495&force_format=png&width=826&wat_scale=73&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=88,204)


3\. Click "**Add**" button.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/1b851f68-77ad-48f6-a9e3-292b2751af37/ascreenshot.jpeg?tl_px=0,0&br_px=1361,590&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=191,424)


4\. Click "**Name**" text field and start writing the name of the new layer. For this example "**Test-Layer-02**".

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/0a4c204a-25c9-4a1f-92e1-22e23745f7c7/ascreenshot.jpeg?tl_px=0,0&br_px=982,549&force_format=png&width=983&wat_scale=87&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=178,25)


5\. Click "**Roles**" dropdown  to select the roles that will be authorized to see and use the new layer.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/c523ddb0-f59b-4875-9fd4-b9970ac080e9/user_cropped_screenshot.jpeg?tl_px=14,0&br_px=997,549&force_format=png&width=983&wat_scale=87&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=459,87)


6\. Select the roles by **clicking** on **each checkbox** or select the **first checkbox** to select all roles.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/ebd77111-f476-419a-a92a-e204f3369a3c/ascreenshot.jpeg?tl_px=0,0&br_px=982,549&force_format=png&width=983&wat_scale=87&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=107,116)


7\. Click anywhere within the window to close the dropdown options.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/30beb30a-780c-4b17-ab86-584e206ae918/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=1146,590&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=18,117)


8\. Click on the "..." in the "**Parent**" field to select a parent for the new Layer. If the new layer does not have a corresponding "**Parent**", this step is not necessary.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/762d0307-fa91-439c-8f14-6fe6e0808a9f/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=1146,590&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=99,154)


9\. For this example the new layer will have the parent "**Test-layer-01**". Start clicking "**test...**" and once the name of the layer is visible, select the layer.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/2d22e236-1001-4e9b-aacf-4a8a8d511d31/user_cropped_screenshot.jpeg?tl_px=0,37&br_px=982,586&force_format=png&width=983&wat_scale=87&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=141,243)


10\. Click this "**Type**" dropdown to select the layer type.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/9e4f019c-358f-4556-9c6b-80373edda8aa/ascreenshot.jpeg?tl_px=0,0&br_px=1146,590&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=464,206)


11\. Select the type of the layer, the most common used type is **Normal**.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/16c81970-3df8-409c-9982-8b4e07a31c9f/screenshot.png?tl_px=0,0&br_px=1355,590&force_format=png&width=1120.0)


**Tip**: Description of layer types.

**Normal:** accepts styles, responds well with less than 10,000 elements per project per layer.

**APX WMS:** accepts styles, responds well with more than 10,000 elements per project per layer

**WMS:** does not accept styles, responds well with more than 10,000 elements per project per layer, certain parameters must be set in order to to work correctly.

**Special:** only and exclusively for use in the Blockage layer.


12\. Click "**Allowed Elements Types**" dropdown.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/679018f4-b990-4670-8a14-853c6c2a1be5/ascreenshot.jpeg?tl_px=0,0&br_px=1361,590&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=384,209)


13\. Select each of the elements that can be used in the layer or select the first option which allows you to select all elements at the same time.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/687f6cc0-b181-458f-a7ed-cfc4cca3c96f/ascreenshot.jpeg?tl_px=0,40&br_px=982,590&force_format=png&width=983&wat_scale=87&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=101,253)


14\. For this example, some elements were selected (Cabinet).

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/d6e3f9c9-b88d-4b85-8cd2-0aabbcf2fae3/ascreenshot.jpeg?tl_px=0,40&br_px=982,590&force_format=png&width=983&wat_scale=87&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=102,319)


15\. For this example, some elements were selected (Fibre cable).

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/f0cef6f7-e9f8-4b38-a475-04f9c2fae143/ascreenshot.jpeg?tl_px=0,128&br_px=825,590&force_format=png&width=826&wat_scale=73&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=103,310)


16\. Click "**X**" to close the drop down menu.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/7222dcf7-7ec2-4311-acea-0924641332a7/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=1146,593&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=462,292)


17\. Click "**Add**" button to add a new parameter.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/09707a14-fac0-43b2-8baa-190c09ff5b21/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=1358,589&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=169,427)


18\. Click "**Add**" button.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/ee904efc-bee4-4733-95d0-ac34d3a1365c/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=1358,589&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=83,386)


19\. Click "**Name**" field, a space to start typing the name will be enabled, start writing the name of the new parameter. For this example, "**new param**".

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/b8862416-3262-4d60-bcfe-d3867f382c81/screenshot.png?tl_px=0,0&br_px=1359,592&force_format=png&width=1120.0)


20\. Click "**Value**" field a space to start typing the value will be enabled, start writing the value of the new parameter. For this example, "**10**".


21\. Click "**Apply**" button.

![](https://ajeuwbhvhr.cloudimg.io/colony-recorder.s3.amazonaws.com/files/2023-10-17/4f9c7d1d-78d6-44f8-ae4d-1b903bc4de64/user_cropped_screenshot.jpeg?tl_px=0,0&br_px=1355,588&force_format=png&width=1120.0&wat=1&wat_opacity=1&wat_gravity=northwest&wat_url=https://colony-recorder.s3.amazonaws.com/images/watermarks/14B8A6_standard.png&wat_pad=170,425)


**Tip**: The new layer has been created
