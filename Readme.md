<!-- default file list -->
*Files to look at*:

* **[Form1.cs](./CS/T292798/Form1.cs) (VB: [Form1.vb](./VB/T292798/Form1.vb))**
<!-- default file list end -->
# How to edit the SqlDataSource connection and query at runtime via wizard by using the SqlDataSourceUIHelper class


<p>This example demonstrates how to use the <a href="https://documentation.devexpress.com/#WindowsForms/clsDevExpressDataAccessUISqlSqlDataSourceUIHelpertopic">SqlDataSourceUIHelper</a> class to give the End-User a capability to edit the <a href="https://documentation.devexpress.com/#CoreLibraries/clsDevExpressDataAccessSqlSqlDataSourcetopic">SqlDataSource</a> component's connection or queries at runtime via wizards.</p>
<p>To execute a connection configuration wizard, call the <a href="https://documentation.devexpress.com/#WindowsForms/DevExpressDataAccessUISqlSqlDataSourceUIHelper_ConfigureConnectiontopic">SqlDataSourceUIHelper.ConfigureConnection</a> method and pass the SqlDataSource component instance to it. <br />To execute a query editing wizard, call the <a href="https://documentation.devexpress.com/#WindowsForms/DevExpressDataAccessUISqlSqlDataSourceUIHelper_EditQuerytopic">SqlDataSourceUIHelper.EditQuery</a> method and pass the SqlDataSource component's SqlQuery instance to it. <br /><strong>Note</strong> that it is necessary to refill the SqlDataSource after its connection or query was edited. Use the <a href="https://documentation.devexpress.com/#CoreLibraries/DevExpressDataAccessSqlSqlDataSource_Filltopic">SqlDataSource.Fill</a> method for this purpose.<br /><br />Finally, I would like to mention that the <a href="https://documentation.devexpress.com/#WindowsForms/clsDevExpressDataAccessUISqlSqlDataSourceUIHelpertopic">SqlDataSourceUIHelper</a> class also provides other wizards that can be used to configure the SqlDataSource component. Please refer to the <a href="https://documentation.devexpress.com/#WindowsForms/DevExpressDataAccessUISqlSqlDataSourceUIHelperMembersTopicAll">SqlDataSourceUIHelper Members</a> help topic for more information regarding this.</p>
<br /><br /><strong>See also:<br /></strong><a href="https://documentation.devexpress.com/#WindowsForms/CustomDocument18167">Binding to SQL Data</a><br /><a href="https://www.devexpress.com/Support/Center/p/T291969">T291969: SqlDataSource - How to change connection parameters at runtime</a>

<br/>


