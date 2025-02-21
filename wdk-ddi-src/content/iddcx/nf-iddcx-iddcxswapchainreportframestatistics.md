---
UID: NF:iddcx.IddCxSwapChainReportFrameStatistics
title: IddCxSwapChainReportFrameStatistics function (iddcx.h)
description: An OS callback function the driver calls to report the frame statistics after it has processed a frame completely.
old-location: display\iddcxswapchainreportframestatistics.htm
tech.root: display
ms.date: 05/10/2018
keywords: ["IddCxSwapChainReportFrameStatistics function"]
ms.keywords: IddCxSwapChainReportFrameStatistics, IddCxSwapChainReportFrameStatistics method [Display Devices], display.iddcxswapchainreportframestatistics, iddcx/IddCxSwapChainReportFrameStatistics
req.header: iddcx.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 10
req.target-min-winversvr: Windows Server 2016
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: IddCxStub.lib
req.dll: IddCx.dll
req.irql: _Must_inspect_result_
targetos: Windows
req.typenames: 
f1_keywords:
 - IddCxSwapChainReportFrameStatistics
 - iddcx/IddCxSwapChainReportFrameStatistics
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - DllExport
api_location:
 - IddCx.dll
api_name:
 - IddCxSwapChainReportFrameStatistics
---

# IddCxSwapChainReportFrameStatistics function


## -description

An OS callback function the driver calls to report the frame statistics after it has processed a frame completely

## -parameters

### -param SwapChainObject


[in[ Pointer to a [**IDARG_IN_REPORTFRAMESTATISTICS **](ns-iddcx-idarg_in_reportframestatistics.md) structure.

### -param pInArgs [in]


Input arguments to the function

## -returns

(NTSTATUS) The method returns STATUS_SUCCESS if the operation succeeds. Otherwise, this method may return an appropriate <a href="/windows-hardware/drivers/kernel/ntstatus-values">NTSTATUS</a> error code.
