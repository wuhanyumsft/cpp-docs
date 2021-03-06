---
title: "&lt;cfenv&gt;"
ms.date: "11/04/2016"
ms.assetid: 6a17ad51-2182-4e91-8108-65997382acd3
---
# &lt;cfenv&gt;

Includes the Standard C library header \<fenv.h> and adds the associated names to the `std` namespace.

## Syntax

```cpp
#include <cfenv>

```

## Remarks

Including this header ensures that the names declared using external linkage in the Standard C library header are declared in the `std` namespace.

## See also

[Header Files Reference](../standard-library/cpp-standard-library-header-files.md)<br/>
[C++ Standard Library Overview](../standard-library/cpp-standard-library-overview.md)<br/>
[Thread Safety in the C++ Standard Library](../standard-library/thread-safety-in-the-cpp-standard-library.md)<br/>
