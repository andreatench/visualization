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
    - VS code with python and plotly express

    > Who is your intended audience? 
    - Public health officials or the general public to understand severity of covid over time.

    > What information or message are you trying to convey with your visualization? 
    - Cases of COVID in the ICU over time and the relationship with the number of COVID patients on a ventilator. The second plot also gives us clear information about the regions of Ontario where these severe cases occured.

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    - I wanted to portray accurate and substantive information in a clearly understandable way. 
    - Given I am trying to portray trends of severe cases over time (related to ICU numbers and ventilation requirements) rather than individual points, I had to consider what information I could include with the markers. For example, I tried to change the marker size by an additional feature like my prism graph but it made it hard to interpret the trends over time and took away from the main messages trying to be portrayed.
    - I think the cognitive load was too high to get information about the region from the hover name, so I made a second version with the subplots which makes it much more readily clear how the patterns changes by different areas of Ontario and could inform public health decisions more easily. This also made the information more perceptual  because you can clearly see trends by region.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    - I added comments to the code for why I did different steps so that the information is traceable and could be reproduced. I think this is particularly important given the data types needed to be changed and some data had to be excluded. I also made sure to make secondary data frames and not alter the original dataset.

    
    > How did you ensure that your data visualization is accessible?  
    - Used a colour scheme that is color blind safe (I searched what schemes are).
    - The words are simple and could be annotated for a screen reader in the static image.
    - In the notebook there is more information when you hover, which may be overwhelming if it was dictated by a screen reader given there are so many points.
    - I made the second version to make it more easily interpretable. However, multiple subplots together where all the axis labels aren't there might be challenging for a screen reader to convey the information.
    
    > Who are the individuals and communities who might be impacted by your visualization?
    - This selection of data is now retrospective to understand the severity over time and gives us an understanding of when the cases were worst. And the subplots in my second version also tell us where those most severe cases were occuring. I think it is easier to understand this messaging from my python plot compared to my prism plot.  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    - Interested in the progression of the severe COVID cases over time relating to those in the ICU and the most severe, those needing a ventilator. All of these factors are captured in the plot.

    > What ‘underwater labour’ contributed to your final data visualization product?
    - Collection of numbers of cases, hospitalizations, and reporting by the different regions during a stressful and chaotic time in the healthcare system. There were some missing values that needed to be exluded.

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
