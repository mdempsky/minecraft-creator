---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.service: minecraft-bedrock-edition
title: minecraft/server-editor.IVector3PropertyItem Interface
description: Contents of the @minecraft/server-editor.IVector3PropertyItem class.
---
# IVector3PropertyItem Interface

## Extends
- *IPropertyItemBase*

A property item which supports Vector3 properties

## Properties

### **value**
`read-only value: Readonly<Vector3>;`

Current value of the property item.

Type: *Readonly<Vector3>*

## Methods
- [updateAxisLimits](#updateaxislimits)

### **updateAxisLimits**
`
updateAxisLimits(limits: {
        min?: Partial<Vector3>;
        max?: Partial<Vector3>;
    }): void
`

Updates Vector3 limits and clamps the current value.

#### **Parameters**
- **limits**: *{
        min?: Partial<Vector3>;
        max?: Partial<Vector3>;
    }*

**Returns** *void*
