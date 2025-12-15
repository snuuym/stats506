Sunny Ma  
Uniqname: mchenran  
Stats 506 Final Project Report  
GitHub: https://github.com/snuuym/stats506/tree/main/final%20projects   
## Leadership Age and Nonprofit Service Priorities 
**SUMMARY**  
This project examines the association between leadership age and nonprofit service priorities using data from the National Survey of Nonprofit Trends and Impacts Spring 2021 provided by the Urban Data Catalog. The analysis finds evidence that younger leadership (defined as under 45 years old) is positively associated with an organization’s programmatic focus on serving the LGBTQ+ community, even after controlling for organizational and leadership characteristics.  

**INTRODUCTION**  
The central research question for this project is: Controlling for covariates, is there an association between the age of a nonprofit's leadership (Chief Executive and Board Chair) and the organization's focus on serving LGBTQ+ community? To address this question, this study uses the National Survey of Nonprofit Trends and Impacts Spring 2021 dataset from Urban Data Catalog.   
The dataset contains survey responses from 2,306 nonprofit organizations and includes 359 variables. Because the survey employs sampling weights, all analyses are conducted using survey-weighted methods. After data cleaning and listwise deletion on variables used in the analysis, the final analytic sample consists of 1,688 completed responses, representing 1,548 weighted observations.  
Leadership age is operationalized as a binary variable. An organization is classified as having younger leadership if either the Chief Executive Officer or the Board Chair is younger than 45 years old. Six covariates are included to control for organizational and leadership characteristics. These covariates include organizational variables: Census region (CENSUSREGION4),  Organizational size, measured by the number of full-time staff (STAFF_1_1_1),Organizational sector (NTMAJ5). And leadership demographic variables: Sexual orientation, race and gender of the CEO or Board Chair (CEOBCdem_1_1, CEOBCdem_1_2; CEORACE, BCRACE; CEOGENDER, BCGENDER)  

**RESULTS**  
Weighted descriptive analyses and visualizations indicate that organizations with younger leadership are more likely to report a programmatic focus on serving the LGBTQ+ community. This relationship is further supported by the survey-weighted logistic regression results. After controlling for organizational size, region, sector, and leadership demographic characteristics, the indicator for younger leadership remains positively associated with LGBTQ+ programmatic focus. The estimated effect is statistically significant, with a p-value of 0.045, which is below the conventional 0.05 significance threshold.   
The results also suggest that leadership race and sexual orientation are stronger predictors of an organization’s LGBTQ+ focus than leadership age alone. Organizations with LGBTQ+ representation or racial diversity among their leadership has higher likelihood of prioritizing LGBTQ+ communities in their programming.  

**CONCLUSION**  
This analysis provides evidence that nonprofit organizations with younger leadership (under 45 years old) are more likely to prioritize serving the LGBTQ+ community. While leadership age is a significant predictor, other leadership characteristics—particularly race and sexual orientation—appear to have even stronger associations with LGBTQ+ programmatic focus.  

**ATTRIBUTES OF SOURCES**  
Google Gemini (https://gemini.google.com) was used to assist in identifying appropriate R packages (survey and srvyr) for analyzing and visualizing survey-weighted data. These tools were essential for correctly specifying the survey design and computing weighted estimates.
