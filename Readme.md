<!-- default file list -->
*Files to look at*:

* [Default.aspx](./CS/WebSite/Default.aspx) (VB: [Default.aspx](./VB/WebSite/Default.aspx))
* [Default.aspx.cs](./CS/WebSite/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/WebSite/Default.aspx.vb))
<!-- default file list end -->
# ASPxGridView - how to hide Text in the GridViewDataColorEditColumn in browse mode


This task is implemented with DataItemTemplate:

```
<dx:GridViewDataColorEditColumn FieldName="Color" VisibleIndex="3">
                        <DataItemTemplate>
                            <div style="width: 15px; height: 15px; border: #9f9f9f 1px solid; background-color: <%#Container.Text %>"></div>
                        </DataItemTemplate>
</dx:GridViewDataColorEditColumn>
```
