# Cell-Cell-Communication

### Mast Cell Communication During Inflammation

### Biological Question

How does a mast cell communicate with other cells during inflammation?

## Chosen sender cell and biological context

| **Item**               | **Answer** |
| ---------------------- | ---------- |
| **Sender cell**        | Mast cell |
| **Biological context** | Inflammation |
| **Main purpose**       |Regulation of inflammatory and immune responses through communication with other cells|

## Candidate ligand and evidence for sender-cell expression

| **Item**            | **Information** |
| ------------------- | -------------- |
| Sender cell         | Mast cell |
| Candidate gene      | IL13 |
| Protein name        | Interleukin-13 |
| Expression evidence | The Human Protein Atlas identifies IL-13 as a secreted protein and provides protein-level evidence for the human IL-13 protein. Mast cells are also included among the cell types with enhanced IL13 expression. |
| Source              | https://www.proteinatlas.org/ENSG00000169194-IL13 |

## Receptor and receiver cell with supporting evidence

| **Item** | **Information** |
|----------|-----------------|
| Ligand / Signaling molecule | IL-13 (Interleukin-13), encoded by *IL13* |
| Receptor | IL4R + IL13RA1 (type II IL-4 receptor complex) |
| Receiver cell | Neutrophil |
| Receptor expression evidence | The Human Protein Atlas shows IL4R and IL13RA1 expression associated with neutrophils, supporting the presence of the receptor components in the receiver cell. |
| Receiver-cell evidence | A study using human neutrophils showed that IL-13 can affect neutrophil functions, including migration and extracellular trap formation. |
| Biological context | Inflammation |
| Signaling context | Inflammation; IL-13 signaling through the type II IL-4 receptor can activate downstream signaling pathways in neutrophils and influence inflammatory cell functions. |
| Supporting source Omnipath | [IL13 – ligand](https://explore.omnipathdb.org/search?q=IL13%2C&tab=intercell&species=9606&parents=ligand), [IL4R – receptor](https://explore.omnipathdb.org/search?q=IL4R%2C&tab=intercell&species=9606&parents=receptor), [IL13RA1 – receptor](https://explore.omnipathdb.org/search?q=IL13RA1%2C&tab=intercell&species=9606&parents=receptor) |
| Supporting source HPA | [IL4R](https://www.proteinatlas.org/ENSG00000077238-IL4R), [IL13RA1](https://www.proteinatlas.org/ENSG00000131724-IL13RA1) |
| Supporting source: peer-reviewed study | Impellizzieri et al. (2019), *IL-4 receptor engagement in human neutrophils impairs their migration and extracellular trap formation*. (https://www.sciencedirect.com/science/article/abs/pii/S0091674919302039#preview-section-abstract)|

## IntAct Validation

| **Item** | **Information** |
|----------|-----------------|
| **Protein pair** | IL13RA1 – IL4R |
| **IntAct accession** | EBI-1645096 |
| **Interaction type** | Direct interaction |
| **Detection method** | Isothermal titration calorimetry (ITC) |
| **Experimental setting** | In vitro |
| **Species** | Homo sapiens |
| **MI Score** | 0.56 |
| **Publication** | LaPorte et al. (2008), *Molecular and structural basis of cytokine receptor pleiotropy in the interleukin-4/13 system* |
| **Publication reference** | PMID: 18243101 |
| **Evidence conclusion** | Supports a direct physical interaction between IL13RA1 and IL4R in the IL-13 receptor complex. |

**IL13RA1 and IL4R** are what I chose because they are receptor components involved in the proposed IL-13 signaling pathway. Since IL-13 is the signaling molecule in my model, examining these receptor components helps provide experimental evidence for how IL-13 can signal through its receptor complex. The IntAct record EBI-1645096 reports a direct interaction between IL13RA1 and IL4R detected using isothermal titration calorimetry (ITC). The record also describes that IL-13 first binds IL13RA1, after which the IL-13/IL13RA1 complex recruits IL4Rα. This supports the receptor portion of my proposed signaling model, although the experiment was performed in vitro and does not by itself demonstrate the complete mast cell-to-neutrophil signaling pathway.

**Source:** [IntAct – EBI-1645096](https://www.ebi.ac.uk/intact/details/interaction/EBI-1645096)
