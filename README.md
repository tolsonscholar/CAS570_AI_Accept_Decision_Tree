  
 
# CAS 570, *Fundamentals of Complex Adaptive Systems science*
## Computational Project, FallC 2023 Term
## William Tolson, ASU Interdisciplinary Studies MA

This notebook uses scikit-learn 1.3.2 to train a decision tree on data conveying survey opinions about advanced technologies to begin an investigation into the socio-technological complex adaptive systems behind the public acceptance of AI technologies. Adapted in part from "Training of a Decision Tree with Scikit-Learn" by Dr. Enrico Borriello.

*Recommended environment is JupyterLab:* https://jupyter.org/ 

## DATA SOURCE

**PEW RESEARCH CENTER**  
**Wave 99 American Trends Panel**  
Dates: Nov. 1-Nov. 7, 2021  
Mode: Web  
Sample: Full panel  
Language: English and Spanish  
N=10,260  

***************************************************************************************************************************
NOTES

For a small number of respondents with high risk of identification, certain values have been randomly swapped with those of lower risk cases with similar characteristics.

***************************************************************************************************************************
WEIGHTS 

WEIGHT_W99 is the weight for the sample. Data for all Pew Research Center reports are analyzed using this weight.

***************************************************************************************************************************
Releases from this survey:

March 17, 2022 "AI and Human Enhancement: Americans’ Openness Is Tempered by a Range of Concerns"
https://www.pewresearch.org/internet/2022/03/17/ai-and-human-enhancement-americans-openness-is-tempered-by-a-range-of-concerns/ 

March 17, 2022 "5 key themes in Americans’ views about AI and human enhancement" 
https://www.pewresearch.org/fact-tank/2022/03/17/5-key-themes-in-americans-views-about-ai-and-human-enhancement/

May 4, 2022 "Highly religious Americans more skeptical of human enhancements such as brain implants, gene editing"
https://www.pewresearch.org/fact-tank/2022/05/04/highly-religious-americans-more-skeptical-of-human-enhancements-such-as-brain-implants-gene-editing/

July 14, 2022 "How Black Americans view the use of face recognition technology by police"
https://www.pewresearch.org/fact-tank/2022/07/14/how-black-americans-view-the-use-of-face-recognition-technology-by-police/

August 3, 2022 "U.S. women more concerned than men about some AI developments, especially driverless cars"
https://www.pewresearch.org/fact-tank/2022/08/03/u-s-women-more-concerned-than-men-about-some-ai-developments-especially-driverless-cars/

October 24, 2022 "Older Americans more wary than younger adults about prospect of driverless cars on the road"
https://www.pewresearch.org/fact-tank/2022/10/24/older-americans-more-wary-than-younger-adults-about-prospect-of-driverless-cars-on-the-road/
