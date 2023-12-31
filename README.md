# DataCuration-Analysis
**The goal of your project:**                                                                                               
The goal of my project was to take 13 years of Billboard Hot 100 number ones from 2009 to 2022 and analyze any relevant changes within the months, weeks, songs, and artists from the charts and generate insights. This required us to perfom ETL which is an acronym for ectract, transform, and load. Through this project, I was able to further practice web scrabing and parsing raw data into a csv file.                                                                                        
                                                                                       
 **Links to any relevant API documentation:**                                                                                            
 2009: https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number_ones_of_2009                        
2010: https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number_ones_of_2010           
                                                                                       2011: https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number_ones_of_2011          
                                                                                       2012: https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number_ones_of_2012           
                                                                                        2013: https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number_ones_of_2013           
                                                                                       2014: https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number_ones_of_2014           
                                                                                       2015: https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number_ones_of_2015                                                                
                                                                                       2016: https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number_ones_of_2016                                                                 
                                                                                                                                          2017: https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number_ones_of_2017                                                                                                                                                                                                   
                                                                                      2018: https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number_ones_of_2018                                                                                                                                                                                                        
           2019: https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number_ones_of_2019                                                                                                                                                                                            
     2020: https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number_ones_of_2020                                                                                                                                                                                             
    2021: https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number_ones_of_2021                                                                                                                                                                                              
       2022: https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number_ones_of_2022                                                    
                                                     
**The license of your data and any source data:**                                                                                                                                      
1. MIT Licence
2. Wikipedia Licence: https://en.wikipedia.org/wiki/Wikipedia:Text_of_the_Creative_Commons_Attribution-ShareAlike_4.0_International_License

                       
**A data type and description for each attribute in your data:**                                                            
1. NO.: (Type: Integrer) The unique identifier or serial number of the entry in the dataset.                     
2. Issue Month: (Type: String) The month in which the song reached the number one position on the Billboard Top 100 chart.                                                                                                            
3. Issue Date: (Type: Integer) The specific date (day of the month) when the song reached the number one position on the Billboard Top 100 chart.                                                                                                  
4. Song: (Type: String) The title of the song that achieved the number one position on the Billboard Top 100 chart.       
5. Artist(s): (Type: String) The name of the artist or artists who performed the song that reached the number one position on the Billboard Top 100 chart. In some cases, there are multiple artists involved.                                                                                                                                  
 6. Ref.: (Type: Integer) The number of references or sources cited for the song's position on the chart.                                                                                                                                       
 7. Weeks: (Type: Integer) The number of consecutive weeks the song stayed at the number one position on the Billboard Top 100 chart.
                                     
**Any known issues or potential issues, such as sources of bias in collection:**                                                        
While Wikipedia strives for accuracy, it can sometimes contain errors. This may include the data being misinterpreted or misrepresented during the transfer from Billboard to Wikipedia, or during subsequent edits by Wikipedia contributors. Wikipedia might not have a complete dataset leading some songs or artists might be missing from the data, resulting in a biased sample. The way songs and artists are categorized can also introduce bias. For example, certain genres might be overrepresented or underrepresented due to the subjective categorization by contributors. Billboard itself might have biases in how it collects and ranks data. Certain genres or demographics might be favored over others, affecting which songs make it to the top of the charts. Billboard's data may also be influenced by industry pressures, promotions, or biases in reporting, leading to certain songs or artists being overrepresented.
