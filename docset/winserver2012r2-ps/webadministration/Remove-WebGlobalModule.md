---
external help file: Microsoft.IIS.PowerShell.Provider.dll-Help.xml
Module Name: WebAdministration
online version: 
schema: 2.0.0
title: Remove-WebGlobalModule
description: 
keywords: powershell, cmdlet
author: Kateyanne
manager: jasgro
ms.date: 10/30/2017
ms.topic: reference
ms.prod: powershell
ms.technology: powershell
ms.assetid: 54025C94-825F-4597-810C-415F63EA9D1D
ms.author: v-kaunu
ms.reviewer: brianlic
---

# Remove-WebGlobalModule

## SYNOPSIS
Removes an IIS module.

## SYNTAX

```
Remove-WebGlobalModule [-Name] <String> [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
The **Remove-WebGlobalModule** cmdlet removes an Internet Information Services (IIS) module.

## EXAMPLES

### Example 1: Removing a module
```
IIS:\>Remove-WebGlobalModule -Name "testGlobalModule"
```

This command removes the module named testGlobalModule from the default website.

## PARAMETERS

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -Name
Specifies the name of the module to remove.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 0
Default value: None
Accept pipeline input: True (ByPropertyName)
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

[Disable-WebGlobalModule](./Disable-WebGlobalModule.md)

[Enable-WebGlobalModule](./Enable-WebGlobalModule.md)

[Get-WebGlobalModule](./Get-WebGlobalModule.md)

[New-WebGlobalModule](./New-WebGlobalModule.md)

[Set-WebGlobalModule](./Set-WebGlobalModule.md)

