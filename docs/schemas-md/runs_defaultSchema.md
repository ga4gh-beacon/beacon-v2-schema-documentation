|Field | description | type | properties | example | enum|
| ---| ---| ---| ---| ---| --- |
| [biosampleId](./obj/biosampleId.md) | Reference to the biosample ID. | string | NA | 008dafdd-a3d1-4801-8c0a-8714e2b58e48 | NA|
| [id](./obj/id.md) | Run ID. | string | NA | SRR10903401 | NA|
| [individualId](./obj/individualId.md) | Reference to the individual ID. | string | NA | TCGA-AO-A0JJ | NA|
| [info](./obj/info.md) | Placeholder to allow the Beacon to return any additional information that is necessary or could be of interest in relation to the query or the entry returned. It is recommended to encapsulate additional informations in this attribute instead of directly adding attributes at the same level than the others in order to avoid collision in the names of attributes in future versions of the specification. | object | NA | NA | NA|
| [libraryLayout](./obj/libraryLayout.md) | Ontology value for the library layout e.g "PAIRED", "SINGLE" #todo add Ontology name? | string | NA | NA | PAIRED, SINGLE|
| [librarySelection](./obj/librarySelection.md) | Selection method for library preparation, e.g "RANDOM", "RT-PCR" | string | NA | RANDOM, RT-PCR | NA|
| [librarySource](./obj/librarySource.md) | Definition of an ontology term. | object | [id](./obj/id.md), [label](./obj/label.md) | NA | NA|
| [libraryStrategy](./obj/libraryStrategy.md) | Library strategy, e.g. "WIG'S" | string | NA | NA | NA|
| [platform](./obj/platform.md) | General platform technology label. It SHOULD be a subset of the platformModel and used only for query convenience, e.g. "return everything sequenced with Illimuna", where the specific model is not relevant | string | NA | Illumina, Oxford Nanopore, Affymetrix | NA|
| [platformModel](./obj/platformModel.md) | Definition of an ontology term. | object | [id](./obj/id.md), [label](./obj/label.md) | NA | NA|
| [runDate](./obj/runDate.md) | Date at which the experiment was performed. | string | NA | NA | NA|
