# Tutorial found at PQ Docs
Please see the [Microsoft Graph Tutorial](https://docs.microsoft.com/en-us/power-query/samples/mygraph/readme) at the PQ Docs site for instructions.
Microsoft Graph Tutorial is customized for gathering all provisioned team list with members from Microosft Teams by using the following API:
https://graph.microsoft.com/beta/groups?$expand=members&$filter=resourceProvisioningOptions/Any(x:x eq 'Team')