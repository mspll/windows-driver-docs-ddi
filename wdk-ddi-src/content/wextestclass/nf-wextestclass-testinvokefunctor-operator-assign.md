---
UID: NF:wextestclass.TestInvokeFunctor.operator-assign
title: "TestInvokeFunctor::operator= function (wextestclass.h)"
description: "The operator= overloaded assignment operator sets the typed data represented by the ExtRemoteTyped object by copying the information from another object."
old-location: debugger\extremotetyped_operatorequals_debug_typed_data.htm
tech.root: taef
ms.date: 02/27/2018
keywords: ["operator= function"]
ms.keywords: ExtRemoteTyped class [Windows Debugging], operator= method, debugger.extremotetyped_operatorequals_debug_typed_data, operator=, operator= method [Windows Debugging], operator= method [Windows Debugging], ExtRemoteTyped class
req.header: wextestclass.h
req.include-header: Engextcpp.hpp, Wexlogtrace.h, Wextestclass.h, Wextestclass.h
req.target-type: Desktop
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: NtosKrnl.exe
req.dll: 
req.irql: 
targetos: Windows
req.typenames: TTraceLevel
req.product: Windows 10 or later.
f1_keywords:
 - TestInvokeFunctor::operator=
 - wextestclass/TestInvokeFunctor::operator=
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - arrayofelements.hpp
api_name:
 - TestInvokeFunctor::operator=
---

# operator= function


## -description

The <b>operator=</b> overloaded assignment operator sets the typed data represented by the <a href="..\engextcpp\nl-engextcpp-extremotetyped.md">ExtRemoteTyped</a> object by copying the information from another object.

## -parameters

## -param

<p>A pointer to a <a href="/windows-hardware/drivers/ddi/wdbgexts/ns-wdbgexts-_debug_typed_data"><b>DEBUG_TYPED_DATA</b></a> structure that describes the data and type to be assigned to this object.</p>

## -returns

<b>operator=</b>  returns the <a href="..\engextcpp\nl-engextcpp-extremotetyped.md">ExtRemoteTyped</a> object.

## -syntax

```
ExtRemoteTyped & operator=(
  [in] const DEBUG_TYPED_DATA *Typed
);
```

## -remarks

The typed data can also be copied using the <a href="..\engextcpp\nf-engextcpp-extbuffer-copy(const_t_ulong).md">ExtRemoteTyped::Copy(Debug Typed Data)</a> or <a href="..\engextcpp\nf-engextcpp-extbuffer-copy(const_t_ulong).md">ExtRemoteTyped::Copy(ExtRemoteTyped)</a> methods.

## -see-also

<a href="..\engextcpp\nl-engextcpp-extremotetyped.md">ExtRemoteTyped</a>



<a href="..\wextestclass\nf-wextestclass-fixtureinvokefunctor-operator-assign.md">ExtRemoteTyped::Operator= (ExtRemoteTyped)</a>



<a href="..\wdbgexts\ns-wdbgexts-_debug_typed_data.md">DEBUG_TYPED_DATA</a>

