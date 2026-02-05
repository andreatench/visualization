# Data Visualization

## Assignment 3: Final Project

Data: COVID-19 cases in hospital and ICU by OH region
https://data.ontario.ca/dataset/covid-19-cases-in-hospital-and-icu-by-ontario-health-region/resource/e760480e-1f95-4634-a923-98161cfb02fa 

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    - GraphPad Prism 10

    > Who is your intended audience? 
    - Public health officials/hopitals for planning

    > What information or message are you trying to convey with your visualization? 
    - The number of patients hospitalized and in the ICU in different regions of Ontario. As well as the number of patients on a vent (size of dot). This can help understand where there is a heavier patient load and where the sickest paitents are related to the overall number of hospitalized patients. 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    - Accessible colour 
    - The data spread may make the coginitive load a bit high when trying to differentiate the different regions - subplots by each region could help. I made one subplot for Central Ontario, but I had to manually filter the data which introduces the chance of error.
    - Asthetic and clean and so you can see as much information as possible - extended the axes, clear labels and legends
    - It is substantive as nothing is skewed or manipulated; however, the lower values overlap a lot which may detract from some understanding. The main areas of concern would be identifying where there are more patients hospitalized and in the ICU, and how many are on a vent, which is more clearly differentiated. The size of scale of the number of patients on a vent may make that diffifcult to ascertain from the static image, but the information is included in when hovering over a point. 
    

    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    - The data is imported and locked so the baseline data can't be altered. However how the plot was created doesn't have a clear history like in python so there could be issues in someone trying to reproduce the exact same plot.
    - The software is also paid which limits what features can be used by different licences which adds an additional barrier.
    - To make subplots I had to manually filter the data (however, maybe there is a way to do this automated) which introduces more potential for errors.
    
    > How did you ensure that your data visualization is accessible?  
    - Prism has a colour blind safe section to choose the colours
    - Used some transparency to see points beneath but made sure they are still visible - it could also be helpful to have subplots by region rather than everything overlayed to be able to better visualize the overlapping points.
    Made sure all labels and legends are clear and descriptive

    > Who are the individuals and communities who might be impacted by your visualization?  
    - Individuals in the different regions of Ontario.
    - As data was updated throughout the pandemic it could help predict the patient loads on the ICUs and the number of ventillators needed in different regions.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    - Wanted to show where the most severe cases of COVID (in ICU) were (what OH region) and how that related to the number hospitalized in the different regions. 
    - I initially wanted to use date as I did in the python plot but I couldn't figure out how to change the data type to make it work which is a limitation of the software.
    - There is more information accessible with the hovering feature (automatically part of the plot) but it may increase the cognitive load too much.


    > What ‘underwater labour’ contributed to your final data visualization product?
    - Collection of numbers of cases, hospitalizations, and reporting by the different regions during a stressful and chaotic time in the healthcare system. There were some missing values that needed to be exluded. This also required accurate testing information for the hospitalizations and there could have been shortages on supplies for testing at different points. 

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 11/02/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
