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
# <a name="office-scripts-api-reference"></a>Referenzdokumentation zur Office Scripts-API

Mit der Office Scripts-API können Sie häufige Aufgaben in Excel im Internet automatisieren. In dieser Referenzdokumentation erfahren Sie mehr über die Klassen, Methoden und anderen Typen, die für Ihre Skripts verfügbar sind. Alle Objekte, auf die über Office-Skripts zugegriffen werden kann, finden Sie im Inhaltsverzeichnis auf der linken Seite.

> [!NOTE]
> Wenn Sie die JavaScript-APIs für die Entwicklung von Office-Add-ins suchen, besuchen Sie die [Office-Add-ins JavaScript-API-Referenz](/javascript/api/overview?view=excel-js-preview).

## <a name="common-classes"></a>Allgemeine Klassen

In der folgenden Liste werden die Grundlagen des Office Scripts-Objektmodells aufgeschlüsselt. Dadurch werden die allgemeinen Klassen und ihre Beziehung miteinander dargestellt.

- Eine [Arbeitsmappe](/javascript/api/office-scripts/excel/excelscript.workbook) enthält mindestens ein [Arbeitsblatt](/javascript/api/office-scripts/excel/excelscript.worksheet).
- Ein [Arbeitsblatt](/javascript/api/office-scripts/excel/excelscript.worksheet) ermöglicht den Zugriff auf Zellen über [Bereichsobjekte](/javascript/api/office-scripts/excel/excelscript.range).
- Ein [Bereich](/javascript/api/office-scripts/excel/excelscript.range) besteht aus einer Gruppe zusammenhängender Zellen.
- [Bereiche](/javascript/api/office-scripts/excel/excelscript.range) werden verwendet, um [Tabellen](/javascript/api/office-scripts/excel/excelscript.table), [Diagramme](/javascript/api/office-scripts/excel/excelscript.chart), [Formen](/javascript/api/office-scripts/excel/excelscript.shape) sowie andere Objekte für die Datenvisualisierung oder -organisation zu erstellen und zu platzieren.
- Ein [Arbeitsblatt](/javascript/api/office-scripts/excel/excelscript.worksheet) enthält Arrays, die mit den Objekten gefüllt sind, die im einzelnen Blatt vorhanden sind.
- Eine [Arbeitsmappe](/javascript/api/office-scripts/excel/excelscript.workbook) enthält Arrays mit einigen dieser Datenobjekte für die gesamte Arbeitsmappe.

Weitere Informationen zum Office Scripts-Objektmodell finden Sie unter [Scripting Fundamentals for Office scripts in Excel im Internet](/office/dev/scripts/develop/scripting-fundamentals) .

## <a name="see-also"></a>Siehe auch

- [Informationen zu Office-Skripts](/office/dev/scripts/overview/excel)
- [Aufzeichnen, Bearbeiten und Erstellen von Office-Skripts in Excel im Web](/office/dev/scripts/tutorials/excel-tutorial)
- [Grundlegendes zur Skripterstellung für Office-Skripts in Excel im Web](/office/dev/scripts/develop/scripting-fundamentals)
