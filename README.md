# Cybersecurity Research Corpus for NotebookLM

This repository contains a curated collection of cybersecurity resources, including industry reports, technical articles, and threat intelligence data. The primary objective is to provide a structured dataset for deep analysis and synthesis using **Gemini NotebookLM**.

## 🎯 Project Objective
The goal is to consolidate disparate security documents—ranging from vulnerability research to network defense strategies—into a machine-readable format to leverage AI-driven insights, summarization, and cross-referencing.

🛠️ Data Processing & Tooling
To prepare these resources for Gemini NotebookLM, I utilized two custom Python tools I developed for content optimization:
HTML to MD Converter: Used to strip unnecessary HTML tags and convert web-based resources into clean, structured Markdown for better AI comprehension.
MD to HTML Converter: Used to generate web-compatible versions of the research notes while maintaining structural integrity.
These tools ensured that the disparate sources were unified into a consistent, machine-readable format.

## 📁 Content Overview
* **Formats:** Cleaned Markdown (.md) and HTML files.
* **Topics:** Threat Intelligence, Network Security, Digital Forensics, and SecOps.
* **Optimization:** Documents are formatted to maintain structural integrity during AI ingestion.

## 📚 Source Attribution & Metadata
The materials hosted here are collected from publicly available repositories, research blogs, and open-access security reports. All intellectual property belongs to the respective original authors and organizations.

File ID	Original Title / Source	Resource Type	Link / Reference
01	can_değer_sss.txt	Can Değer (LuNiZz)	GitHub Repo
02	02_sibergüvenlik_dalları.txt	General Security Resources	GitHub Repo
03	03_yazılım.txt	Software Development Basics	GitHub Repo
04	04_tüm_linux.txt / tüm_linux.md	Linux Systems Guide	Official Site
05	Main Aircrack-ng.md	Aircrack-ng Team	Official Docs
06	PayloadsAllTheThings.md	SwisskyRepo	GitHub Repo
07	YazbelPython...pdf	Yazbel (istihza)	Official Site
08	awsome-sec.md	Awesome-Security Community	GitHub Repo
09	cyber-security.pdf	Roadmap.sh	Cyber Security Roadmap
10	owasp_top_ten_2025.md	OWASP Foundation	Official Site
11	peass-ng github	carlospolop	GitHub Repo
12	68747470...png	Paul Jerimy	Certification Roadmap
13	Custom Converter Tools	Siberkosereal	HTML-to-MD / HTML-Merger

## ⚖️ Disclaimer & Fair Use
This repository is intended for **educational and research purposes only** under "Fair Use" guidelines. If you are a copyright holder and wish for your content to be removed, please open an issue or contact the maintainer, and the content will be deleted immediately.
