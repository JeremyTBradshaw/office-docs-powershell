---
external help file: Microsoft.Exchange.TransportMailflow-Help.xml
online version: https://docs.microsoft.com/powershell/module/exchange/set-policyconfig
applicable: Security & Compliance Center
title: Set-PolicyConfig
schema: 2.0.0
author: chrisda
ms.author: chrisda
ms.reviewer:
---

# Set-PolicyConfig

## SYNOPSIS
This cmdlet is available only in Security & Compliance Center PowerShell. For more information, see [Security & Compliance Center PowerShell](https://docs.microsoft.com/powershell/exchange/scc-powershell).

Use the Set-PolicyConfig cmdlet to 

For information about the parameter sets in the Syntax section below, see [Exchange cmdlet syntax](https://docs.microsoft.com/powershell/exchange/exchange-cmdlet-syntax).

## SYNTAX

```
Set-PolicyConfig
 [-ClassificationScheme <ClassificationScheme>]
 [-ComplianceUrl <String>]
 [-Confirm]
 [-DocumentIsUnsupportedSeverity <RuleSeverity>]
 [-EnableLabelCoauth <Boolean>]
 [-EnableSpoAipMigration <Boolean>]
 [-EndpointDlpGlobalSettings <PswsHashtable[]>]
 [-EndpointDlpGlobalSettingsPsws <PswsHashtable[]>]
 [-OnPremisesWorkload <Workload>]
 [-ProcessingLimitExceededSeverity <RuleSeverity>]
 [-RetentionForwardCrawl <Boolean>]
 [-RuleErrorAction <PolicyRuleErrorAction>]
 [-SenderAddressLocation <PolicySenderAddressLocation>]
 [-WhatIf]
 [<CommonParameters>]
```

## DESCRIPTION
You need to be assigned permissions in the Security & Compliance Center before you can use this cmdlet. For more information, see [Permissions in the Security & Compliance Center](https://docs.microsoft.com/microsoft-365/security/office-365-security/permissions-in-the-security-and-compliance-center).

## EXAMPLES

### Example 1
```powershell
{{ Add example code here }}
```

{{ Add example description here }}

## PARAMETERS

### -ClassificationScheme
{{ Fill ClassificationScheme Description }}

```yaml
Type: ClassificationScheme
Parameter Sets: (All)
Aliases:
Accepted values: Default, V0_AggregatedOnly, V1_DetailedResults
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ComplianceUrl
{{ Fill ComplianceUrl Description }}

```yaml
Type: String
Parameter Sets: (All)
Aliases:
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Confirm
The Confirm switch specifies whether to show or hide the confirmation prompt. How this switch affects the cmdlet depends on if the cmdlet requires confirmation before proceeding.

- Destructive cmdlets (for example, Remove-\* cmdlets) have a built-in pause that forces you to acknowledge the command before proceeding. For these cmdlets, you can skip the confirmation prompt by using this exact syntax: -Confirm:$false.
- Most other cmdlets (for example, New-\* and Set-\* cmdlets) don't have a built-in pause. For these cmdlets, specifying the Confirm switch without a value introduces a pause that forces you acknowledge the command before proceeding.


```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -DocumentIsUnsupportedSeverity
{{ Fill DocumentIsUnsupportedSeverity Description }}

```yaml
Type: RuleSeverity
Parameter Sets: (All)
Aliases:
Accepted values: Low, Medium, High, None, Informational, Information
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EnableLabelCoauth
{{ Fill EnableLabelCoauth Description }}

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases:
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EnableSpoAipMigration
{{ Fill EnableSpoAipMigration Description }}

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases:
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EndpointDlpGlobalSettings
{{ Fill EndpointDlpGlobalSettings Description }}

```yaml
Type: PswsHashtable[]
Parameter Sets: (All)
Aliases:
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -EndpointDlpGlobalSettingsPsws
{{ Fill EndpointDlpGlobalSettingsPsws Description }}

```yaml
Type: PswsHashtable[]
Parameter Sets: (All)
Aliases:
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -OnPremisesWorkload
{{ Fill OnPremisesWorkload Description }}

```yaml
Type: Workload
Parameter Sets: (All)
Aliases:
Accepted values: None, Exchange, SharePoint, Intune, OneDriveForBusiness, PublicFolder, SharePointOnPremises, ExchangeOnPremises, AuditAlerting, Skype, ModernGroup, DynamicScope, Teams, UnifiedAuditAzure, EndpointDevices, ThirdPartyApps, OnPremisesScanner
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -ProcessingLimitExceededSeverity
{{ Fill ProcessingLimitExceededSeverity Description }}

```yaml
Type: RuleSeverity
Parameter Sets: (All)
Aliases:
Accepted values: Low, Medium, High, None, Informational, Information
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RetentionForwardCrawl
{{ Fill RetentionForwardCrawl Description }}

```yaml
Type: Boolean
Parameter Sets: (All)
Aliases:
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -RuleErrorAction
{{ Fill RuleErrorAction Description }}

```yaml
Type: PolicyRuleErrorAction
Parameter Sets: (All)
Aliases:
Accepted values: Ignore, RetryThenBlock
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -SenderAddressLocation
{{ Fill SenderAddressLocation Description }}

```yaml
Type: PolicySenderAddressLocation
Parameter Sets: (All)
Aliases:
Accepted values: Header, Envelope, HeaderOrEnvelope
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
The WhatIf switch doesn't work in Security & Compliance Center PowerShell.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi
Applicable: Security & Compliance Center

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/p/?LinkID=113216).

## INPUTS

###  

## OUTPUTS

###  

## NOTES

## RELATED LINKS