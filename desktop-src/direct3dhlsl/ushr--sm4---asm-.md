---
title: ushr (sm4 - asm)
description: Shift right.
ms.assetid: 3E7CB515-9D0F-44C7-A770-AD0584631BFE
ms.topic: reference
ms.date: 05/31/2018
---

# ushr (sm4 - asm)

Shift right.



| ushr dest\[.mask\], src0\[.swizzle\], src1.select\_component |
|--------------------------------------------------------------|



 



| Item                                                            | Description                                                   |
|-----------------------------------------------------------------|---------------------------------------------------------------|
| <span id="dest"></span><span id="DEST"></span>*dest*<br/> | \[in\] The address of the result of the operation.<br/> |
| <span id="src0"></span><span id="SRC0"></span>*src0*<br/> | \[in\] The components to shift.<br/>                    |
| <span id="src1"></span><span id="SRC1"></span>*src1*<br/> | \[in\] The amount to shift *src0*.<br/>                 |



 

## Remarks

This instruction performs a component-wise shift of each 32-bit value in *src0* right by an unsigned integer bit count provided by the LSB 5 bits (0-31 range) in *src1.select\_component*, inserting 0. The 32-bit per component result is placed in *dest*. The count is a scalar value applied to all components.

This instruction applies to the following shader stages:



| Vertex Shader | Geometry Shader | Pixel Shader |
|---------------|-----------------|--------------|
| x             | x               | x            |



 

## Minimum Shader Model

This function is supported in the following shader models.



| Shader Model                                              | Supported |
|-----------------------------------------------------------|-----------|
| [Shader Model 5](d3d11-graphics-reference-sm5.md)        | yes       |
| [Shader Model 4.1](dx-graphics-hlsl-sm4.md)              | yes       |
| [Shader Model 4](dx-graphics-hlsl-sm4.md)                | yes       |
| [Shader Model 3 (DirectX HLSL)](dx-graphics-hlsl-sm3.md) | no        |
| [Shader Model 2 (DirectX HLSL)](dx-graphics-hlsl-sm2.md) | no        |
| [Shader Model 1 (DirectX HLSL)](dx-graphics-hlsl-sm1.md) | no        |



 

## Related topics

<dl> <dt>

[Shader Model 4 Assembly (DirectX HLSL)](dx-graphics-hlsl-sm4-asm.md)
</dt> </dl>

 

 





