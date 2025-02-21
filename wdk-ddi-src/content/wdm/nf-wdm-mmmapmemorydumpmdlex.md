---
UID: NF:wdm.MmMapMemoryDumpMdlEx
title: MmMapMemoryDumpMdlEx function
description: The MmMapMemoryDumpMdlEx function maps an MDL into a specified virtual address.  
tech.root: kernel
ms.date: 03/01/2020
ms.keywords: MmMapMemoryDumpMdlEx
req.header: wdm.h
req.include-header: 
req.target-type: 
req.target-min-winverclnt: Windows 10, version 2004
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
topic_type:
 - apiref
api_type:
 - DllExport
api_location:
 - wdm.h
api_name:
 - MmMapMemoryDumpMdlEx
product:
 - Windows
f1_keywords:
 - MmMapMemoryDumpMdlEx
 - wdm/MmMapMemoryDumpMdlEx
---

# MmMapMemoryDumpMdlEx function

## -description

The **MmMapMemoryDumpMdlEx** function maps an MDL into a specified virtual address.  

Only one MDL can be mapped at a time. For use by crash dump, hibernate and live dump routines only.

## -parameters

### -param Va

Supplies the VA to map.

### -param PageTotal

Supplies the total number of pages in the VA range.

### -param MemoryDumpMdl

Supplies the MDL to map.

### -param Flags

Supplies **MM_DUMP_MAP_INVALIDATE** to indicate the mapping PTEs should be zeroed and the local TB flushed.

## -returns

This function returns NTSTATUS.

## -remarks

## -see-also
