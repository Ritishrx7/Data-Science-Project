# Socioeconomic Differences Between Bourgogne and Franche-Comté Regions in 2012: A PCA Analysis  
*Data Analysis Lecture - Master 1 in Modelisation Statistique*  
Université Franche-Comté, Besançon (2022–2023)  

## **Project Overview**  
This project focused on analyzing **socioeconomic disparities** between the Bourgogne and Franche-Comté regions using data from the 2012 national French census. **Principal Component Analysis (PCA)** was employed to explore relationships between demographic, employment, education, and housing variables across the two regions. Additionally, clustering analysis and mapping were used to visualize patterns and trends.

### **Problem-Solving Approach**:
1. **PCA on 18 Variables**:  
   Conducted PCA on the following variables:
   - Gender (male/female)
   - Education (diploma/no diploma)
   - Employment (unemployed, agriculture, managers, manual workers)
   - Housing (ownership, rent, HLM, house/apartment, secondary residence)
   - Age Groups (15-29, 30-74, 75+)

2. **Mapping and Visualizations**:  
   Used R packages to create visualizations, including:
   - `sf`, `tmap`, `leaflet`: For generating maps.
   - `gridExtra`, `ggrepel`: For detailed plotting.
   Generated maps to visualize population distribution, employment status, housing types, and education levels across both regions.

3. **Clustering Analysis**:  
   Applied clustering and dendrograms to group communes based on socioeconomic factors, revealing insights such as:
   - More homeownership in Bourgogne.
   - Higher rates of renting and unemployment in Franche-Comté.

## **Key Findings**:
- **Manual Workers**: Closely correlated with not having a diploma.
- **Unemployment**: Unemployed individuals are more likely to live in HLM housing and rent homes.
- **Homeownership**: People aged 30-74 are more likely to own homes in Bourgogne.
- **Executive Jobs**: More common in Bourgogne, while renting is more prevalent in Franche-Comté.
- **Gender Differences**: Women are more likely to hold executive jobs in Franche-Comté than in Bourgogne.

## **Key Tools**:
- **Principal Component Analysis (PCA)** for dimensionality reduction and correlation analysis.
- **Clustering and Dendrogram Analysis** for identifying group patterns.
- **R Packages** for mapping and visualization:
  - `sf`, `tmap`, `leaflet`, `gridExtra`, `ggrepel`

## **Project Files**:
- `.Rmd`: R Markdown file containing the full analysis and code.
- `.html`: Rendered HTML report showing results of the analysis.


