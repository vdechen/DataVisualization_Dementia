# Data Visualization - Dementia 
How aware are we? Dementia rates and representations in the last decades
 
# Project Goal and Description
This data visualization project aimed at showing "dementia" mentions in NY Times articles in order to compare them with data from other sources and better understand how informed the general population is on the topic. 

# Technologies 
- NY Times API
- Python (Pandas, Wordcloud)
- Tableau

# Steps
- Articles were searched from 1995-2022 in https://developer.nytimes.com/apis with 'dementia' and 'Alzheimer' terms in them. 
- Results were cleaned and left only with articles that mentioned the terms in their headlines, snippets, lead paragraphs and keywords. There were 1066 articles left for 'dementia' and 2856 for 'Alzheimer'. 
- Both queries were merged into a big dataframe (alzheimer_dementia) from which other dementia related terms were searched for ('mild cognitive impairment', 'alzheimer', 'vascular dementia', 'frontotemporal dementia', 'lewy body'), since the NY Times API displayed unstable response to queries with more than a word. All results were saved in CSV files. 
- CSV files were opened in Tableau, data was visualized through graphics and insights were drawn from them.    
- Word clouds were created for the lead paragraphs of all years and queries, which were turned into GIFs. Patterns of words were noticed throughout the years.
- More content and data were researched on websites, such as https://ourworldindata.org/, https://www.who.int/, https://www.nia.nih.gov/health/topics and https://www.alzint.org/.
- A Tableau dashboard was created to display the findings. 

# Conclusion
- There has been an increase in dementia cases and in longevity in the last decades.
- 'Disease' was the most frequent word in the lead paragraphs of the articles. 
- 'Dementia and 'Alzheimer' are frequently associated with terms related to family, time, uncertainty, life, death and community. 
- After 2007, they have also been increasingly related to health and science words. 
- Even thought mentions about Alzheimer and dementia have slightly increased, different types of dementia and Mild Cognitive Impairment are not very popular. Knowledge about them, however, is important for the early detection of dementia and diverse symptoms, which may allow actions towards future planning and better life quality.
  
# Contact
- LinkedIn: vanessadechen
- GitHub: /vdechen
- Email: vanessadechen@gmail.com
