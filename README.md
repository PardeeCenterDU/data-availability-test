# Intro
When rebasing IFs to a more current time point, it is desired to examine the gap in terms of data coverage across different base years. In the script, please make sure you change the directory for it to point to your own IFHistSeries. Year range can be changed as well. <br/><br/>
This short script provides such functionality that prints out data points available acorss all preprocessors. Note that each year of data from a preprocessor table would ideally result in 188 data points (we currently have 188 entities in IFs). Additonally, we rely on the field of DataDict to count number of preprocessors. Example output- <br/><br/>
2017 73234<br/>
2018 70302<br/>
2019 67050<br/>
2020 64389<br/>
2021 57987<br/>
2022 27966<br/>
2023 13924<br/>

Further, it allows the users to explore what data sources are lacking behind. Example output- <br/><br/>
Source<br/>
FAO BATCH PULL                                                                                                                                                                                                  160<br/>
World Development Indicators (WDI), World Bank                                                                                                                                                                   62<br/>
UNESCO Institute for Statistics (UIS)                                                                                                                                                                            39<br/>
BGR; "Reserves, Resources and Availability of Energy Resources"Bundesanstalt für Geowissenschaften und Rohstoffe (BGR) in Hannover; Annual Report. Reserves, Resources and Availability of Energy Resources"     11<br/>
FAO FishstatJ software, Global  Aquaculture Production Quantity data                                                                                                                                              9<br/>
JMP WHO/UNICEF                                                                                                                                                                                                    8<br/>
