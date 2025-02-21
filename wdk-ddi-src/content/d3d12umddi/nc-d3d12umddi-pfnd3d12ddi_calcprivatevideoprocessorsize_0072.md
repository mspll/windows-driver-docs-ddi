---
UID: NC:d3d12umddi.PFND3D12DDI_CALCPRIVATEVIDEOPROCESSORSIZE_0072
title: PFND3D12DDI_CALCPRIVATEVIDEOPROCESSORSIZE_0072 (d3d12umddi.h)
description: Learn more about the PFND3D12DDI_CALCPRIVATEVIDEOPROCESSORSIZE_0072 callback function.
ms.date: 12/15/2023
keywords: ["PFND3D12DDI_CALCPRIVATEVIDEOPROCESSORSIZE_0072 callback function"]
req.header: d3d12umddi.h
req.include-header: 
req.target-type: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.lib: 
req.dll: 
req.irql: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
targetos: Windows
tech.root: display
f1_keywords:
 - PFND3D12DDI_CALCPRIVATEVIDEOPROCESSORSIZE_0072
 - d3d12umddi/PFND3D12DDI_CALCPRIVATEVIDEOPROCESSORSIZE_0072
topic_type:
 - apiref
api_type:
 - UserDefined
api_location:
 - d3d12umddi.h
api_name:
 - PFND3D12DDI_CALCPRIVATEVIDEOPROCESSORSIZE_0072
product:
 - Windows
---

# PFND3D12DDI_CALCPRIVATEVIDEOPROCESSORSIZE_0072 callback function

## -description

**PFND3D12DDI_CALCPRIVATEVIDEOPROCESSORSIZE_0072** calculates the size of the private video processor.

## -parameters

### -param hDrvDevice

A handle to the display device (graphics context).

### -param pArgs

Pointer to a [**D3D12DDIARG_CREATE_VIDEO_PROCESSOR_0072**](ns-d3d12umddi-d3d12ddiarg_create_video_processor_0072.md) structure with arguments for this callback to use.

## -returns

Returns the size of the video processor in bytes.

## -remarks

The Direct3D runtime allocates memory for storing the driver's CPU object that represents the video processor. This method is used to calculate the driver object size.

See the [D3D Video Protected Resource Support Specification](https://microsoft.github.io/DirectX-Specs/d3d/D3D12_Video_ProtectedResourceSupport.html) for more information.

## -see-also

[**D3D12DDIARG_CREATE_VIDEO_PROCESSOR_0072**](ns-d3d12umddi-d3d12ddiarg_create_video_processor_0072.md)
