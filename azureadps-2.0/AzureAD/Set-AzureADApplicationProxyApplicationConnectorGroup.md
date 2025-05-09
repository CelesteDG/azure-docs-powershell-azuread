---
external help file: Microsoft.Open.MS.GraphV10.PowerShell.Custom.dll-Help.xml
Module Name: AzureAD
online version:
schema: 2.0.0
---

# Set-AzureADApplicationProxyApplicationConnectorGroup

## SYNOPSIS
The Set-AzureADApplicationProxyApplicationConnectorGroup cmdlet assigns the given connector group to a specified application.

## SYNTAX

```
Set-AzureADApplicationProxyApplicationConnectorGroup -ObjectId <String> -ConnectorGroupId <String>
 [<CommonParameters>]
```

## DESCRIPTION
The Set-AzureADApplicationProxyApplicationConnectorGroup cmdlet sets the connector group assigned for the specified application.
The application must be configured for Application Proxy in Azure Active Directory (AD).

## EXAMPLES

### Example 1
```
PS C:\> Set-AzureADApplicationProxyApplicationConnectorGroup -ObjectId aaaaaaaa-0000-1111-2222-bbbbbbbbbbbb -ConnectorGroupId bbbbbbbb-1111-2222-3333-cccccccccccc
```

Example 1: Set a new Connector Group for a specific application

## PARAMETERS

### -ConnectorGroupId
The Id of the Connector group that should be assigned to the application.
You can find this by using the Get-AzureADApplicationProxyConnectorGroup command.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### -ObjectId
The unique application Id for the application the Connector group will be assigned to.
This can be found using the Get-AzureADApplication command.

```yaml
Type: String
Parameter Sets: (All)
Aliases:

Required: True
Position: Named
Default value: None
Accept pipeline input: True (ByPropertyName, ByValue)
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](http://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### System.String
## OUTPUTS

### System.Object
## NOTES

## RELATED LINKS
