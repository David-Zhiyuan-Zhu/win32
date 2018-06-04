---
Description: Effect default parameters.
ms.assetid: a8a24cf2-0ecd-4429-97d3-086ff49540a1
title: D3DXEFFECTDEFAULT structure
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: structure
ms.date: 05/31/2018
---

# D3DXEFFECTDEFAULT structure

Effect default parameters.

## Syntax


```C++
typedef struct D3DXEFFECTDEFAULT {
  LPSTR                 pParamName;
  D3DXEFFECTDEFAULTTYPE Type;
  DWORD                 NumBytes;
  LPVOID                pValue;
} D3DXEFFECTDEFAULT, *LPD3DXEFFECTDEFAULT;
```



## Members

<dl> <dt>

**pParamName**
</dt> <dd>

Type: **LPSTR**

</dd> <dd>

Parameter name.

</dd> <dt>

**Type**
</dt> <dd>

Type: **[**D3DXEFFECTDEFAULTTYPE**](https://msdn.microsoft.com/windows/desktop/d698ad6e-2ce2-48d6-90be-49bc08f172a9)**

</dd> <dd>

Data type in pValue. For more information, see [**D3DXEFFECTDEFAULTTYPE**](https://msdn.microsoft.com/windows/desktop/d698ad6e-2ce2-48d6-90be-49bc08f172a9)

</dd> <dt>

**NumBytes**
</dt> <dd>

Type: **[**DWORD**](https://msdn.microsoft.com/windows/desktop/4553cafc-450e-4493-a4d4-cb6e2f274d46)**

</dd> <dd>

Size, in bytes, of the data pointed to by pValue.

</dd> <dt>

**pValue**
</dt> <dd>

Type: **[**LPVOID**](https://msdn.microsoft.com/windows/desktop/4553cafc-450e-4493-a4d4-cb6e2f274d46)**

</dd> <dd>

Pointer to the memory location that contains the data.

</dd> </dl>

## Requirements



|                   |                                                                                        |
|-------------------|----------------------------------------------------------------------------------------|
| Header<br/> | <dl> <dt>D3dx9mesh.h</dt> </dl> |



## See also

<dl> <dt>

[Effect Structures](dx9-graphics-reference-effects-structures.md)
</dt> </dl>

 

 



