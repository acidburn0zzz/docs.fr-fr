---
title: Interface de IXCLRDataMethodInstance
ms.date: 01/16/2019
api.name:
- IXCLRDataMethodInstance Interface
api.location:
- mscordacwks.dll
api.type:
- COM
f1.keywords:
- IXCLRDataMethodInstance Interface
helpviewer.keywords:
- IXCLRDataMethodInstance Interface [.NET Framework debugging]
topic_type:
- apiref
author: cshung
ms.author: andrewau
ms.openlocfilehash: 0eef69cea9f59911b5076f56579b0192be357431
ms.sourcegitcommit: 6b308cf6d627d78ee36dbbae8972a310ac7fd6c8
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/23/2019
ms.locfileid: "54659109"
---
# <a name="ixclrdatamethodinstance-interface"></a><span data-ttu-id="fcc98-102">Interface de IXCLRDataMethodInstance</span><span class="sxs-lookup"><span data-stu-id="fcc98-102">IXCLRDataMethodInstance Interface</span></span>

<span data-ttu-id="fcc98-103">Fournit des méthodes pour obtenir des informations sur une instance de méthode.</span><span class="sxs-lookup"><span data-stu-id="fcc98-103">Provides methods for querying information about a method instance.</span></span>

[!INCLUDE[debugging-api-recommended-note](../../../../includes/debugging-api-recommended-note.md)]

## <a name="methods"></a><span data-ttu-id="fcc98-104">Méthodes</span><span class="sxs-lookup"><span data-stu-id="fcc98-104">Methods</span></span>

| <span data-ttu-id="fcc98-105">Méthode</span><span class="sxs-lookup"><span data-stu-id="fcc98-105">Method</span></span>                                                                                                                  | <span data-ttu-id="fcc98-106">Description</span><span class="sxs-lookup"><span data-stu-id="fcc98-106">Description</span></span>                                 |
| ----------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| [<span data-ttu-id="fcc98-107">GetILAddressMap</span><span class="sxs-lookup"><span data-stu-id="fcc98-107">GetILAddressMap</span></span>](../../../../docs/framework/unmanaged-api/debugging/ixclrdatamethodinstance-getiladdressmap-method.md) | <span data-ttu-id="fcc98-108">Obtient le langage intermédiaire aux informations de mappage d’adresse.</span><span class="sxs-lookup"><span data-stu-id="fcc98-108">Gets the IL to address mapping information.</span></span> |

## <a name="remarks"></a><span data-ttu-id="fcc98-109">Notes</span><span class="sxs-lookup"><span data-stu-id="fcc98-109">Remarks</span></span>

<span data-ttu-id="fcc98-110">Cette interface réside dans le runtime et n’est pas exposée par le biais d’en-têtes ou les fichiers de bibliothèque.</span><span class="sxs-lookup"><span data-stu-id="fcc98-110">This interface lives inside the runtime and is not exposed through any headers or library files.</span></span> <span data-ttu-id="fcc98-111">Toutefois, il est une interface COM qui dérive de `IUnknown` avec le GUID `ECD73800-22CA-4b0d-AB55-E9BA7E6318A5` qui peuvent être obtenues via les mécanismes COM habituels.</span><span class="sxs-lookup"><span data-stu-id="fcc98-111">However, it's a COM interface that derives from `IUnknown` with GUID `ECD73800-22CA-4b0d-AB55-E9BA7E6318A5` that can be obtained through the usual COM mechanisms.</span></span>

## <a name="requirements"></a><span data-ttu-id="fcc98-112">Spécifications</span><span class="sxs-lookup"><span data-stu-id="fcc98-112">Requirements</span></span>

<span data-ttu-id="fcc98-113">**Plateformes :** Consultez [Configuration requise](../../../../docs/framework/get-started/system-requirements.md).</span><span class="sxs-lookup"><span data-stu-id="fcc98-113">**Platforms:** See [System Requirements](../../../../docs/framework/get-started/system-requirements.md).</span></span>  
<span data-ttu-id="fcc98-114">**En-tête :** Aucun.</span><span class="sxs-lookup"><span data-stu-id="fcc98-114">**Header:** None</span></span>  
<span data-ttu-id="fcc98-115">**Bibliothèque :** Aucun.</span><span class="sxs-lookup"><span data-stu-id="fcc98-115">**Library:** None</span></span>  
<span data-ttu-id="fcc98-116">**Versions du .NET Framework :** [!INCLUDE[net_current_v47plus](../../../../includes/net-current-v47plus.md)]</span><span class="sxs-lookup"><span data-stu-id="fcc98-116">**.NET Framework Versions:** [!INCLUDE[net_current_v47plus](../../../../includes/net-current-v47plus.md)]</span></span>  

## <a name="see-also"></a><span data-ttu-id="fcc98-117">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="fcc98-117">See also</span></span>

- [<span data-ttu-id="fcc98-118">Débogage</span><span class="sxs-lookup"><span data-stu-id="fcc98-118">Debugging</span></span>](../../../../docs/framework/unmanaged-api/debugging/index.md)
- [<span data-ttu-id="fcc98-119">Interfaces de débogage</span><span class="sxs-lookup"><span data-stu-id="fcc98-119">Debugging Interfaces</span></span>](../../../../docs/framework/unmanaged-api/debugging/debugging-interfaces.md)