# School_District_Analysis

##Overview
- It has been discovered that grades from 9th graders Thomas High School are incorrect due to academic dishonesty. The goal of this analysis was to determine how     removing the grades of these students affect district summary scores, school summary scores, Thomas High School's overall scores, and scores by grade, school       spending, school size, and school type.

##How is the district summary affected?
- The prior district summary data were 	
	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
	79.0	                81.9	              75.0	                85.8	              65.2
- After removing the grades from the 9th graders from Thomas the data were
  Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
	78.9	            81.9	                  74.8	            85.7	          64.9
- Therefore the changes in district scores were the average math score decreased by .1, the average reading score stayed the same (to one decimal point), the % passing math decreased by .2%, the % passing reading decreased by .1% and the %overall passing decreased by .3%.

##How is the school summary affected?
- The old scores for Thomas High School were: 
	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
	  83.4                  83.8                    93.3              97.3            90.9
- The scores for Thomas High School after removing the grades from the 9th graders were:
Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
  83.4	                  83.9                     93.2             97.0	        90.6
- Therefore the changes in Thomas High School scores were the average math score stayed the same (to one decimal point), the average reading score increased by .1, the % passing math decreased by .1%, the % passing reading decreased by .3% and the %overall passing decreased by .3%.

##How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- Thomas still has the 2nd best overall passing % relative to other schools even after replacing the ninth graders' math and reading scores. However, before replacing the scores Thomas had the best passing reading %. After replacing it has the 3rd best passing reading %. It's % passing math ranking is unchanged (7th).

##How does replacing the ninth-grade scores affect the following:
###Math and reading scores by grade
- Prior to removing Thomas' 9th grader scores, the average 9th grader math score was 80.4 and the average 9th grader reading score was 82.5. 
- After to removing Thomas' 9th grader scores, the average 9th grader math score was 80.1 and the average 9th grader reading score was 82.4.
- The average scores for the other grades are unchanged.

###Scores by school spending
- Prior to removing Thomas' 9th grader scores, the scores by school spending were
 Spending Ranges (Per Student). Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing				
<$584	                              83.5	            83.9	                  93.5	        96.6                  90.4
$585-629	                          81.9	            83.2	                  87.1	        92.7                  81.4
$630-644	                          78.5	            81.6	                  73.5	         84.4                 62.9
$645-675	                          77.0	            81.0	                  66.2	         81.1                 53.5
- After removing Thomas' 9th grader scores, the scores by school spending were
	Spending Ranges (Per Student) Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing 					
<$584	                           83.5	                83.9	                  93.5	            96.6              90.4
$585-629	                      81.9	                83.2	                  87.1	            92.7	            81.4
$630-644	                      78.5	                81.6	                  73.5	            84.3	            62.8
$645-675	                      77.0	                81.0	                  66.2	            81.1	            53.5
- Therefore the % passing reading and % overall passing decreased by .1 for the $630-644/student bin.

###Scores by school size
- Prior to removing Thomas' 9th grader scores, the scores by school size were
School Size       Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing			
Small (<1000)         	83.8	            83.9	              93.6	            96.1	              89.9
Medium (1000-2000)	    83.4	            83.9	              93.6	            96.8	              90.6
Large (2000-5000)	      77.7	            81.3	              70.0	            82.8	              58.3
- After removing Thomas' 9th grader scores, the scores by school size were
School Size	    Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Small (<1000)	      83.8	          84.0	                  93.6	            96.1	              89.9
Medium (1000-2000)	83.4	          83.9	                  93.6              96.7	              90.6
Large (2000-5000)	  77.7	          81.3	                  70.0	            82.8	              58.3
- Therefore the % passing reading dropped by .1 for medium schools.

###Scores by school type
- Prior to removing Thomas' 9th grader scores, the scores by school type were
School Type			Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Charter	          83.5	            83.9                        93.6	        96.6                90.4
District	        77.0	            81.0                        66.5	        80.8                53.7
- After removing Thomas' 9th grader scores, the scores by school size were
School Type			Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
Charter	          83.5                    83.9	            93.6              96.6                90.4
District	        77.0	                  81.0              66.5	            80.8                53.7
- There the scores by school type were unchanged (to 1 decimal place).

##Summary
-  Four changes after removing 9th grader scores from Thomas High school were
1) Overall district summary scores and % passing values decreased a little bit.
2) Overall scores and % passing values for Thomas high school decreased a bit.
3) Thomas High School % passing reading ranking dropped to 3rd.
4) The % passing reading and % overall passing decreased a little bit for the $630-644/student bin. 





