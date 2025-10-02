DC Crime Data
-
Question: "In which neighborhood cluster did the most burglaries take place?

Steps to answer:

  1. Create pivot table from all data
  2. Put "NEIGHBORHOOD_CLUSTER" into rows and values
  3. Put "OFFENSE" in rows
  4. The pivot table now shows how many of each offense was committed in each neighborhood cluster
  5. I can now see which neighborhood cluster had the most burglaries

Answer: Cluster 11 had the most burglaries, with 2.

Final Project Data
-
Link to original dataset: [https://www.cdc.gov/mmwr/volumes/68/wr/mm6810a2.htm?s_cid=mm6810a2_w#T2_up](url)

Steps to clean it:
1. Shifted the row with the sports names in it 1 to the right to line them up with the correct data.
2. Deleted the percentages next to each number because that is not the part of the data I wanted, and so Excel would read it as numbers.

Interesting question: "Which sport caused the most injuries among all youth?" This is a newsworthy question to ask because it can lead to changes in a certain sport that appears to be the most dangerous.

Steps to answer the question:
1. Created a pivot table
2. Placed all individual sports in the values box, got the sum of injuries in each one
3. Put "values" in the rows box
4. Saw which sport had the greatest number of injuries

The answer: Football caused the most injuries among all youth
