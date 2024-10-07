<font size="0.8">

# PyCity Schools Analysis
### Primary functions of files included in this repository:
> - the file named "main.ipynb" is a jupyter notebook containing python code which performs the below functions:<br>
> > * call and read the CSV files in the resources folder called schools_complete.csv and students_complete.csv<br>
> > * marge these CSV files into one dataframe to calculate and analyze the data<br>
> > * Perform calculations to get the # of schools, # of students, total budget, average math/reading scores, and<br>
> > passing math, reading, and overall scores for all 15 schools in a data frame titled district_summary<br>
> > * Perform calucations to get the school types, total students, total budget, per capita budget, average math<br>
> > * and reading scores, and percentage of passing of math/reading/overall in a data frame titled per_school_summary<br>
> > * sort these results by highest performing schools based on % of passing in a dataf rame titled top_schools<br>
> > * sort these results by bottom performing schools based on % of passing in a dataf rame titled bottom_schools<br>
> > * sorting the data to display average math scores for each school for 9th, 10th, 11th, and 12th graders<br>
> > * sorting the data to display average reading scores for each school for 9th, 10th, 11th, and 12th graders<br>
> > * sorting the data to display average scores & percentage passing for schools based on per capita spent<br>
> > in a data frame titled spending_summary<br>
> > * do the same as above but sorting by school size in a data frame called size_summary<br>
> > * doing the same as above but sorting by school type in a data frame called type_summary<br>
<br>
### Analyzing the various summarization data frames allows us to determine the below analysis:<br>
> - Charter schools significantly outperform District schools as Charter schools populate the top 8 of school<br>
> performance in overall passing percentage while at least the bottom 5 schools in overall passing percentage<br> 
> are district schools.<br>
> > * this analysis is backed up by the School Type summary in which average scores and percentages are much<br>
> > higher at Charter Schools overall than they are at District Schools<br>
> - It does not seem to be the case that the more money that is spent on a school overall, the better the performance<br>
> of students passing reading and math.  There are District Schools such as Hernandez and Rodriguez High Schools in<br> 
> whch more than 2.5 Million Dollars is spent overall and they are still in the bottom 5 schools in ranking.<br>
> - From this same data, it can be correlated in some cases that the budget metric that seems to determine overall passing<br>
> percentage trends is actually the money spent PER STUDENT rather than TOTAL on the school.<br>
> > * This is represented by many instances in which the students at a Charter School outperform a District school,<br>
> > the overall spend of the Charter school is less while the spending per student at the Charter school more. But,<br>
> > this is by no means a trend that is true of all schools.  In fact, it is an uncommon result.<br>
> - The Spending Ranges summary indicates that this trend of "more money spent per student equals higher overall<br> 
> passing percentage" is more nuanced, however. This summary shows that schools that spend less than `$585` dollars per student<br>
> actually perform the best with an over `90%` overall passing rate.  But, the schools that spend between `$645-$680` per<br>
> student actually have the lowest percent of overall passing `(~53%)`.  This indicates that the budget of money<br>
> spent per student is much more nuanced and likely is greatly affected by school size, size of administration staff,<br>
> the number of teachers, the exclusivity that Charter Schools may promote,  or another nuanced data metric that<br> 
> cannot be captured in this data set.<br>  
> > * This nuanced result is backed-up by the data indicating that the top 5 performing charter schools all had a<br>
> > per capita spend of between `$582-$638` while the 5 bottom District schools had a per capita spend of<br>
> > between `$637-$655`.  But, the overall passing percentage of all top 5 Charter schools is over `90%` while the<br>
> > Overall Passing percentage of all bottom 5 District schools are below `55%`<br>
> - When comapring the two subjects, it seems that no matter the type of school, the budget, the number of students, or<br>
> the per-capita spend, reading is a subject in which many more students excel overall when compared to math<br>
</font>

---
