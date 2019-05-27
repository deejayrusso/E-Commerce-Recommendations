# E-Commerce-Recommendations
Recommendation System for E-Commerce Project (Python)<br>
Analysis with SQLite and Pandas

<br>

### <u>Methods Used</u>
<ul>
  <li>Data Analysis with SQLite and Pandas</li>
  <li>Market Basket Analysis</li>
  <li>Apriori algorithm</li>
  </ul>

### <u>Technologies/Libraries Used</u>
<ul>
  <li>Python 3</li>
  <li>Pandas</li>
  <li>NumPy</li>
  <li>SQLite3</li>
  <li>mlxtend</li>
  <li>Jupyter</li>
  </ul>
  
## <u>Description</u>
The premise of this project is a hypothetical company, "The Company", in the e-commerce industry that would like to develop a recommendation system. "The Company" speacializes in selling adhesives and sealants in addition to many related products in other categories.

There are two parts:
<ol>
  <li><b>Notebook:</b> Uses transaction data from "The Company" to show how to identify complementary products using machine learning techniques to lay the foundation for an automated recommendation engine. Includes code and brief EDA.</li>
  <li><b>PowerPoint:</b> Discusses when brands matter and why customers may choose one brand over another. Then presents how to automatically detect items to use in recommendation system with examples from findings developed in the notebook.</li>
</ol>

## <u>Data </u>
The data used will be two datasets that have been combined. There is a dataset with six months of transactions where items in the "adhesives and sealants" category were purchased and another dataset containing all transactions over a two week period. The raw data contains:

<ul><b>Order Number:</b> The unique identifier for each individual transaction</ul>
<ul><b>l1:</b> Level 1 product identifier (most broad)</ul>
<ul><b>l2:</b> Level 2 product identifier</ul>
<ul><b>l3:</b> Level 3 product identifier (most granular)</ul>
<ul><b>Sku:</b> The unique identifier for a specific item</ul>
<ul><b>Brand:</b> The unique identifier for the specific brand of an item </ul>

## <u>Summary</u>
The apriori algorithm and association rule mining were used to extract frequent itemsets (items purchased together) from the data and generate rules for frequent item patterns. These rules can be used in a recommendation engine in the context of "customers who viewed ... also viewed..." and "customers who purchased ... also purchased..." in order to encourage add-on purchases or encourage past customers to  continue using "The Company" for their e-commerce needs. The results are contained in a CSV file that can be used across platforms for production purposes.

 
 
