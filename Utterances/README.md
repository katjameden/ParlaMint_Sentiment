
# Utterance-level sentiment annotation

This section contains annotation setup for manual utterance-level sentiment annotation and inter-annotator agreement analysis.

## Directories

**[Annotation_Main](./Annotation_Main):** Annotations and inter-annotator agreement analysis for the main annotation phases (1,000 instances).

**[Annotations_Tests](./Annotations_Tests)**: Test annotation rounds conducted to refine the annotation process, together with their results.

> **Note:** We initially used Cohen's &kappa; as the primary inter-annotator agreement metric. Later, we switched to Krippendorff's &alpha; to enable direct comparison with agreement scores from the sentence-level annotations. As a result, the Jupyter notebooks in the ``Annotations_Main or _Tests``directories still include calculations based on Cohen's &kappa;. The calculations with Krippendorff's &alpha; are done in the ``Inter-annotator_agreement.ipynb`` Jupyter Notebook.

** The [Inter-annotator_agreement.ipynb](./Inter-annotator_agreement.ipynb) notebook reports inter-annotator agreement using Krippendorff's &alpha; for all annotation phases, both the 6-class and 3-class annotation schemes, and for both the full dataset and the non-procedural subset (i.e., instances where the speaker is a regular speaker rather than the chair).

**[Datasets](./Datasets)**: Annotation samples used during the test and main annotation phases.

**[Processing](./Processing/)**: Jupyter notebooks and supporting scripts used for data conversion and sampling.

Visualisations and inter-annotator agreement results are available in **[Figures](./Figures/)**: and **[Tables](./Tables/)** folders.

