html 
----------
> Table 

CSS 
----------

tYPES OF SELECTORS 
-------------------------
1. Element/ tag selector --> used based on tag name
2. Id selector -> used with a given id  ex ; #header{  }
3. class Selector > used to select  an elemnt by given class name .container{ }

4.Descedndant Selector : select the elemnt that are decendant of a spesific parent , used by multiple elemnt by space   .container p{    }

5.child Selector : selects elemnt that arer direct children of a specific parent elemnt ,
                   it involves specifying multiple elemnt separated by > symbol ex : ul>li 
                   

6. Grouping selector : by grouping same style apply  like h1,h2,h3 ,p {  }     

7.universal selector : apply to the document  *{ }   

8.Attribute selector : select by their attribute value ex : input[type="text"]{}

9.Adjacent sibiling selector :   Selects an element that immiditaly follows the another     
                               specific element  ,use + symbol   ex : h2+p{   style applied  
                                  to  p element  immidiatly following an  h2 element }

10.Pseudo class selector  : selects elemnts based on their state   position ex : a:hover{  }      


11.pseudoelemnt selector : selects parts of an elemnt  p::first-line { }
