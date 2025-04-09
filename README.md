# OpenCloning cloning workshop

This is a workshop in which attendees will choose scientific papers where plasmids or genomes were engineered, and they will try to reproduce _in silico_ the cloning process using [OpenCloning](https://opencloning.org).

Despite DNA engineering being used in many fields in the biological sciences, there is a lack of standards to document cloning and genome engineering. Consequently, it is often difficult to reproduce the cloning process of a scientific paper. During this workshop, we will use [OpenCloning](https://opencloning.org) to try to reproduce the cloning process of a scientific paper.
* If you manage to reproduce the cloning, it will be deposited in this repository for others to be able to easily understand the cloning process.
* If not, your submission will help create a dataset to raise awareness of the need for standards in cloning.

## Prerequisites

- Create a [GitHub](https://github.com) account. GitHub is a website that allows you to store and manage code, but we also use it to manage submissions by workshop participants.
- Create an [ORCID](https://orcid.org) account. ORCID is a persistent digital identifier for you as a researcher that can be used for attribution purposes (publications, datasets, this workshop, etc).


## Introduction to OpenCloning

OpenCloning is a web application where you can design a cloning strategy through an intuitive web interface or programmatically, and provides a standardised data model to represent cloning strategies. Users can:

* 📡 Import plasmid sequences from repositories like AddGene and genome sequences from NCBI using unique identifiers and genome coordinates.
* 🧬 Plan cloning and design primers using common techniques (Gibson, golden gate, gateway, etc.).
* 🦠 Plan strain and cell line engineering via CRISPR, homologous recombination, etc.
* 📜 Archive the entire cloning history as a json file (data model uses the modelling framework LinkML)
* 🤖 Automate repetitive cloning and primer design using scripts or web forms.

[This example](https://opencloning.org/?source=example&example=homologous_recombination.json) shows cloning history to construct a deletion allele via homologous recombination in yeast.

To get started, see the [demo video](https://www.youtube.com/watch?v=n0hedzvpW88&t=158s&ab_channel=Genestorian) and try the [hosted app](https://opencloning.org/).

## Workshop

> NOTE: If submitting in a language other than English would make things easier for you, you can fill your submission in your language of choice.

Before getting started, it's good to have a look at the submission form that you will have to fill when you finish with a paper. It shows the information you will have to provide about the cloning process. To access it, you can go to the [create an issue](https://github.com/OpenCloning/cloning_workshop/issues/new?template=submission_en.yml). If you want to fill it along while you are working on the paper, you can work on this [google doc template](). Make a copy of that document, and fill the information as you go along. Then you can make a submission by [creating an issue](https://github.com/OpenCloning/cloning_workshop/issues/new?template=submission_en.yml).


### Choose a paper to reproduce

You can get a paper of your choice or pick one from the [list](https://docs.google.com/spreadsheets/d/1UuljFV8-FEAFT3jnHevuTmERE0VNCNRSH693Y2Uq7Ag/edit?usp=sharing).

### Identify the plasmids or alleles engineered in the paper

From the text in the paper, identify which plasmids or alleles were created for the research performed, and take note of their names and identifiers if they have them.

### Identify the methods section that describes the cloning process

* Identify the section that describes the cloning process (which existing plasmids were used, what primers were designed, from which genome regions were genes amplified, etc.).
* Copy the text from the paper that describes this process into your google doc template.
* If there are tables in the paper text listing primers, copy those as well.
* Download and the supplementary files that are relevant for cloning (sequences, spreadsheets or pdf with primer lists, etc.).

### Try to reproduce in OpenCloning

* Start by loading the starting sequences and primers into OpenCloning, then follow the cloning process described in the paper.
* Sometimes, you may have to make some assumptions, or find sequences online that you cannot be 100% sure are the same as the ones in the paper, take note of the assumptions you made in the template.
* If something is missing, take note of what would have been needed to reproduce the cloning process in OpenCloning.
* If you manage to reproduce the cloning process, download it as a json file. You will have to upload it in the form.

### Submit your work

When you have finished, simply [create an issue](https://github.com/OpenCloning/cloning_workshop/issues/new?template=submission_en.yml) and fill the form.





