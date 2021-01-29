# Graph API Beta Custom Connector for Power BI
Please see the [Microsoft Graph Tutorial](https://docs.microsoft.com/power-query/samples/mygraph/readme?WT.mc_id=m365-0000-aycabas) at the PQ Docs site for instructions.
Microsoft Graph Tutorial is customized for gathering all provisioned team list with members from Microosft Teams by using the following API:
https://graph.microsoft.com/beta/groups?WT.mc_id=m365-0000-aycabas$expand=members&$filter=resourceProvisioningOptions/Any(x:x eq 'Team')
