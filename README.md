# Maurice Heide

I am an MSc student in Data Science at ETH Zurich. My work so far has been machine learning research: compressing large models into small and fast ones, training them on GPU clusters, and evaluating the results statistically.

**Selected work**

- MuCoDi ([paper](https://arxiv.org/abs/2607.05533), [code](https://github.com/KatherLab/MuCoDi)), shared first author with Tim Lenz, Best Paper Award at the MICCAI 2026 Workshop on Efficient Medical AI. We distill three pathology foundation models of up to 1.1B parameters into edge models with multi-teacher contrastive training. A 6.4M-parameter student, 99x smaller than the best teacher, comes within 0.9 AUROC points of it on external data.
- [mucodi-radiology](https://github.com/mooofna/mucodi-radiology) ([live demo](https://mooofna.github.io/mucodi-radiology/)), the code of my Bachelor thesis at Harvard Medical School and Massachusetts General Hospital. It distills CT foundation models into 14 compact 3D students, trained with PyTorch DDP on up to eight A100 GPUs (about 2,260 GPU-hours), and evaluates them with a tested package and patient-clustered bootstrap intervals. A web demo runs the students in the browser, on the visitor's own CPU.
- [singapore-urban-heat](https://github.com/mooofna/singapore-urban-heat) ([live map](https://mooofna.github.io/singapore-urban-heat/)), which grew out of a course project at NTU Singapore. It measures surface heat on a 200 m hexagon grid from every clear Landsat 8 and 9 scene since 2013, explains it with spatial lag, error and Durbin models, and publishes a web map that a scheduled workflow updates every month.

Before ETH I studied Computer Science at TU Dresden and worked at the EKFZ for Digital Health, Fraunhofer IVI and EY in Paris.

[Homepage](https://mooofna.github.io), [LinkedIn](https://www.linkedin.com/in/maurice-heide) and [Google Scholar](https://scholar.google.com/citations?user=x6GTx8kAAAAJ)

