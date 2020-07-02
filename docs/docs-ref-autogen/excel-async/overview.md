---
title: Referenzdokumentation zur Office Scripts-API
description: Eine Übersicht über die asynchronen JavaScript-APIs für Office-Skripts.
ms.date: 06/29/2020
ms.openlocfilehash: 3d8d37b30d9535e8b6a56a08c44f9034cb599f31
ms.sourcegitcommit: 9c4c4c213a203e58c55eb3d84d7d92fa527f3eb8
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 07/01/2020
ms.locfileid: "45003954"
---
# <a name="office-scripts-async-api-reference"></a>Office Scripts Async-API-Referenz

Die asynchrone API für Office-Skripts unterstützt ältere Skripts, die während der Office Scripts Preview-Phase erstellt wurden. In dieser Referenzdokumentation erfahren Sie mehr über die Klassen, Methoden und anderen Typen, die von diesen älteren Skripts verwendet werden. Alle Objekte, auf die über Office-Skripts zugegriffen werden kann, finden Sie im Inhaltsverzeichnis auf der linken Seite.

> [!IMPORTANT]
> Es wird dringend empfohlen, neue Skripts mit den standardmäßigen Office Scripts-APIs zu erstellen. Wenn Sie ein neues Skript erstellen oder bearbeiten, wechseln Sie zur [nicht asynchronen Version](?view=office-scripts) der APIs.

## <a name="common-classes"></a>Allgemeine Klassen

In der folgenden Liste werden die Grundlagen des Office Scripts-Objektmodells aufgeschlüsselt. Dadurch werden die allgemeinen Klassen und ihre Beziehung miteinander dargestellt.

- Eine [Arbeitsmappe](/javascript/api/office-scripts/excelscript/excelscript.workbook) enthält ein oder mehrere [Arbeitsblätter](/javascript/api/office-scripts/excelscript/excelscript.worksheet) in einer [worksheetcollection](/javascript/api/office-scripts/excelscript/excelscript.worksheetcollection).
- Ein [Arbeitsblatt](/javascript/api/office-scripts/excelscript/excelscript.worksheet) ermöglicht den Zugriff auf Zellen über [Bereichsobjekte](/javascript/api/office-scripts/excelscript/excelscript.range).
- Ein [Bereich](/javascript/api/office-scripts/excelscript/excelscript.range) besteht aus einer Gruppe zusammenhängender Zellen.
- [Bereiche](/javascript/api/office-scripts/excelscript/excelscript.range) werden verwendet, um [Tabellen](/javascript/api/office-scripts/excelscript/excelscript.table), [Diagramme](/javascript/api/office-scripts/excelscript/excelscript.chart), [Formen](/javascript/api/office-scripts/excelscript/excelscript.shape) sowie andere Objekte für die Datenvisualisierung oder -organisation zu erstellen und zu platzieren.
- Ein [Arbeitsblatt](/javascript/api/office-scripts/excelscript/excelscript.worksheet) enthält Auflistungen dieser Datenobjekte (beispielsweise eine [chartcollection](/javascript/api/office-scripts/excelscript/excelscript.chartcollection)), die im einzelnen Blatt vorhanden sind.
- [Arbeitsmappen](/javascript/api/office-scripts/excelscript/excelscript.workbook) enthalten Auflistungen einiger dieser Datenobjekte (beispielsweise eine [tablecollection](/javascript/api/office-scripts/excelscript/excelscript.tablecollection)) für die gesamte [Arbeitsmappe](/javascript/api/office-scripts/excelscript/excelscript.workbook).

Weitere Informationen zum Office Scripts-Objektmodell finden Sie unter [Scripting Fundamentals for Office scripts in Excel im Internet](/office/dev/scripts/develop/scripting-fundamentals) .

## <a name="see-also"></a>Siehe auch

- [Verwenden der Office Scripts Async-APIs zur Unterstützung von älteren Skripts](/office/dev/scripts/develop/excel-async-model)
- [Informationen zu Office-Skripts](/office/dev/scripts/overview/excel)
- [Aufzeichnen, Bearbeiten und Erstellen von Office-Skripts in Excel im Web](/office/dev/scripts/tutorials/excel-tutorial)
- [Grundlegendes zur Skripterstellung für Office-Skripts in Excel im Web](/office/dev/scripts/develop/scripting-fundamentals)
