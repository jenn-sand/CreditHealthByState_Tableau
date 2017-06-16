# Credit Health by State

Using the 2014 Prosper Loans Data, the [Credit Health by State visualization](https://public.tableau.com/views/CreditHealthbyState/CreditHealth?:embed=y&:display_count=yes&publish=yes) aims to provide an overview of US residents' credit health.  The map shows the average credit score for each state, and clearly shows that the average score in North Dakota is the lowest in the nation.  To show more detail on the nation's credit health, I also chose the Prosper credit grade which is a score from AA to HR (http://www.lendacademy.com/prosper-review/).  Additionally, I've chosen metrics to display how much debt the average Prosper creditor is in for each state, and whether they are taking out additional loans and making payments or paying off their existing loans.

*Design*

I've chosen to display the credit score for each state at the top, as the map is linked to a state-level filter for all other visualizations.  The color scheme is blue-teal, with the Credit Score by State visualization's color scheme stepped with 5 steps to show some distinction between states other than North Dakota.  All other design choices were made to simplify the design as much as possible.

*Feedback*

I received two major pieces of feedback from the persons I shared the visualization with.

First, that the Number of Loans treemap was unclear and confusing.  Both persons who found this confusing didn't understand what "Number of Loans" meant on the visualization detail, and why there were two values with this description.  "The credit grade and total number of prosper loans (say for OK, there's a "1" and a "3" you roll over the 3 and it says "total prosper loans: 3" and right under that it says "total prosper loans: 51" and the same thing, but different numbers on the 1. What is that referring to?"  To clarify this, I renamed the first tooltip to 'Concurrent Prosper Loans' and edited the second so it would show the number of Prosper members in that category.  

The second criticism was regarding the coloring for Credit Score by State.  "*What questions do you have about the data?*  Why does North Dakota stand out in the Credit Score By State plot?" I realized that North Dakota was the only state with a clear visual difference from the others; the coloring was blurring the difference between the other states.  To address this, I changed the color scheme to the 5 step scheme mentioned in the design section.

*Resources*

Color Properties. (n.d.). Retrieved June 16, 2017, from http://onlinehelp.tableau.com/current/pro/desktop/en-us/viewparts_marks_markproperties_color.html

Tableau Tip Tuesday: Poor Man's Custom Geocoding (Part 1). (n.d.). Retrieved June 16, 2017, from https://vizpainter.com/tableau-tip-tuesday-poor-mans-custom-geocoding-part-1/

Understanding Sequential and Diverging Color Palettes in Tableau. (2016, October 14). Retrieved June 16, 2017, from https://www.interworks.com/blog/rrouse/2014/12/15/understanding-sequential-and-diverging-color-palettes-tableau

Understanding Sequential and Diverging Color Palettes in Tableau. (2016, October 14). Retrieved June 16, 2017, from https://www.interworks.com/blog/rrouse/2014/12/15/understanding-sequential-and-diverging-color-palettes-tableau
