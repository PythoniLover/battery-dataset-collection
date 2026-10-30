[README.md](https://github.com/user-attachments/files/34189286/README.md)
# battery-dataset-collection
A curated directory of 41 publicly shared battery dataset resources, with original download links and associated papers.
# Battery Dataset Collection

A curated directory of 41 publicly shared battery dataset resources, with original download links and associated paper information where provided.

The collection covers battery aging and cycle life, health estimation, fault detection, and real-world vehicle operation. It brings together resources from universities, research institutes, and individual contributors.

## Contents

- [About this collection](#about-this-collection)
- [Dataset directory](#dataset-directory)
- [Access and source notes](#access-and-source-notes)
- [Contributing](#contributing)
- [Acknowledgments and terms](#acknowledgments-and-terms)
- [Full English translation](docs/Battery_Dataset_Collection_EN.md)
- [English Word document](docs/Battery_Dataset_Collection_EN.docx)

## About this collection

I compiled this directory while working on large AI models for lithium-ion batteries. Access to high-quality battery data can be difficult for researchers, students, and algorithm developers, so I collected publicly shared resources from academic papers and online platforms and organized their original links in one place.

The source compilation describes the linked datasets as totaling more than 500 GB. This is the compiler's estimate, rather than an independently verified measurement. This repository contains the directory and its documentation; the datasets are hosted by their original providers.

The full English translation preserves the source document's introduction, all 41 entries, and closing remarks. This README adapts that material for GitHub and adds notes about missing or ambiguous metadata.

## Dataset directory

Numbering follows the source document. An em dash (—) means that the source did not provide that field. Release years, publisher labels, links, and paper information are reproduced from the source; they have not been independently validated against the hosting sites. Battery type is specified only for entries 1 and 5.

| Index | Release year | Publisher | Data link | Paper | Battery type |
| --- | --- | --- | --- | --- | --- |
| 1 | 2019 | MIT/Stanford | [https://data.matr.io/1/](<https://data.matr.io/1/>) | Data-driven prediction of battery cycle life before capacity degradation | LFP/1.1Ah |
| 2 | — | CALCE | [https://calce.umd.edu/battery-data](<https://calce.umd.edu/battery-data>) | — | — |
| 3 | — | NASA | [https://www.nasa.gov/intelligent-systems-division/discovery-and-systems-health/pcoe/pcoe-data-set-repository/](<https://www.nasa.gov/intelligent-systems-division/discovery-and-systems-health/pcoe/pcoe-data-set-repository/>) | — | — |
| 4 | — | Oxford | [https://battery-intelligence-lab.github.io/data-and-code/](<https://battery-intelligence-lab.github.io/data-and-code/>) | — | — |
| 5 | 2022 | Huazhong University of Science and Technology (HUST) | [https://data.mendeley.com/datasets/nsc7hnsg4s/2](<https://data.mendeley.com/datasets/nsc7hnsg4s/2>) | Real-time personalized health status prediction of lithium-ion batteries using deep transfer learning | LFP/1.1Ah |
| 6 | 2024 | Tsinghua University | [https://1drv.ms/f/s!AuAiTLYEMUuKbLRMwP_d3RbUFs4?e=LL44SK](<https://1drv.ms/f/s!AuAiTLYEMUuKbLRMwP_d3RbUFs4?e=LL44SK>) | Towards real-world state of health estimation,Part 1:Cell-level method using lithium-ion battery laboratory data | — |
| 7 | 2024 | Tsinghua University | [https://data.mendeley.com/datasets/mcsh4hnb8b/1](<https://data.mendeley.com/datasets/mcsh4hnb8b/1>) | Towards Real-World State of Health Estimation:Part 2,System Level Method Using Electric Vehicle Field Data | — |
| 8 | 2025 | Shandong University | [https://data.mendeley.com/datasets/dbwsn6t96j/1](<https://data.mendeley.com/datasets/dbwsn6t96j/1>) | The Dataset for: Large Battery Model for Multi-State Co-estimation and Intelligent Recommendation using Mixed Data Sources | — |
| 9 | 2025 | Shandong University | [https://zenodo.org/records/14859405](<https://zenodo.org/records/14859405>) | Deep sorting of reused batteries for enabling long-term consistency grouping with unknown prior conditions | — |
| 10 | 2025 | Shanghai Jiaotong University | [https://data.mendeley.com/datasets/vfd3f3srfk/2](<https://data.mendeley.com/datasets/vfd3f3srfk/2>) | Battery health prognosis in data-deficient practical scenarios via reconstructed voltage-based machine learning | — |
| 11 | 2022 | Tongji University | [https://zenodo.org/records/6405084](<https://zenodo.org/records/6405084>) | Data-driven capacity estimation of commercial lithium-ion batteries from voltage relaxation | — |
| 12 | 2024 | Xi'an Jiaotong University | [https://zenodo.org/records/10963339](<https://zenodo.org/records/10963339>) | Physics-informed neural network for lithium-ion battery degradation stable modeling and prognosis | — |
| 13 | 2025 | Chongqing University | [https://ivstskl.changan.com.cn/?p=2697](<https://ivstskl.changan.com.cn/?p=2697>) | Multi-modal framework for battery state of health evaluation using open-source electric vehicle data | — |
| 14 | 2026 | University of Michigan | [https://zenodo.org/records/17654407](<https://zenodo.org/records/17654407>) | Discovery Learning predicts battery cycle life from minimal experiments | — |
| 15 | 2021 | RWTH | [https://publications.rwth-aachen.de/record/818642](<https://publications.rwth-aachen.de/record/818642>) | — | — |
| 16 | 2021 | Stanford University | [https://data.mendeley.com/datasets/68jkb7x6t4/3](<https://data.mendeley.com/datasets/68jkb7x6t4/3>) | — | — |
| 17 | 2021 | Massachusetts Institute of Technology; Beijing Institute of Technology | [https://data.mendeley.com/datasets/kw34hhw7xg/3](<https://data.mendeley.com/datasets/kw34hhw7xg/3>) | Battery Degradation Prediction Against Uncertain Future Conditions with Recurrent Neural Network Enabled Deep Learning | — |
| 18 | 2024 | Beijing Institute of Technology | [https://zenodo.org/records/14576042](<https://zenodo.org/records/14576042>) | Smart Health Evaluation for Lithium-Ion Battery With Super-Short-Segment Charging | — |
| 19 | 2023 | Aalborg | [https://data.mendeley.com/datasets/yz4pttm73n/2](<https://data.mendeley.com/datasets/yz4pttm73n/2>) | — | — |
| 20 | 2025 | University of Bayreuth | [https://zenodo.org/records/15755725](<https://zenodo.org/records/15755725>) | — | — |
| 21 | 2024 | Technische Universität Darmstadt | [https://zenodo.org/records/13715694](<https://zenodo.org/records/13715694>) | Gaussian Process-based Online Health Monitoring and Fault Analysis of Lithium-Ion Battery Systems from Field Data Cell Report Physical Science | — |
| 22 | 2023 | Karlsruhe Institute of Technology | [https://www.radar-service.eu/radar/de/dataset/uabgQSNJZVAhKHgS#](<https://www.radar-service.eu/radar/de/dataset/uabgQSNJZVAhKHgS>) | FOBSS: Monitoring Data from a Modular Battery System | — |
| 23 | 2024 | Karlsruhe Institute of Technology | [https://radar.kit.edu/radar/en/dataset/kww7jv8ajuvchcah](<https://radar.kit.edu/radar/en/dataset/kww7jv8ajuvchcah>) | Comprehensive battery aging dataset: capacity and impedance fade measurements of a lithium-ion NMC/C-SiO cell | — |
| 24 | 2023 | Abhishek Bansal | [https://data.mendeley.com/datasets/364p44vtj2/1](<https://data.mendeley.com/datasets/364p44vtj2/1>) | — | — |
| 25 | 2025 | National Renewable Energy Laboratory | [https://data.mendeley.com/datasets/ksc4sv46x6/1](<https://data.mendeley.com/datasets/ksc4sv46x6/1>) | Searching for a Pulse: Evaluating the Use of Rapid DC Pulses for Diagnosing Battery Health, State-of-Charge, and Safety | — |
| 26 | 2025 | Seoul National University | [https://data.mendeley.com/datasets/zn82y35zr8/4](<https://data.mendeley.com/datasets/zn82y35zr8/4>) | — | — |
| 27 | 2025 | East China Normal University | [https://figshare.com/articles/dataset/Datasets_of_three_downstream_tasks_in_LLiM/28260095](<https://figshare.com/articles/dataset/Datasets_of_three_downstream_tasks_in_LLiM/28260095>) | Large lithium-ion battery model for secure shared electric bike battery in smart cities | — |
| 28 | 2020 | McMaster University | [https://data.mendeley.com/datasets/9xyvy2njj3/2](<https://data.mendeley.com/datasets/9xyvy2njj3/2>) | — | — |
| 29 | 2020 | McMaster University | [https://data.mendeley.com/datasets/b5mj79w5w9/2](<https://data.mendeley.com/datasets/b5mj79w5w9/2>) | — | — |
| 30 | 2020 | McMaster University | [https://data.mendeley.com/datasets/cp3473x7xv/3](<https://data.mendeley.com/datasets/cp3473x7xv/3>) | — | — |
| 31 | 2024 | University of Limerick | [https://zenodo.org/records/15657829](<https://zenodo.org/records/15657829>) | Advanced machine learning techniques for State-of-Health estimation in lithium-ion batteries: A comparative study | — |
| 32 | 2021 | Univ. of Colorado Colorado Springs | [https://data.mendeley.com/datasets/p8kf893yv3/1](<https://data.mendeley.com/datasets/p8kf893yv3/1>) | Lithium-Ion Battery Charging Control Using a Coupled Electro-Thermal Model and Model Predictive Control | — |
| 33 | 2024 | Munich University of Applied Sciences | [https://figshare.com/articles/dataset/Multi-Stage_Lithium_Ion_Battery_Aging_Study/25975315](<https://figshare.com/articles/dataset/Multi-Stage_Lithium_Ion_Battery_Aging_Study/25975315>) | A multi-stage lithium-ion battery aging dataset using various experimental design methodologies | — |
| 34 | 2018 | University of Wisconsin Madison; McMaster University | [https://data.mendeley.com/datasets/wykht8y7tg/1](<https://data.mendeley.com/datasets/wykht8y7tg/1>) | — | — |
| 35 | 2025 | Bilkent University | [https://zenodo.org/records/14606633](<https://zenodo.org/records/14606633>) | — | — |
| 36 | 2023 | Hong Kong University of Science and Technology | [https://drive.google.com/drive/folders/1wMoXu-G9zC6CPyo-t742XNEkHYbPnWmb](<https://drive.google.com/drive/folders/1wMoXu-G9zC6CPyo-t742XNEkHYbPnWmb>) | Detecting Abnormality of Battery Lifetime from First-Cycle Data Using Few-Shot Learning | — |
| 37 | 2024 | Tsinghua University | [https://zenodo.org/records/10715209](<https://zenodo.org/records/10715209>) | Non-destructive degradation pattern decoupling for early battery trajectory prediction via physics-informed learning | — |
| 38 | 2024 | University of Pavia; University of Trieste | [https://data.mendeley.com/datasets/ycx459r5c3/2](<https://data.mendeley.com/datasets/ycx459r5c3/2>) | A dataset for large prismatic lithium-ion battery cells (CALB L148N58A): Comprehensive characterization and real-world driving cycles | — |
| 39 | 2022 | Chang’an University | [https://github.com/BatICM/battery-charging-data-of-on-road-electric-vehicles](<https://github.com/BatICM/battery-charging-data-of-on-road-electric-vehicles>) | Journal of Energy Chemistry 99 (2024) 681–691 Contents lists available at ScienceDirect Journal of Energy Chemistry journal homepage: | — |
| 40 | 2025 | The Hong Kong University of Science and Technology | [https://zenodo.org/records/19688272](<https://zenodo.org/records/19688272>) | BatteryLife:A Comprehensive Dataset and Benchmark for Battery Life Prediction | — |
| 41 | 2023 | Carnegie Mellon University | [https://kilthub.cmu.edu/articles/dataset/eVTOL_Battery_Dataset/14226830/2](<https://kilthub.cmu.edu/articles/dataset/eVTOL_Battery_Dataset/14226830/2>) | A battery dataset for electric vertical takeoff and landing aircraft | — |

## Access and source notes

- Follow each original data link for download instructions, dataset versions, experimental conditions, papers, and any access requirements. Some links lead to institutional collections rather than individual datasets.
- Two major source portals are [Mendeley Data](https://data.mendeley.com/) and [Zenodo](https://zenodo.org/).
- Users in mainland China may need additional network-access tools to reach some of the linked sites, as noted in the source document.
- Entries 6 and 7 share the release year 2024 and publisher Tsinghua University through merged cells in the source. These shared values are repeated in both rows here for readability.
- Entry 21 includes the text “Cell Report Physical Science” in the paper field. The source wording is retained pending confirmation.
- Entry 34 lists two institution names without a separator in the source. A separator has been added for readability; the attribution has not been independently verified.
- Entry 39 contains journal information and copied journal-page text rather than an identifiable paper title. The source text is retained pending clarification.
- Line breaks, spacing, and the “ﬁ” ligature have been normalized for readability. Original dataset URLs are preserved. Link availability has not been checked online for this draft.

## Contributing

Suggestions for new datasets, corrected metadata, updated links, and clearer descriptions are welcome through an issue or pull request. Please include:

- The original dataset URL and provider.
- The release year or version, if available.
- The associated paper, DOI, or citation, if available.
- Battery chemistry, capacity, test conditions, and access terms, if available.
- A brief explanation of the addition or correction.

This directory is a continuing community effort and does not claim to include every public battery dataset.

## Acknowledgments and terms

Thank you to all authors, institutions, and contributors who have made their battery datasets publicly available. Please cite the original datasets and papers when using their work.

Each linked dataset and paper remains subject to the terms provided by its respective owner. Public availability does not establish a common license across all resources. This directory does not grant permission to use or redistribute third-party data.

No repository license has been selected in this draft.
