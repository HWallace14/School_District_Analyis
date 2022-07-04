# School_District_Analysis

## Overview

The purpose of this analysis is to help Maria, our chief data analyst friend for the city school district, with combing through all of the data for the school district in order to better inform the schools on what they need to work on. This is based on the standardized testing data that she's been given and will be presented to the district's board for review, along with our analysis of the data and any recommendations that we might have.

### Challenge Overview

After looking through the initial batch of data we've been told that there's evidence of academic dishonesty with Thomas High School's 9th graders. We've been asked to scrub their data from the rolls and then complete the analysis again, then compare the two analyses to see what effect was had on the district.

## Results

Removing the 9th graders from Thomas High School had a relatively low impact on the results of the analysis. For example, look at the two screenshots of the district summary below:

###### Before Removal

<img width="686" alt="Original District Summary" src="https://user-images.githubusercontent.com/105998378/177196182-946fb9d9-ced6-45ff-b567-2b70f844c52a.png">


###### After Rework and Removal

<img width="685" alt="District Summary After Removal" src="https://user-images.githubusercontent.com/105998378/177196039-6575c2f4-13bf-4674-95ca-961aa6a28a6a.png">

As you can see the removal of the Thomas High students caused a slight drop of less than 1% in all categories for the district except for the average reading score, which remained the same. This was of course adjusted for the new student count so as not to throw off our data.

The per school summary only changed in regards to Thomas High School, which is expected whenever data is removed. See below:

###### Before Removal

<img width="737" alt="Per School Summary Original" src="https://user-images.githubusercontent.com/105998378/177196933-934b5295-7277-46e1-ae01-7e92d6c88fdb.png">


###### After Removal

<img width="740" alt="Per School Summary After Removal" src="https://user-images.githubusercontent.com/105998378/177196948-b28d8990-c2a3-41d9-9527-65e76e7c4559.png">

While the average scores for reading and math were left relatively close to where they began, all three percentages (reading, math and overall) dropped significantly from the 90s into the 60s. Clearly this wasn't normal so we recounted the number of students in Thomas High minus the bad seeds (as we did for the district summary) and readjusted the percentages to match the current data. That gave us the following per school summary:

###### After Rework

<img width="737" alt="Per School After Adjustment" src="https://user-images.githubusercontent.com/105998378/177197769-f391f177-38ae-48be-a5e4-eb0c31566bed.png">

Interestingly enough, Thomas's scores didn't change all that much overall. They even retained their spot as the 2nd highest-ranked school in the district. 

###### Before Removal

<img width="800" alt="Top Schools Original" src="https://user-images.githubusercontent.com/105998378/177198882-ec70659d-30a8-4da0-adb8-c7db1f5b63f1.png">

###### After Rework and Removal

<img width="800" alt="Top Schools After Removal" src="https://user-images.githubusercontent.com/105998378/177198915-87f452af-beac-4677-90c8-ac93e1803981.png">

## Summary

