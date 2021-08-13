---
title: Referenzdokumentation zur Office Scripts-API
description: Eine Übersicht über die JavaScript-APIs für Office Skripts.
ms.date: 06/29/2020
ms.openlocfilehash: 3ce3344fb49b2811719feb13f8fb4118f1a20060db9d85a06d1be939f22bf3c5
ms.sourcegitcommit: 6a0182075a558c4fe664fedfee08fea76513b192
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/11/2021
ms.locfileid: "58183426"
---
# <a name="office-scripts-api-reference"></a>Referenzdokumentation zur Office Scripts-API

Mit der api Office Skripts können Sie allgemeine Aufgaben in Excel im Web automatisieren. Verwenden Sie diese Referenzdokumentation, um mehr über die Klassen, Methoden und anderen Typen zu erfahren, die für Ihre Skripts verfügbar sind. Alle Objekte, auf die über Office Skripts zugegriffen werden kann, befinden sich im Inhaltsverzeichnis auf der linken Seite.

> [!NOTE]
> Wenn Sie nach den JavaScript-APIs für die Entwicklung von Office-Add-Ins suchen, besuchen Sie die [JavaScript-API-Referenz Office Add-Ins.](/javascript/api/overview?view=excel-js-preview)

## <a name="common-classes"></a>Allgemeine Klassen

In der folgenden Liste werden die Grundlagen des Office Scripts-Objektmodells aufgeführt. Dies zeigt die allgemeinen Klassen und deren Beziehung zueinander.

- Eine [Arbeitsmappe](/javascript/api/office-scripts/excelscript/excelscript.workbook) enthält mindestens ein [Arbeitsblatt](/javascript/api/office-scripts/excelscript/excelscript.worksheet).
- Ein [Arbeitsblatt](/javascript/api/office-scripts/excelscript/excelscript.worksheet) ermöglicht den Zugriff auf Zellen über [Bereichsobjekte](/javascript/api/office-scripts/excelscript/excelscript.range).
- Ein [Bereich](/javascript/api/office-scripts/excelscript/excelscript.range) besteht aus einer Gruppe zusammenhängender Zellen.
- [Bereiche](/javascript/api/office-scripts/excelscript/excelscript.range) werden verwendet, um [Tabellen](/javascript/api/office-scripts/excelscript/excelscript.table), [Diagramme](/javascript/api/office-scripts/excelscript/excelscript.chart), [Formen](/javascript/api/office-scripts/excelscript/excelscript.shape) sowie andere Objekte für die Datenvisualisierung oder -organisation zu erstellen und zu platzieren.
- Ein [Arbeitsblatt](/javascript/api/office-scripts/excelscript/excelscript.worksheet) enthält Arrays, die mit den Objekten gefüllt sind, die im einzelnen Blatt vorhanden sind.
- Eine [Arbeitsmappe](/javascript/api/office-scripts/excelscript/excelscript.workbook) enthält Arrays einiger dieser Datenobjekte für die gesamte Arbeitsmappe.

Weitere Informationen zum Office Scripts-Objektmodell finden Sie [unter Scripting fundamentals for Office Scripts in Excel im Web](/office/dev/scripts/develop/scripting-fundamentals)

## <a name="see-also"></a>Siehe auch

- [Informationen zu Office Skripts](/office/dev/scripts/overview/excel)
- [Aufzeichnen, Bearbeiten und Erstellen von Office-Skripts in Excel im Web](/office/dev/scripts/tutorials/excel-tutorial)
- [Grundlagen der Skripterstellung für Office-Skripts in Excel im Web](/office/dev/scripts/develop/scripting-fundamentals)
