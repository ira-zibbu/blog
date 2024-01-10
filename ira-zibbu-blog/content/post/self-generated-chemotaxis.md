---
title: "Aatmanirbhar: Self-Generated Chemoattractant Gradients Drive Robust Chemotaxis"
date: 2023-05-09T22:44:12+05:30
---

Chemotaxis is the movement of cells along a chemical gradient. From *Escherichia coli* to *Homo sapiens*, it is a highly conserved behaviour that enables directed cell movement. For motile unicellular organisms, chemotaxis enables movement towards resources like nutrition and space and away from toxins or competitors. For multicellular organisms like metazoans, chemotaxis drives coordinated cell movements during development, such as gastrulation, germ cell migration, and neural crest cell migration. Immune cells like leukocytes use chemotaxis to move towards sites of infection. Defects in chemotaxis have been associated with diseases such as craniofacial disorders (defective neural crest cell migration) and autoimmunity (defective leukocyte chemotaxis) [1].

Traditionally, chemotaxing cells are viewed as passive responders that only sense but do not affect an externally imposed chemoattractant gradient. The self-generated chemoattractant gradient model represent the opposite view, where a group of migrating cells produce a local gradient to enable autonomous movement. In reality, most cell migration occurs through an intermediate mechanism, where they locally modify an external gradient to some extent by endocytosis or enzymatic degradation of the attractant [1]. Most evidence for self-generated chemoattractant gradients comes from studies on unicellular organisms, while very few examples have been found in animals. In the slime mould *Dictyostelium discoideum*, cAMP is produced in a cell density-dependent manner, allowing chemotaxis to drive dispersal and prevent crowding. The lateral line primordium of zebrafish generates a local sdf-1 gradient for migration, and mesendoderm cells in zebrafish embryos migrate in response to a self-generated toddler gradient [3][4]. There is also evidence that a self-generated gradient drives germ cell migration in Drosophila embryos [2].

Self-generated chemoattractant gradients can be created by localised attractant depletion. In bacteria, cells consume nutrients in their immediate surroundings, creating a local gradient that drives movement toward other regions with higher concentrations of nutrients. In lateral line primordium in zebrafish, the posterior end of the tissue acts as a sink for sdf-1, creating a gradient directed towards the leading edge of the cell cluster. Self-generated gradients can also be produced by autorepellant secretion, which creates a gradient where concentration is highest where cell numbers are highest. For example, quorum-sensing molecules in *Helicobacter pylori* enable the cells to disperse from regions of high cell density and competition [2].

Self-generated chemoattractant gradients are hard to detect, and their advantages over externally imposed gradients are harder to demonstrate experimentally. Here, computational simulations of migrating cells become essential, and these studies have revealed some key differences. During chemotaxis, cell surface receptors detect the attractant and operate in a restricted concentration range around the receptor dissociation constant *Kd*. If the concentration is too high, all receptors become saturated and cannot respond to changes in concentration. If the concentration is too low, an insufficient signal is generated. Therefore, in externally imposed gradients, this restricted concentration range must be spread across the entire length of migration, creating a shallow and ‘unreadable’ gradient. In contrast, self-generated gradients are more robust for long-distance migration as they only need to create a local gradient, which can be steeper and drive stronger chemotactic response. Self-generated gradients also improve the dynamic range of attractant sensing by two orders of magnitude. In externally imposed gradients, at high concentrations, cells are overwhelmed and stall in one location. In self-generated gradients, if a region of high concentration is encountered, cells can endocytose/degrade the attractant, shifting the concentration gradient to a readable range after a time delay. This detection range is further improved if the degradation of the attractant is inducible and proportional to the local attractant concentration [1]. In cases where there is both a global and self-generated gradient of the same attractant, the local action of the cells can refine the gradient and make it more readable. For example, a linear external gradient can be locally refined to an exponential gradient to drive a stronger chemotactic response. 

Experiments with *Dictyostelium discoideum* have shown an additional benefit of self-generated gradients in allowing cells to gather information about regions without physically visiting them. This was demonstrated in mazes constructed in microfluidic devices with a homogeneous distribution of a chemoattractant. D. discoideum cells break down as the attractant as they enter the maze, and cells can identify which branches of a maze connect to the exit because fresh attractant diffuses in from them. In contrast, no additional attractant diffuses in dead-end branches [2]. This would not be possible if the cells did not locally break down the attractant. One shortcoming of self-generated gradients is that they fail to drive chemotaxis if cell populations are low. However, if the chemoattractant is also a mitogen (as with VEGF), self-generated gradients become robust to population drops [1].

The word *Aatmanirbhar* means ‘self-reliance’; this property of self-generated gradients makes them a robust method to drive directed cell movement. Despite the theoretically predicted advantages of self-generated chemoattractant gradients, very few instances of their occurrence in animals have been described. The dynamic and unstable nature of these gradients makes it difficult to visualise them. Fluorescently tagged chemoattractants can be used for this purpose. However, it is challenging to detect differential uptake levels across a group of migrating cells or distinguish between uptake leading to signalling and uptake leading to degradation without signalling [2]. Tandem fluorescent tags that enable visualisation of receptor age and turnover have been successfully used to demonstrate self-generated gradients [4]. As experimental techniques improve, more cases of self-generated gradients will be discovered. 

### References
1. Tweedy, L. & Insall, R. H. Self-Generated Gradients Yield Exceptionally Robust Steering Cues. Frontiers in Cell and Developmental Biology (2020)
2. Insall, R. H., Paschke, P. & Tweedy, L. Steering yourself by the bootstraps: how cells create their own gradients for chemotaxis. Trends in Cell Biology (2022)
3. Stock, J., Kazmar, T., Schlumm, F., Hannezo, E. & Pauli, A. A self-generated Toddler gradient guides mesodermal cell migration. Science Advances (2022)
4. Donà, E. et al. Directional tissue migration through a self-generated chemokine gradient. Nature (2013)

*This article was originally written for a class*
