---
title: Office Scripts-API-Referenz
description: Eine Übersicht über die JavaScript-APIs für Office-Skripts
ms.date: 12/12/2019
ms.openlocfilehash: b3e75cbecac13f41c83f019c681b0682571ead41
ms.sourcegitcommit: 2834ee43a14a4b0953d5fb22749c115a42960e20
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/10/2020
ms.locfileid: "42704477"
---
# <a name="office-scripts-api-reference"></a>Office Scripts-API-Referenz

Mit der Office Scripts-API können Sie häufige Aufgaben in Excel im Internet automatisieren. In dieser Referenzdokumentation erfahren Sie mehr über die Klassen, Methoden und anderen Typen, die für Ihre Skripts verfügbar sind. Alle Objekte, auf die über Office-Skripts zugegriffen werden kann, finden Sie im Inhaltsverzeichnis auf der linken Seite.

## <a name="common-classes"></a>Allgemeine Klassen

In der folgenden Liste werden die Grundlagen des Office Scripts-Objektmodells aufgeschlüsselt. Dadurch werden die allgemeinen Klassen und ihre Beziehung miteinander dargestellt.

- Eine [Arbeitsmappe](/javascript/api/office-scripts/excel/excel.workbook) enthält ein oder mehrere [Arbeitsblätter](/javascript/api/office-scripts/excel/excel.worksheet) in einer [worksheetcollection](/javascript/api/office-scripts/excel/excel.worksheetcollection).
- Ein [Arbeitsblatt](/javascript/api/office-scripts/excel/excel.worksheet) ermöglicht den Zugriff auf Zellen über [Bereichs](/javascript/api/office-scripts/excel/excel.range) Objekte.
- Ein [Bereich](/javascript/api/office-scripts/excel/excel.range) stellt eine Gruppe von zusammenhängenden Zellen dar.
- [Bereiche](/javascript/api/office-scripts/excel/excel.range) werden zum Erstellen und Platzieren von [Tabellen](/javascript/api/office-scripts/excel/excel.table), [Diagrammen](/javascript/api/office-scripts/excel/excel.chart), [Formen](/javascript/api/office-scripts/excel/excel.shape)und anderen Daten Visualisierungs-oder Organisationsobjekten verwendet.
- Ein [Arbeitsblatt](/javascript/api/office-scripts/excel/excel.worksheet) enthält Auflistungen dieser Datenobjekte (beispielsweise eine [chartcollection](/javascript/api/office-scripts/excel/excel.chartcollection)), die im einzelnen Blatt vorhanden sind.
- [Arbeitsmappen](/javascript/api/office-scripts/excel/excel.workbook). enthält Auflistungen einiger dieser Datenobjekte (beispielsweise eine [tablecollection](/javascript/api/office-scripts/excel/excel.tablecollection)) für die gesamte [Arbeitsmappe](/javascript/api/office-scripts/excel/excel.workbook).

Weitere Informationen zum Office Scripts-Objektmodell finden Sie unter [Scripting Fundamentals for Office scripts in Excel im Internet](/office/dev/scripts/develop/scripting-fundamentals) .

## <a name="see-also"></a>Siehe auch

- [Informationen zu Office-Skripts](/office/dev/scripts/overview/excel)
- [Aufzeichnen, bearbeiten und Erstellen von Office-Skripts in Excel im Internet](/office/dev/scripts/tutorials/excel-tutorial)
- [Grundlegendes zur Skripterstellung für Office-Skripts in Excel im Internet](/office/dev/scripts/develop/scripting-fundamentals)
