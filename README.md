# Credit Health by State

Using the 2014 Prosper Loans Data, the [Credit Health by State visualization](https://public.tableau.com/views/CreditHealthbyState/CreditHealth?:embed=y&:display_count=yes&publish=yes) aims to provide an overview of US residents' credit health and how that is reflected in loan payoff rates. Prosper's credit rating appears to be successfully reflecting the ability of a member to pay off their loans, with lower-rated members less likely to successfully pay off this debt. The dashboard at the end of the story shows how this effect is more severe in certain states, e.g. Iowa.

*Design*

To show more detail on the nation's credit health, I also chose the Prosper credit grade which is a score from AA to HR (http://www.lendacademy.com/prosper-review/). I've started the story with a treemap of just this credit grade so that I could explain what it was, and show immediately that most common credit grades for prosper members are C and D. For one-level data like credit grade, a simple area-based visualization like a treemap quickly allows persons to see which values are more commonly present in the data, especially when the number of possible values is low like credit grades.

I then used a line graph to show that regardless of credit grade, most members did not have multiple Prosper loans. The stacked line graph allowed me to show each type of grade side by side, while showing the steep decline of members with one line to two loans, then the drop to almost no members for 3-5 loans.

For the next story point, I chose a grouped bar chart to show the number of loans in each status. I grouped by credit grade so that it would be a side-by-side comparison of the different grades' loan statuses.  I then sorted by loan status to make it easier to compare different credit grades at a glance.  I wanted to show here how even though there are more loans in the C and D credit grades, there are also substantially more defaulted and charged off loans with these grades.  

For the ending dashboard, I've chosen to display the credit score for each state at the top, as the map is linked to a state-level filter for all other visualizations. The color scheme is blue-teal, with the Credit Score by State visualization's color scheme stepped with 5 steps to show some distinction between states other than North Dakota. All other design choices were made to simplify the design as much as possible.

Based on the feedback in the next section, I made some color and naming changes to add to the simplification and clarity goals of the design.

*Feedback*

I received two major pieces of feedback from the persons I shared the [original visualization](https://public.tableau.com/views/CreditHealthbyState_Draft/Story1?:embed=y&:display_count=yes&publish=yes) with.

First, that the Number of Loans treemap was unclear and confusing. Both persons who found this confusing didn't understand what "Number of Loans" meant on the visualization detail, and why there were two values with this description. "The credit grade and total number of prosper loans (say for OK, there's a "1" and a "3" you roll over the 3 and it says "total prosper loans: 3" and right under that it says "total prosper loans: 51" and the same thing, but different numbers on the 1. What is that referring to?" To clarify this, I renamed the first tooltip to 'Concurrent Prosper Loans' and edited the second so it would show the number of Prosper members in that category. 

The second criticism was regarding the coloring for Credit Score by State. "*What questions do you have about the data?* Why does North Dakota stand out in the Credit Score By State plot?" I realized that North Dakota was the only state with a clear visual difference from the others; the coloring was blurring the difference between the other states. To address this, I changed the color scheme to the 5 step scheme mentioned in the design section.

*Resources*

Color Properties. (n.d.). Retrieved June 16, 2017, from http://onlinehelp.tableau.com/current/pro/desktop/en-us/viewparts_marks_markproperties_color.html

Tableau Tip Tuesday: Poor Man's Custom Geocoding (Part 1). (n.d.). Retrieved June 16, 2017, from https://vizpainter.com/tableau-tip-tuesday-poor-mans-custom-geocoding-part-1/

Understanding Sequential and Diverging Color Palettes in Tableau. (2016, October 14). Retrieved June 16, 2017, from https://www.interworks.com/blog/rrouse/2014/12/15/understanding-sequential-and-diverging-color-palettes-tableau

Understanding Sequential and Diverging Color Palettes in Tableau. (2016, October 14). Retrieved June 16, 2017, from https://www.interworks.com/blog/rrouse/2014/12/15/understanding-sequential-and-diverging-color-palettes-tableau
