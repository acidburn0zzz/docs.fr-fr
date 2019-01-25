---
title: Méthode SqlStreamChars.SetLength(Int64) (System.Data.SqlTypes)
author: douglaslMS
ms.author: douglasl
ms.date: 12/20/2018
ms.technology:
- dotnet-data
topic_type:
- apiref
api_name:
- System.Data.SqlTypes.SqlStreamChars.SetLength
api_location:
- System.Data.dll
api_type:
- Assembly
ms.openlocfilehash: c7199cbd08e62b1f0391437a0c1864cb9036fe1f
ms.sourcegitcommit: a36cfc9dbbfc04bd88971f96e8a3f8e283c15d42
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/11/2019
ms.locfileid: "54222695"
---
# <a name="sqlstreamcharssetlengthint64-method"></a><span data-ttu-id="39450-102">SqlStreamChars.SetLength(Int64) (méthode)</span><span class="sxs-lookup"><span data-stu-id="39450-102">SqlStreamChars.SetLength(Int64) Method</span></span>

<span data-ttu-id="39450-103">En cas de substitution dans une classe dérivée, libère les ressources utilisées par le flux.</span><span class="sxs-lookup"><span data-stu-id="39450-103">When overridden in a derived class, releases the resources used by the stream.</span></span> <span data-ttu-id="39450-104">L’assembly qui contient cette méthode a une relation de friend avec SQLAccess.dll.</span><span class="sxs-lookup"><span data-stu-id="39450-104">The assembly that contains this method has a friend relationship with SQLAccess.dll.</span></span> <span data-ttu-id="39450-105">Il est prévu pour une utilisation par SQL Server.</span><span class="sxs-lookup"><span data-stu-id="39450-105">It's intended for use by SQL Server.</span></span> <span data-ttu-id="39450-106">Pour les autres bases de données, utilisez le mécanisme d’hébergement fourni par cette base de données.</span><span class="sxs-lookup"><span data-stu-id="39450-106">For other databases, use the hosting mechanism provided by that database.</span></span>

```csharp
public abstract void SetLength (long value);
```

## <a name="parameters"></a><span data-ttu-id="39450-107">Paramètres</span><span class="sxs-lookup"><span data-stu-id="39450-107">Parameters</span></span>

`value`\
<span data-ttu-id="39450-108">Longueur souhaitée du flux actuel en octets.</span><span class="sxs-lookup"><span data-stu-id="39450-108">The desired length of the current stream in bytes.</span></span>

## <a name="remarks"></a><span data-ttu-id="39450-109">Notes</span><span class="sxs-lookup"><span data-stu-id="39450-109">Remarks</span></span>

> [!WARNING]
> <span data-ttu-id="39450-110">Le `SqlStreamChars.SetLength` méthode est privée et qu’il n’est pas destiné à être utilisé directement dans votre code.</span><span class="sxs-lookup"><span data-stu-id="39450-110">The `SqlStreamChars.SetLength` method is private and is not meant to be used directly in your code.</span></span>
>
> <span data-ttu-id="39450-111">Microsoft ne prend pas en charge l’utilisation de ce champ dans une application de production en toute circonstance.</span><span class="sxs-lookup"><span data-stu-id="39450-111">Microsoft does not support the use of this field in a production application under any circumstance.</span></span>

## <a name="requirements"></a><span data-ttu-id="39450-112">Spécifications</span><span class="sxs-lookup"><span data-stu-id="39450-112">Requirements</span></span>

<span data-ttu-id="39450-113">**Espace de noms :** <xref:System.Data.SqlTypes></span><span class="sxs-lookup"><span data-stu-id="39450-113">**Namespace:** <xref:System.Data.SqlTypes></span></span>

<span data-ttu-id="39450-114">**Assembly :** System.Data (dans System.Data.dll)</span><span class="sxs-lookup"><span data-stu-id="39450-114">**Assembly:** System.Data (in System.Data.dll)</span></span>

<span data-ttu-id="39450-115">**Versions du .NET framework :** Disponible à partir de 2.0.</span><span class="sxs-lookup"><span data-stu-id="39450-115">**.NET Framework versions:** Available since 2.0.</span></span>