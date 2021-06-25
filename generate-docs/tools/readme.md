# <a name="office-scripts-api-documentation-tools"></a>Office Skript-API-Dokumentationstools

Diese Tools unterstützen die Office SCripts-Dokumentation und das Team dahinter. Befolgen Sie diese Anweisungen, um die Tools in diesem Ordner auszuführen.

## <a name="coverage-tester"></a>Abdeckungstester

Dieses Tool bietet eine Übersicht über die Dokumentationsabdeckung für jede API. Jede API wird auf Die Qualität der Dokumentation und das Vorhandensein von Beispielcode überprüft. Die Qualitätsmetriken befinden sich noch in der Entwicklung.

Die Ausgabe dieses Tools ist eine `.csv` Datei.

### <a name="coverage-tester-instructions"></a>Anweisungen für abdeckungstester

1. Klonen oder verzweigen Sie das Repository.
1. Wechseln Sie in einem Befehlsfenster zu `/office-scripts-docs-reference/generate-docs/tools`
1. Ausführen `npm install`
1. Ausführen `npm run build`
1. Ausführen `node coverage-tester`
1. Öffnen Sie "API-Abdeckung Report.csv"
