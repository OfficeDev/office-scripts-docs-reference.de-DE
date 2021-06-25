# <a name="office-scripts-api-documentation-tools"></a><span data-ttu-id="6101f-101">Office Skript-API-Dokumentationstools</span><span class="sxs-lookup"><span data-stu-id="6101f-101">Office Scripts API Documentation Tools</span></span>

<span data-ttu-id="6101f-102">Diese Tools unterstützen die Office SCripts-Dokumentation und das Team dahinter.</span><span class="sxs-lookup"><span data-stu-id="6101f-102">These tools help support the Office SCripts documentation and the team behind it.</span></span> <span data-ttu-id="6101f-103">Befolgen Sie diese Anweisungen, um die Tools in diesem Ordner auszuführen.</span><span class="sxs-lookup"><span data-stu-id="6101f-103">Follow these instructions to run the tools in this folder.</span></span>

## <a name="coverage-tester"></a><span data-ttu-id="6101f-104">Abdeckungstester</span><span class="sxs-lookup"><span data-stu-id="6101f-104">coverage-tester</span></span>

<span data-ttu-id="6101f-105">Dieses Tool bietet eine Übersicht über die Dokumentationsabdeckung für jede API.</span><span class="sxs-lookup"><span data-stu-id="6101f-105">This tool gives an overview of the documentation coverage for each API.</span></span> <span data-ttu-id="6101f-106">Jede API wird auf Die Qualität der Dokumentation und das Vorhandensein von Beispielcode überprüft.</span><span class="sxs-lookup"><span data-stu-id="6101f-106">Each API is assessed for documentation quality and the presence of sample code.</span></span> <span data-ttu-id="6101f-107">Die Qualitätsmetriken befinden sich noch in der Entwicklung.</span><span class="sxs-lookup"><span data-stu-id="6101f-107">The quality metrics are still in development.</span></span>

<span data-ttu-id="6101f-108">Die Ausgabe dieses Tools ist eine `.csv` Datei.</span><span class="sxs-lookup"><span data-stu-id="6101f-108">The output of this tool is a `.csv` file.</span></span>

### <a name="coverage-tester-instructions"></a><span data-ttu-id="6101f-109">Anweisungen für abdeckungstester</span><span class="sxs-lookup"><span data-stu-id="6101f-109">coverage-tester Instructions</span></span>

1. <span data-ttu-id="6101f-110">Klonen oder verzweigen Sie das Repository.</span><span class="sxs-lookup"><span data-stu-id="6101f-110">Clone or fork the repo.</span></span>
1. <span data-ttu-id="6101f-111">Wechseln Sie in einem Befehlsfenster zu `/office-scripts-docs-reference/generate-docs/tools`</span><span class="sxs-lookup"><span data-stu-id="6101f-111">In a command window, go to `/office-scripts-docs-reference/generate-docs/tools`</span></span>
1. <span data-ttu-id="6101f-112">Ausführen `npm install`</span><span class="sxs-lookup"><span data-stu-id="6101f-112">Run `npm install`</span></span>
1. <span data-ttu-id="6101f-113">Ausführen `npm run build`</span><span class="sxs-lookup"><span data-stu-id="6101f-113">Run `npm run build`</span></span>
1. <span data-ttu-id="6101f-114">Ausführen `node coverage-tester`</span><span class="sxs-lookup"><span data-stu-id="6101f-114">Run `node coverage-tester`</span></span>
1. <span data-ttu-id="6101f-115">Öffnen Sie "API-Abdeckung Report.csv"</span><span class="sxs-lookup"><span data-stu-id="6101f-115">Open “API Coverage Report.csv”</span></span>
