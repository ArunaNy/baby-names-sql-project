# Baby Name Trends in the United States (1880–2025): An SQL Analysis

## Overview
This project analyzes 146 years of U.S. baby name data to explore popularity trends, name evolution, gender shifts, and cultural influences.

## Dataset
- Source: U.S. Social Security Administration
(https://catalog.data.gov/dataset/baby-names-from-social-security-card-applications-national-data)
- Time span: 1880-2025
- Number of records: 2,181,032
  
Columns		    Description
year 			    Birth year 
first_name		Baby name
sex			      Male/Female
num 		    	Number of babies given the name

## Tools Used
- SQL (GROUP BY, HAVING, CASE, CTEs, Window functions, RANK(), DENSE_RANK(), LAG(), LEAD(), Aggregate functions, JOINs, REGR_SLOPE())
- Tableau
- Python (Pandas), Jupyter Notebook

## Project Questions
### Popularity
- What are the most popular names of all time?
<img width="1422" height="818" alt="top20_male_names" src="https://github.com/user-attachments/assets/e99a0489-126e-41a4-b7b8-3575d6785f18" />

<img width="1424" height="820" alt="top20_female_names" src="https://github.com/user-attachments/assets/8e043171-5462-4af7-abc9-87a9cda65c91" />

- How does the popularity of the names James and Mary change over 140 years? 
<img width="1363" height="815" alt="james_mary" src="https://github.com/user-attachments/assets/5c14f168-ba38-4ecc-8edd-b195476e99b2" />

- Which names have remained popular for over 100 years?
<img width="1364" height="816" alt="top20_for_over_100years" src="https://github.com/user-attachments/assets/58c0cf76-bc1e-4cc5-8b51-18b28a2d8f2c" />

- Which names disappeared? 
<img width="1370" height="822" alt="disappeared" src="https://github.com/user-attachments/assets/0effc6bc-185d-4779-8d2d-e9c403ce5ef5" />

- One-hit wonder names
<img width="1372" height="817" alt="one_hit_wonder_names" src="https://github.com/user-attachments/assets/9a767f19-77d3-4727-99ed-3df4a66b3015" />

### Trends
- Which names grew the fastest?
<img width="1371" height="817" alt="names_grew_fastest" src="https://github.com/user-attachments/assets/6c04e419-2f4a-4c4b-8406-fab6f2ed0750" />

- Which names declined the fastest?
<img width="1370" height="819" alt="names_declined_fastest" src="https://github.com/user-attachments/assets/8dbd844b-e8ad-40a6-88db-1728a1b491b4" />

- Which decade introduced the most new names?
<img width="1422" height="814" alt="decade_with_most_new_names" src="https://github.com/user-attachments/assets/e24135f5-3dae-45de-9528-5f7195e92330" />

### Diversity
- Has name diversity increased over time?
<img width="1374" height="823" alt="diversity_over_time" src="https://github.com/user-attachments/assets/2eb18222-1776-46f4-8229-2ae0fd6b4bce" />

- How concentrated were the top 10 names each decade?
<img width="1421" height="815" alt="top10_share" src="https://github.com/user-attachments/assets/347d2398-3c01-4d96-a9cd-b6b915a3933e" />

### Gender
- Which names are now mostly female but used to be male?
<img width="1423" height="818" alt="male_to_female_name_shift" src="https://github.com/user-attachments/assets/dd9a5d52-0217-4a45-a67a-b154521209af" />



- Which names are now mostly male but used to be female?
<img width="1422" height="816" alt="female_to_male_name_shift" src="https://github.com/user-attachments/assets/e03773de-59ec-4a61-aa7a-4f2b01b2a3b0" />

### Cultural Influence
- Effect of historical events on naming
<img width="1433" height="820" alt="presidents" src="https://github.com/user-attachments/assets/8bf4f461-e93e-4486-9a81-e09e22454e2e" />


<img width="1433" height="821" alt="famous_people" src="https://github.com/user-attachments/assets/654d2f79-52ff-4fd0-a1d8-432eaf7f6bfb" />

- Names inspired by celebrities 
<img width="1435" height="823" alt="actors" src="https://github.com/user-attachments/assets/3b051c71-5050-4a65-afc1-f267a2f391fa" />


<img width="1435" height="821" alt="singers" src="https://github.com/user-attachments/assets/1cba955d-775f-48ca-9d4b-187e6b195ea8" />

## Key insights

- James and Mary are the most popular baby names in U.S. history. Both dominated the early twentieth century but gradually declined afterwards. 
- Baby name diversity has steadily increased over time,  while the share of births captured by the top 10 names declined, suggesting parents increasingly choose unique names.
- Historical events and celebrities can significantly influence baby naming trends. Names such as Franklin, Barack, Elon, Leonardo, Elvis, Margot, and Keanu experienced noticeable increases in popularity following the rise of prominent public figures. In contrast, some celebrities had little measurable impact when their names were already common (e.g., John, Bill, Diana), while others were associated with sharp declines in name usage (e.g., Adolf after Adolf Hitler).























  

