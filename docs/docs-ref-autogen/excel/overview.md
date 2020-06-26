---
title: Referenzdokumentation zur Office Scripts-API
description: Eine Übersicht über die JavaScript-APIs für Office-Skripts.
ms.date: 06/17/2020
ms.openlocfilehash: 5634d0e5f68464655054ad1c09eb7931e0da62d4
ms.sourcegitcommit: 163b26a43411ad7f13a01237efe9b8d6de656b47
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/25/2020
ms.locfileid: "44884836"
---
# <a name="office-scripts-api-reference"></a><span data-ttu-id="5a2f5-103">Referenzdokumentation zur Office Scripts-API</span><span class="sxs-lookup"><span data-stu-id="5a2f5-103">Office Scripts API reference</span></span>

<span data-ttu-id="5a2f5-104">Mit der Office Scripts-API können Sie häufige Aufgaben in Excel im Internet automatisieren.</span><span class="sxs-lookup"><span data-stu-id="5a2f5-104">The Office Scripts API lets you automate common tasks in Excel on the web.</span></span> <span data-ttu-id="5a2f5-105">In dieser Referenzdokumentation erfahren Sie mehr über die Klassen, Methoden und anderen Typen, die für Ihre Skripts verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="5a2f5-105">Use this reference documentation to learn more about the classes, methods, and other types available for your scripts.</span></span> <span data-ttu-id="5a2f5-106">Alle Objekte, auf die über Office-Skripts zugegriffen werden kann, finden Sie im Inhaltsverzeichnis auf der linken Seite.</span><span class="sxs-lookup"><span data-stu-id="5a2f5-106">All the objects accessible through Office Scripts can be found in the table of contents on the left of the page.</span></span>

> [!NOTE]
> <span data-ttu-id="5a2f5-107">Wenn Sie die JavaScript-APIs für die Entwicklung von Office-Add-ins suchen, besuchen Sie die [Office-Add-ins JavaScript-API-Referenz](/javascript/api/overview?view=excel-js-preview).</span><span class="sxs-lookup"><span data-stu-id="5a2f5-107">If you're looking for the JavaScript APIs for developing Office Add-ins, visit the [Office Add-ins JavaScript API reference](/javascript/api/overview?view=excel-js-preview).</span></span>

## <a name="common-classes"></a><span data-ttu-id="5a2f5-108">Allgemeine Klassen</span><span class="sxs-lookup"><span data-stu-id="5a2f5-108">Common classes</span></span>

<span data-ttu-id="5a2f5-109">In der folgenden Liste werden die Grundlagen des Office Scripts-Objektmodells aufgeschlüsselt.</span><span class="sxs-lookup"><span data-stu-id="5a2f5-109">The following list breaks down the basics of the Office Scripts object model.</span></span> <span data-ttu-id="5a2f5-110">Dadurch werden die allgemeinen Klassen und ihre Beziehung miteinander dargestellt.</span><span class="sxs-lookup"><span data-stu-id="5a2f5-110">This shows the common classes and how they relate to one another.</span></span>

