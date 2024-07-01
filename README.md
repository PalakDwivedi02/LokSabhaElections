Indian General Elections 2024 - Data Extraction and Analysis


**Overview**
This project focuses on extracting, cleaning, and analyzing data from the Election Commission of India’s website for the 2024 General Elections. I collected data related to the performance of various political parties, their winning candidates, and overall election results. This repository includes scripts for scraping the election results, processing and merging the data, and performing various analyses to derive insights.

**Data Extraction**
The data extraction process involved web scraping the Election Commission of India’s official results page. I targeted specific URLs corresponding to different states and parties to gather comprehensive election results. Using Python's BeautifulSoup and requests libraries, I parsed the HTML content and extracted tabular data efficiently. Each URL provided data for a different political party, capturing details such as the number of seats won, the winning candidates, and the total votes received.

**Data Processing** 
Once the data was extracted, the next step was to ensure it was clean and consistent across all files. I processed each CSV file to maintain uniformity in data representation. Each CSV corresponds to a political party and contains detailed information about the winning candidates, the number of seats won, and other relevant metrics. I then merged these individual party data files into a single consolidated dataframe. This involved ensuring that all necessary columns were included, such as the party's full name and winning candidates, and handling any missing or inconsistent data entries. The merged dataset provided a comprehensive view of the election results across all parties.

**Analysis**
The analysis phase was crucial in deriving meaningful insights from the data. I calculated the total seat counts for each party, identified the party with the maximum seats, and categorized parties into alliances such as NDA and I.N.D.I. This involved writing scripts to sum the total seats won by each party, identify the party with the highest seat count, and filter out parties that were part of these alliances. Additionally, I extracted winning candidate details for each party, providing a detailed breakdown of the results. Insights derived from this analysis included the total number of seats won by each party and the identification of the parties with the highest seat counts.

**Insights and Findings**
One of the primary insights from this project was identifying the party with the maximum seats won in the 2024 General Elections. This required aggregating the data and pinpointing the party that outperformed others in terms of seat count. Another key finding was categorizing the parties into their respective alliances and determining the total seats won by each alliance. For instance, parties such as BJP, AJSUP, ADS, AGP, JNP, JDS, JDU, LJP, NCP, SHS, SKM, TDP, UPPL, and HAMS were identified as part of the NDA alliance, and their combined seat counts were analyzed. Similarly, I.N.D.I alliance members such as AAP, CPI, INC, DMK, AITC, SS, SP, NCP, IUML, JKN, CPOI, JMM, VCK, RSP, RJD, MDMK, ML, KEC, and RLP were analyzed for their performance.

**Conclusion**
The final merged dataset provided a detailed overview of the election results, making it easier to visualize and understand the performance of various political entities. This project not only automated data collection and processing but also offered valuable insights that could be used for further political analysis and forecasting. By consolidating data from multiple sources and ensuring its cleanliness and consistency, I was able to create a robust dataset that served as a foundation for in-depth analysis.
