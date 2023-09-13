## Selected projects in bioinformatics 

---

### GPRFinder: A tool for guiding the curation of genome-scale metabolic models through comparative genomics

GPRFinder is a homology-based tool for finding gene-reaction association rules of genes missing in Genome-scale Metabolic Models (GEMs). The tool compares the whole genome of your model (target)
versus the genome of a model from the BiGG database (template), and extracts bi-directional best hits (BBHs) with a provided PID threshold. It generates a table in CSV format containing the ID of the orthologous genes (target vs. template) with information on the reactions (Reaction ID, name, subsystem, and string) in which the template genes participate. This table can be used to accelerate gap-filling and curation processes of GEMs.

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/Bash-white?logo=GNUbash)](#)

[View repository](https://github.com/CarlosFocil/GPRFinder)

---
### Metatranscriptomic analysis of RNA-Seq data from a microbial consortium
In this project, I designed the bioinformatics methodology and workflow
for the study of the metatranscriptome of a microbial consortium. 
The general workflow consisted of the following steps:
RNA-seq reads processing -> De novo metatranscriptome assembly ->
Reads alignment and quantification -> Functional and domain prediction
-> Differential gene expression -> Transcript clustering and visualization

<img src="images/spectrum.02318-21-f005.gif?raw=true"/>

[![](https://img.shields.io/badge/Python-white?logo=Python)](#) [![](https://img.shields.io/badge/pandas-white?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMIAAAEDCAMAAABQ/CumAAAAeFBMVEX///8TB1QAAEb/ygDnBIgPAFLNzNYTAFnQ0NgMAFcAAETb2eP39/oUBlfV1N7/xwDmAID/9tfLydcjG17/4Yz//vbCwM3ykcL61OfoBIwyKmgAADYAAE0AAErx8PTIxdT/+un/34T85/Lyir/lAHv50eX+9fkpH2Ma8J+4AAACEklEQVR4nO3dzVIaQRSAUYNCEIGoiYmJivnP+79hFrmLVHELZ6pnmG483xqaPruh5lb32ZkkSZIkSZIkvb52z7dZU2+rT4uH2X6rx6m31afF7M1+87dTb6tPCDWEUEMINYRQQ5MS1tu0nqtMSrhKn26e1v1WmZawyn58g4DQL4QIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyECOFA6cvM5a4nYb29yjoO4WmVvM58WPQkbF8e+RqPcDlPVp4t+xLS/W0QEBCqI8yTLpsizN8n/WmJ0CEEBAQEBAQEBIT2CF+/fci6a4hw8y7rvC3CeRYCAgICAgICAgICAgICwlCEtJYIdzdp/3+kdkKHToFQ+RjJMCEcCKF7CAdC6B7CgRC6Nylh9zGtJUJ6uNCsnsOFhhkvPAHC9x+fsloi/Pp5nXTREuH++iLpMwICAgICAgICAgICAgKC/87R7/u0lggdQkBAQEBAQEB4dYQON67UTqh9KuwkDlRBQED4R8gOF5o3Rdh8yepLGO0ez6MNPO+WQ9w3NilhvBAihLIQIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyECKEshAihLIQIoSyEKJt+lL0SNeADUR4TG9cGWXHew10AkPP4aRBO9ohEuOFUEMINYRQQwg1dAKEDvd41t5t2u7lL0qSJEmSJEnSyfUXeomSFq0EzbkAAAAASUVORK5CYII=)](#) [![](https://img.shields.io/badge/Bash-white?logo=GNUbash)](#)

[View paper](/pdf/spectrum.02318-21.pdf)

## Personal projects
---
### MandalaPy: Drawing mandalas with Python and Voronoi diagrams.
Here I developed a mandala generator based on Voronoi diagrams using SciPy and NumPy libraries. MandalaPy uses arrays to iteratively create equidistant points around a center with a defined radius. Then it draws a Voronoi diagram for the created points, producing the mandalas figures.
This project resulted in multiple collaborations around the globe, making its way into the SciPy official [documentation](https://docs.scipy.org/doc/scipy/tutorial/spatial.html#voronoi-diagrams) (last example in Voronoi diagrams section).

<img src="images/mandala_example1.png?raw=true"/>

[View repository](https://github.com/CarlosFocil/mandalapy)

---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