- <span data-ttu-id="5a2f5-111">Eine [Arbeitsmappe](/javascript/api/office-scripts/excel/excelscript.workbook) enthält mindestens ein [Arbeitsblatt](/javascript/api/office-scripts/excel/excelscript.worksheet).</span><span class="sxs-lookup"><span data-stu-id="5a2f5-111">A [Workbook](/javascript/api/office-scripts/excel/excelscript.workbook) contains one or more [Worksheets](/javascript/api/office-scripts/excel/excelscript.worksheet).</span></span>
- <span data-ttu-id="5a2f5-112">Ein [Arbeitsblatt](/javascript/api/office-scripts/excel/excelscript.worksheet) ermöglicht den Zugriff auf Zellen über [Bereichsobjekte](/javascript/api/office-scripts/excel/excelscript.range).</span><span class="sxs-lookup"><span data-stu-id="5a2f5-112">A [Worksheet](/javascript/api/office-scripts/excel/excelscript.worksheet) gives access to cells through [Range](/javascript/api/office-scripts/excel/excelscript.range) objects.</span></span>
- <span data-ttu-id="5a2f5-113">Ein [Bereich](/javascript/api/office-scripts/excel/excelscript.range) besteht aus einer Gruppe zusammenhängender Zellen.</span><span class="sxs-lookup"><span data-stu-id="5a2f5-113">A [Range](/javascript/api/office-scripts/excel/excelscript.range) represents a group of contiguous cells.</span></span>
- <span data-ttu-id="5a2f5-114">[Bereiche](/javascript/api/office-scripts/excel/excelscript.range) werden verwendet, um [Tabellen](/javascript/api/office-scripts/excel/excelscript.table), [Diagramme](/javascript/api/office-scripts/excel/excelscript.chart), [Formen](/javascript/api/office-scripts/excel/excelscript.shape) sowie andere Objekte für die Datenvisualisierung oder -organisation zu erstellen und zu platzieren.</span><span class="sxs-lookup"><span data-stu-id="5a2f5-114">[Ranges](/javascript/api/office-scripts/excel/excelscript.range) are used to create and place [Tables](/javascript/api/office-scripts/excel/excelscript.table), [Charts](/javascript/api/office-scripts/excel/excelscript.chart), [Shapes](/javascript/api/office-scripts/excel/excelscript.shape), and other data visualization or organization objects.</span></span>
- <span data-ttu-id="5a2f5-115">Ein [Arbeitsblatt](/javascript/api/office-scripts/excel/excelscript.worksheet) enthält Arrays, die mit den Objekten gefüllt sind, die im einzelnen Blatt vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="5a2f5-115">A [Worksheet](/javascript/api/office-scripts/excel/excelscript.worksheet) contains arrays filled with those objects that are present in the individual sheet.</span></span>
- <span data-ttu-id="5a2f5-116">Eine [Arbeitsmappe](/javascript/api/office-scripts/excel/excelscript.workbook) enthält Arrays mit einigen dieser Datenobjekte für die gesamte Arbeitsmappe.</span><span class="sxs-lookup"><span data-stu-id="5a2f5-116">A [Workbook](/javascript/api/office-scripts/excel/excelscript.workbook) contains arrays of some of those data objects for the entire Workbook.</span></span>

<span data-ttu-id="5a2f5-117">Weitere Informationen zum Office Scripts-Objektmodell finden Sie unter [Scripting Fundamentals for Office scripts in Excel im Internet](/office/dev/scripts/develop/scripting-fundamentals) .</span><span class="sxs-lookup"><span data-stu-id="5a2f5-117">For more information about the Office Scripts object model, visit [Scripting fundamentals for Office Scripts in Excel on the web](/office/dev/scripts/develop/scripting-fundamentals)</span></span>

## <a name="see-also"></a><span data-ttu-id="5a2f5-118">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="5a2f5-118">See also</span></span>

- [<span data-ttu-id="5a2f5-119">Informationen zu Office-Skripts</span><span class="sxs-lookup"><span data-stu-id="5a2f5-119">About Office Scripts</span></span>](/office/dev/scripts/overview/excel)
- [<span data-ttu-id="5a2f5-120">Aufzeichnen, Bearbeiten und Erstellen von Office-Skripts in Excel im Web</span><span class="sxs-lookup"><span data-stu-id="5a2f5-120">Record, edit, and create Office Scripts in Excel on the web</span></span>](/office/dev/scripts/tutorials/excel-tutorial)
- [<span data-ttu-id="5a2f5-121">Grundlegendes zur Skripterstellung für Office-Skripts in Excel im Web</span><span class="sxs-lookup"><span data-stu-id="5a2f5-121">Scripting fundamentals for Office Scripts in Excel on the web</span></span>](/office/dev/scripts/develop/scripting-fundamentals)
