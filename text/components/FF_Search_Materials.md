## FF Search Materials

![](../../images/components/FF_Search_Materials.png)


Search for available Materials within the fairyfly therm standards library. 



#### Inputs
* ##### keywords 
Optional keywords to be used to narrow down the output list of materials. If nothing is input here, all available materials will be output. 
* ##### join_words 
If False or None, this component will automatically split any strings of multiple keywords (spearated by spaces) into separate keywords for searching. This results in a greater liklihood of finding an item in the search but it may not be appropropriate for all cases. You may want to set it to True when you are searching for a specific phrase that includes spaces. Default: False. 

#### Outputs
* ##### solid_mats
A list of solid materials within the fairyfly therm standards library (filtered by keywords_ if they are input). 
* ##### cavity_mats
A list of gas cavity materials within the fairyfly therm standards library (filtered by keywords_ if they are input). 