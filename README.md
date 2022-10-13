# Prosper Loan Dataset Exploration
## by Oppong Samuel Addo


## Dataset

> This is an exploration of the prosper loan dataset which consists of 113937 rows and 81 columns(financial variables). This dataset contains the loan data of loan applicants and can be downloaded [here](https://www.kaggle.com/datasets/nurudeenabdulsalaam/prosper-loan-dataset) and the data dictionary(definition of variables) can be read [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings

> In summary, the prosper loan dataset was used to derive some insghts.

It was found that, by looking at the distribution of the borrower rate or interest rate which had multiple peaks one at the 0.15 region and another major peak at 0.32 and the higher a borrowers income range, the higher the amount of loan. 
Also, larger loans seem to have had a longer loan term or duration to be paid off completely with most loans haveing a loan term of 36 month (3 years) followed by 60 months (5 year) loan term. Furthermore, there were as much number of home owners as there were not home owners and their percentages were 50.45% and 49.55 respectively which is fairly balanced. Majority of loans were taken to consolidate other debts and also it was interesting to see that computer programmers were the second most popular occupation that borrowed considering their high salary, one wouldn't expect them to go for loan as frequent as it has happened here. Then again, most borrowers originated from california.
There is higher interest rates on loans taken by borrowers who aren't employed. This could be a level of precaution taken by prosper loans to be able to retrieve most of the loan amount given to such persons within a short duration. It was also seen that larger amount of loans have lesser interest rate on them. Interest rate decreases as we move above loan amounts of $15,000. Also, most of the defaulters are in the income range of $25,000-49,999 and it okay since most of the borrowers fall in that income range. Comparing the loan amounts of defaulters and non defaulters, it was found that none of the defaulters borrowed loans up to $30000 whiles that is not the case for non defaulters (there are values even greater than $30000). With this observation in mind, we can say that prosper did a good job issueing no outrageous amount of loans to defaulters. It was also observed that, loan amount increased as the grade increased from HR-A. This trend was discontinued when it got to grade AA. Similar behaviour applies to the prosper rating, there is a steady increase in loan amount moving from the least rating to the best rating that is from HR-AA but the trend discontinued when it got to rating of B. Performance of borrowers with grade `HR` (lowest grade) have increased tremendously. Comparing the pre-2009 with post-2009, it can be seen that the number of defaulters have dropped significantly. In pre-2009, number of defaulters exceeded the number of non defaulters whereas in post-2009, the number of defaulters is less than the number of non defaulters and this shows an improvement in borrowers with grade `HR`. Also, there is performance improvement in those with grade/rating of `AA` since there is drastic reduce in the number of defaulters over the years. In all, there is a decrease in the number of defaulters. This could mean that the company's rating systems was made much better after 2009 onwards. Again, the higher the credit grade the higher the prosper score. 

## Key Insights for Presentation

> - Most loans are borrowed in order to consolidate debts.

> - The higher the income range, the higher the loan amount and the lesser the interest rate on the loan.

> - Comparing the loan amounts of defaulters and non defaulters, it was found that none of the defaulters borrowed loans up to `$30000` whiles that is not the case for non defaulters (there are values even greater than `$30000`). With this observation in mind, we can say that prosper did a good job issueing no outrageous amount of loans to defaulters.

> - The better the credit grade or prosper rating, the higher the loan amount borrowed. This means that borrowers with good credit grade or prosper rating tend to borrow large loan amount.


> - Performance of borrowers with grade `HR` (lowest grade) have increased tremendously. Comparing the pre-2009 with post-2009, it can be seen that the number of defaulters have dropped significantly. In pre-2009, number of defaulters exceeded the number of non defaulters whereas in post-2009, the number of defaulters is less than the number of non defaulters and this shows an improvement in borrowers with grade `HR`. Also, there is performance improvement in those with grade/rating of `AA` since there is drastic reduce in the number of defaulters over the years. In all, there is a decrease in the number of defaulters. This could mean that the company's rating systems was made much better after 2009 onwards.
