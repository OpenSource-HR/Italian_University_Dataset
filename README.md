# Italian Universities Dataset Repository

Welcome to the **Italian Universities Dataset Repository**! 🎉 This repository is dedicated to providing a structured dataset derived from AlmaLaurea, an entity specializing in data collection from Italian university students.

## 🌟 About This Repository

The purpose of this repository is to make data analysis on Italian universities accessible and straightforward. The dataset is presented in a tabular format to facilitate non-commercial analysis by:

- **Companies**: Build informed relationships with the Italian university landscape.
- **Candidates**: Make better decisions when evaluating universities.

This initiative aligns with AlmaLaurea's terms for non-commercial usage, ensuring that data is utilized ethically and effectively. 🌍

---

## 🎯 Goals

1. **Support Informed Decision-Making**: Enable candidates to evaluate universities and companies to enhance employer branding and recruiting strategies.
2. **Simplify Data Accessibility**: Offer a clean and structured dataset ready for analysis.
3. **Foster Transparency**: Provide an open resource for non-commercial use.

---

## 📁 Repository Structure

### 📂 Current Status (Version 0.1)

- **Data**: The repository currently contains 2023 data for all Italian universities in `.csv` format. The categories mirror those used by AlmaLaurea, and every effort has been made to maintain data integrity, adding some macro-categories over the categories where necessary. The data structure is derived from AlmaLaurea's grouping by disciplinary areas and fields, with student numbers aggregated by university. Users can replicate these results using AlmaLaurea's filters directly on their website, linked in the "Important Notice" section of this README. However, the dataset still requires cleaning.
  - **Work in Progress**: We are implementing a column to differentiate between absolute numbers and percentages, as well as separating aggregate data from individual records. Category 5 is currently the most impacted by these upcoming updates.
  - **Methodological Note**: The original data collected by AlmaLaurea used "-" to indicate that no respondents were present in the sample, and "*" to signify that five or fewer respondents answered in that sample, excluding it from analysis. To maintain this structure and improve usability, "-" has been replaced with the numeric value `0` and "*" with `-1` in the dataset. These replacements carry the same meaning as in AlmaLaurea's original methodology. Refer to the "Important Notice" section of this README for links to AlmaLaurea's official pages on data methodologies.

### 🛠️ Future Plans

- **Enhanced Usability**: Clean and rearrange the dataset further to make it even more user-friendly.
- **Historical Data**: Include data from previous years, dividing `.csv` files by year.
- **SQL Format**: Introduce an SQL database version for improved compatibility and scalability with various HR data analysis tools.
- **Dashboard Implementation**: Consider adding a dashboard to this project, making the dataset more accessible to a broader audience. While *not currently on the roadmap*, this would align with the mission of the repository by simplifying data interpretation for more users.

---

## 🛠️ How to Use

1. Download the `.csv` file for the year of interest directly from the repository.
2. Open the file using your preferred data analysis tool, such as Tableau or Power BI.
3. Start exploring and analyzing the data to meet your needs.

---

## 📬 Get in Touch

For questions, suggestions, or collaborations, feel free to open an issue or reach out:

- **Email**: OpenHRProject@gmail.com 📧
- **LinkedIn**:  
  👥 [OpenSource HR Project](https://linkedin.com/company/opensource-hr-project)  
    ➡️ [Riccardo Spedito](https://linkedin.com/in/riccardo-spedito)  
    ➡️ [Federica Dolcemascolo](https://linkedin.com/in/federica-dolcemascolo)  

---

## 🌟 Contributing

We welcome contributions to enhance this project! Write us to get in touch. Together, we can improve the accessibility and usability of HR-related data. 🤝

---

## 📜 License and Attribution

This repository operates under a **Creative Commons Attribution-NonCommercial (CC BY-NC)** license. This means:

- **Non-Commercial Use Only**: the data and resources provided here are strictly for non-commercial purposes, as per AlmaLaurea's requirements.
- **Attribution**: any use of the data must cite OpenSource HR Project and AlmaLaurea as the original source to maintain transparency and traceability of the data's history.
- **Read the license**: for further details, check the repository's [LICENSE](LICENSE.md) file.

### Important Notice:
This project is **not affiliated with AlmaLaurea**. It repurposes data collected by AlmaLaurea in accordance with their non-commercial usage policy. For detailed methodologies, analyses, and data criteria, please refer directly to AlmaLaurea's official pages:

- [All the data available from AlmaLaurea surveys](https://www.almalaurea.it/i-dati/tutti-i-dati)
- [Data Collection from AlmaLaurea surveys](https://www.almalaurea.it/i-dati/le-nostre-indagini)
- [Contacts and Insights](https://www.almalaurea.it/i-dati/approfondimenti)
- [Where to obtain the data used in this project - Graduates (Bachelor, Master degree) by University](https://www.almalaurea.it/i-dati/tutti-i-dati)
- [Methodological notes from AlmaLaurea](https://www2.almalaurea.it/cgi-php/universita/statistiche/note-metodologiche.php?lang=it&config=profilo&anno=2023)
- [Privacy information by AlmaLaurea](https://www.almalaurea.it/info/condizioni/privacy)

---
