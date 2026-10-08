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

## Final model and 150–250 word interpretation

<img width="1102" height="641" alt="05_final_model" src="https://github.com/user-attachments/assets/3454f1fd-3d29-439f-b062-c7f91c2de3d1" />

The proposed model describes how a mast cell may communicate with a neutrophil during inflammation through IL-13 signaling. The mast cell acts as the sender cell and releases IL-13, which first binds IL13RA1 and then allows IL4Rα to become part of the receptor complex. Receptor activation can initiate intracellular signaling involving JAK-STAT-related components, including JAK1/TYK2 and STAT6, which may lead to changes in neutrophil activity. Evidence from the Human Protein Atlas supports the presence of IL4R and IL13RA1 in neutrophils, while OmniPath identifies IL13 as a secreted ligand and IL4R and IL13RA1 as receptor components. The STRING analysis showed functional associations related to cytokine-mediated signaling, JAK-STAT signaling, and interleukin-4 and interleukin-13 signaling. IntAct also provided experimental evidence for a direct interaction between IL13RA1 and IL4R within an IL-13 receptor complex. Together, these findings support the major components of the proposed pathway. However, the complete mast cell-to-neutrophil communication pathway has not been directly demonstrated in one experiment, so the connection between the different pieces of evidence remains a biologically supported model rather than a confirmed complete pathway.

## Questions and Answers

**1. What sender cell did you choose, and in what tissue or biological context does it act?**

I chose a **mast cell** as the sender cell. Mast cells are immune cells that participate in **inflammatory responses** and can communicate with other cells through released signaling molecules.

**2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?**

The signaling molecule I identified is **IL-13 (Interleukin-13)**. IL-13 was identified as a candidate after examining mast-cell-associated information in the Human Protein Atlas, and published studies have demonstrated IL-13 production and release by activated human mast cells.

**3. What receptor receives the signal, and which receiver cell did you select?**

The receptor system is **IL4R + IL13RA1 (type II IL-4 receptor complex)**, and I selected the **neutrophil** as the receiver cell. Human Protein Atlas data support the presence of these receptor components in neutrophils.

**4. What type of cell-to-cell signaling is represented?**

The proposed signaling is **paracrine signaling** because IL-13 is released by the mast cell and may act on another nearby cell, such as a neutrophil.

**5. Which proteins in your STRING network appear most relevant to the receptor-associated response? Explain briefly.**

The most relevant proteins in the network are **IL4R, IL13RA1, and SOCS5**. IL4R and IL13RA1 form the receptor system associated with IL-13 signaling, while SOCS5 is associated with the regulation of cytokine signaling. The STRING network also includes other cytokine-related proteins, but STRING associations do not by themselves establish direct binding or downstream direction.

**6. What enriched pathway or biological process is consistent with your proposed mechanism?**

The most relevant enriched results are the **JAK-STAT signaling pathway**, **cytokine-mediated signaling pathway**, and **Interleukin-4 and Interleukin-13 signaling**. These results are consistent with the proposed IL-13 receptor mechanism.

**7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?**

IntAct record **EBI-1645096** reports a **direct interaction between IL13RA1 and IL4R** detected using **isothermal titration calorimetry (ITC)** in an in vitro setting. The record also describes IL-13 binding to IL13RA1 followed by recruitment of IL4Rα to the complex.

**8. Which parts of your final model are strongly supported, and which parts remain an inference?**

The identification of IL-13 as a mast-cell-associated signaling molecule, the IL4R/IL13RA1 receptor system, the receptor interaction evidence from IntAct, and the involvement of cytokine and JAK-STAT signaling are supported by database and published evidence. The complete **mast cell → IL-13 → neutrophil** communication pathway remains an inference because the entire chain has not been directly demonstrated in a single experiment.

**9. What cellular response is expected in the receiver cell, and why?**

The expected response is **changes in neutrophil functions, including migration and extracellular trap (NET) formation**. Published research using human neutrophils showed that IL-13 can influence these functions, supporting the proposed cellular response.

## References and database links

**Human Protein Atlas (HPA):**  
[IL13](https://www.proteinatlas.org/ENSG00000169194-IL13)  
[IL4R](https://www.proteinatlas.org/ENSG00000077238-IL4R)  
[IL13RA1](https://www.proteinatlas.org/ENSG00000131724-IL13RA1)

**OmniPath:**  
[IL13 – ligand](https://explore.omnipathdb.org/search?q=IL13%2C&tab=intercell&species=9606&parents=ligand)  
[IL4R – receptor](https://explore.omnipathdb.org/search?q=IL4R%2C&tab=intercell&species=9606&parents=receptor)  
[IL13RA1 – receptor](https://explore.omnipathdb.org/search?q=IL13RA1%2C&tab=intercell&species=9606&parents=receptor)

**STRING:**  
[STRING protein-association network](https://string-db.org/)

**IntAct:**  
[IntAct interaction EBI-1645096](https://www.ebi.ac.uk/intact/details/interaction/EBI-1645096)

**Peer-reviewed sources:**  
McLeod JAJA, Baker BN, Ryan JJ. *Mast cell production and response to IL-4 and IL-13.* Cytokine. 2015;75(1):57–61.  
Impellizzieri D, et al. *IL-4 receptor engagement in human neutrophils impairs their migration and extracellular trap formation.* J Allergy Clin Immunol. 2019;144(1):267–279.e4.
