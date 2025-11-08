# Viz16S-Ampli

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Build Status](https://img.shields.io/github/actions/workflow/status/phurinat-udo/viz16s_ampli/ci.yml?branch=main)
![Issues](https://img.shields.io/github/issues/phurinat-udo/viz16s_ampli.svg)
![Stars](https://img.shields.io/github/stars/phurinat-udo/viz16s_ampli.svg)
![Forks](https://img.shields.io/github/forks/phurinat-udo/viz16s_ampli.svg)
![Contributors](https://img.shields.io/github/contributors/phurinat-udo/viz16s_ampli.svg)
![Last Commit](https://img.shields.io/github/last-commit/phurinat-udo/viz16s_ampli.svg)
![Version](https://img.shields.io/github/v/release/phurinat-udo/viz16s_ampli.svg)
![Coverage](https://img.shields.io/codecov/c/github/phurinat-udo/viz16s_ampli.svg)

> A software for visualize the result from 16S rDNA amplicon sequencing analysis.

---

## Table of Contents
- [Viz16S-Ampli](#viz16s-ampli)
	- [Table of Contents](#table-of-contents)
	- [About](#about)
	- [Features](#features)
	- [Tech Stack](#tech-stack)
	- [Requirements](#requirements)
	- [Installation](#installation)
	- [Usage](#usage)
	- [Screenshots](#screenshots)
	- [Roadmap](#roadmap)
	- [Contributing](#contributing)
	- [License](#license)
	- [Contact](#contact)

---

## About
The Viz16S Ampli is a software that aimed to simplify the visualization of a result from 16S rDNA amplicon sequencing. The visualization in this application including a taxonomic structure (taxa abundance) bar plot and a cladogram with biomarkers from linear discriminant analysis effect size (LEfSe). Viz16S-Ampli is developed based on analysis result from QIIME2 amplicon version 2024.5.

This application can be used on without the internet access after the first installation of the dependency applications.

Viz16S-Ampli requires command line interface applications installed locally to be performed the visualization. 

The instruction for installation and application usage can be found below.

---

## Features
- ✅ Visualize taxonomic structure bar plot of 16S rDNA amplicon sequencing analysis result from ***barplot*** function in **QIIME2 taxa** plugin.
- ✅ Input preparation for LEfSe analysis from three inputs i.e., metadata, feature name (taxonomical name), and classification.
- ✅ Visualize cladogram plot with biomarker determine from LEfSe analysis

---

## Tech Stack
- **Language:** Python
- **GUI Development:** Customtkinter, Tkinter, Matplotlib
- **Backend** Pandas, Dokdo, LEfSe, Export2graphlan, GraPhlAn
- **CI/CD:** GitHub Actions

---

## Requirements
**MacOS** with **Apple Silicon** processor.

---

## Installation
- Download this repository as `.zip` file
- Open file `viz16S_Ampli-Install.command`

---

## Usage
```bash
npm start
```
Add examples and screenshots.

---

## Screenshots
![Screenshot](path/to/image.png)

---

## Roadmap
- [ ] Add authentication
- [ ] Implement dark mode
- [ ] Add mobile support

---

## Contributing
1. Fork the repo
2. Create a branch
3. Submit a pull request

---

## License
![License](https://img.shields.io/badge/license-MIT-green.svg)
This project is licensed under the MIT License.

---

## Contact
- Email: phurinat.udo@outlook.com
- GitHub: [phurinat-udo](https://github.com/phurinat-udo)
- LinkedIn: [Your Profile](https://linkedin.com/in/yourprofile)
