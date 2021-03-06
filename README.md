## Add reusable components to a template

1. [Creating a new template](./BriteDocs-Creating_a_new_template.md) or [editing an existing template](./BriteDocs-Editing_and_previewing_a_template.md).

2. Select the Template **Editor** tab.

![Screenshot 3](accessreusablecomponents3.png)
**Figure 3:** Template Editor tab

3. Scroll to **Available Functions**

![Screenshot 4](accessreusablecomponents4.png)
**Figure 4:** Available Functions

4. Select the reusable components you want to add under **Available Functions.** 

**Table 1** summarizes each reusable component and its corresponding description: 


| Available Function  | Tag      |Description|
| ------------- | -------------------------    |------------|
| include |  ```{{ include() }} ```  |Includes a template such as Default Header, Default Footer, and Signature. |
|  asset  |   ```{ %  asset assetname  % }```| Includes an existing asset such as a Company Logo.  |
|extends| ```{{extends()}}``` |"Extends" another template by inserting it first. When the template system evaluates this tag, first if locates the parent and inserts it. The extends tag should be the first tag in the template.|
|get field answer|```{{get_field_answer(,)}}```|Loads the value of any field.|

**Figure 5** and **6** illustrate the include tag functionality.  

![Screenshot 5](accessreusablecomponents5.png)
**Figure 5:** Include tag example 

![Screenshot 6](accessreusablecomponents6.png)
**Figure 6:** Template with several Include tags
