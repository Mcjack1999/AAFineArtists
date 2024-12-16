# **AAFineArtists**  
This repository contains research datasets on African American fine artists throughout history. The project aims to create an accessible database highlighting the artistic contributions of African American artists across various media and artistic movements.

---

## **Rationale**  
Art serves as a fundamental expression of human culture, yet the achievements of African American fine artists have often been overlooked in academic research, public collections, and digital archives. This repository seeks to fill that gap by compiling datasets on African American fine artists, making their contributions more accessible to researchers, educators, and the public.

---

## **Data Collection Process**  
- **Data Source:** [Wikidata](https://query.wikidata.org/) using SPARQL queries.  
- **Query Criteria:** Artists identified as African American painters, including metadata such as:  
  - **Artist Name**  
  - **Birth and Death Dates**  
  - **Birth and Death Places**  
  - **Nationality**  
  - **Education and Training**  
  - **Notable Works and Art Styles**  
  - **Artistic Movements and Eras**  

---

## **Data Cleaning and Normalization**  
- **Data Cleaning Steps:**  
  - Removal of duplicate entries caused by multiple educational institutions or artistic labels.  
  - Date normalization for consistent formatting.  
  - Standardization of art movements and styles.  

- **Data Organization:**  
  - Each artist's information is grouped into unique entries.  
  - Missing or incomplete data is flagged as **"Unknown"**.  

---

## **Data Visualization and Insights**  
- **Visualizations Include:**  
  - Distribution of artistic movements.  
  - Lifespan and activity timeline of artists.  
  - Birthplaces and education institutions attended.  
  - Scatter plots for artists affiliated with specific institutions like **Pratt Institute**.  

---

## **How to Use the Dataset**  
1. **Download the CSV file**: `df_artists.csv` (located in this repository).  
2. **Explore the data:** Use Python, Pandas, and visualization libraries like Matplotlib or Seaborn to analyze trends and patterns.  

---

## **Future Goals**  
- Expand the dataset by including additional art forms such as sculpture, ceramics, and photography.
- Check data accuracy by cross referencing sources.
- Enhance the dataset using other sources like **WikiArt**.  
- Develop a web-based interface for broader public access.  

