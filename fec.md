# Data Analysis 
## Data Cleanup
1. Rename dataset as "ORIGINAL-Dataset_SOFT100K_95-96".
2. Import dataset into OpenRefine and create a new project.
3. Apply "Facet" - "Text Facet" to every column of the spreadsheet. No cluster found. 
4. Change "SONNYWALE" to "SUNNYVALE", "NEW YORKROOK" to "NEW YORK", "ATHERTONO" to "ATHERTON".
5. Export cleaned dataset as csv. file and rename it "CLEAN-Dataset-SOFT100K-95-96-csv".
* **NOTE**: 12 duplicates spotted. Need fact-checking. 

## Data Upload
1. Upload cleaned dataset onto Google Drive.
2. Make a copy of "CLEAN-Dataset-SOFT100K-95-96-csv" in Google Drive. 
3. Freeze the title row and bold it. 

## Question 1
### Which industries contributed the most to the Republican and Democratic parties? 
1. Select the whole spreadsheet and insert pivot table. 
2. Name it "Pivot Table 1".
3. Add "Industry" in Rows, add "Amount" in Values, and add "Party" in Columns. 
4. Copy paste the values in "Pivot Table 1" into a new tab and name it "No Format Pivot Table 1".
5. Sort Column F from Z-A.
6. As shown, the **"Republican/Conservative"** industry contributed the most to the Republican and Democratic parties, with the amount of $7,514,000.
!['Pivot Table 1'](/PivotTable1.png)
### How much was contributed to each party?
1. In "No Format Pivot Table 1" tab, sort Column D (representing the Democratic party) from Z-A. 
2. The **"Media/Entertainment"** industry contributed the most to **the Democratic Party**, with the amount of **$1,880,000**.
3. In "No Format Pivot Table 1" tab, sort Column E (representing the Republican party) from Z-A. 
4. The **"Republican/Conservative"** industry contributed the most to **the Republican Party**, with the amount of **$7,514,000**.

## Question 2
### How much did donors from the Misc. Business sector contribute to the Democratic party? 
1. Sort column "Sector" from A-Z.
2. Select all the cells with Sector "Misc Business" and copy and paste them in to a new tab named "Question 2 Sheet".
3. Also copy and paste the header of the original tab into the tab "Question 2 Sheet".
4. Freeze the title row and bold it in the tab "Question 2 Sheet".
5. Sort column "Party" from A-Z.
6. Use sum formula "=sum(B3:B35)".
7. Donors from the Misc. Business sector contributed **$3,520,000** to the Democratic party.
!['Question 2 Sheet'](/Question2Sheet.png)
### Which donors were based in Miami Lakes, FL?
1. Select column "City" and sort it from A-Z.
2. Two donations are from Miami Lakes, FL and both from **"Windmere Corp"**.
!['Question 2 Sheet2'](/Question2Sheet2.png)

## Question 3
### What percentage of the tobacco industry’s donations does Philip Morris account for? 
1. Sort column "Industry" from A-Z.
2. Select all the cells with Industry "Tobacco" and copy and paste them in to a new tab named "Question 3 Sheet".
3. Also copy and paste the header of the original tab into the tab "Question 3 Sheet".
4. Freeze the title row and bold it in the tab "Question 3 Sheet".
5. Sort column "Donors" from A-Z.
6. In a clean cell underneath the spreadsheet, put in "Philip Morris", and use sum formula "=sum(B5:B17)".
7. In a clean cell underneath the spreadsheet, put in "Total", and use sum formula "=SUM(B2:B22)".
8. In a clean cell underneath the spreadsheet, put in "Percentage", and use divide formula "=B24/B25".
9. Click on the % icon and change the number into percentage. 
10. Philip Morris account for about **68.54%** in the tobacco industry. 
!['Question 3 Sheet2'](/Question3Sheet3.png)
### How much is it?
