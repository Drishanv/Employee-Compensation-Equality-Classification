# Employee-Compensation-Equality-Classification
 
We assess compensation fairness across different job roles and factories based on a pre-processed. The file Equality Table.xlsx includes the following columns:

-- Factory – The factory location of the employee

-- Job Role – The role held by the employee

-- Equality Score – An integer ranging from -100 to +100, where 0 is ideal and indicates complete pay equality.

**Objective**

-- To classify the Equality Score into qualitative categories by adding a new fourth column: Equality Class.

**Problem solving approaches:** 

I created a new column named Equality Class and then apply the following classification logic in excel-

Fair: Scores between -10 and +10 (inclusive)

Unfair: Scores greater than +10 or less than -10, but not beyond ±20

Highly Discriminative: Scores above +20 or below -20
