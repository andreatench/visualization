# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 

 Bad: https://public.tableau.com/app/profile/fergus.smith/viz/FastFashionsEnvironmentalWakeUpCall/Dashboard1

 Good: 
![alt text](image.png)
With legend, from Figure 1J of: 
Belizaire, R. et al. CBL mutations drive PI3K/AKT signaling via increased interaction with LYN and PIK3R1. Blood 137, 2209–2220 (2021).
https://ashpublications.org/blood/article/137/16/2209/474916/CBL-mutations-drive-PI3K-AKT-signaling-via 


- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
    Bad:
    - This infographic about the environmental impacts of fast fashion over time.
    - This figure is certainly aesthetic as they map a lot of information onto a pair of jeans. However, there is a high cognitive load due to how many different illustrations included and that you have to click through many sections to get any meaningful insights. The visualization is missing substance and takes a bit of time to understand what is being portrayed. For example, on the plot on the left pocket showing the global population compared to textile production, it took me a bit of time to recognize the title was the legend and that the jean pocket served as the x and y axis for the two lines.
    - Additionally, I didn't understand what was being shown with the "case of a pair of jeans" on the right. So with the first two images not being clear, it makes one less likely continue through the full visualization. These means of presentation, with so many popups and unclear plots are extraneous and unnecessarily increase the complexity.
    - They also include more rare plot type as well (e.g. the illustration of "Fashion's environmental impact within planetary boundaries from 2015 to 2030), making it more challenging to understand as it is not clear what the colours mean or what the different inner shapes mean. Additionally, you have to click on the silver buttons to gain any insights.
    

    Good:
    - This figure compares the enriched phosphorylation sites of identified by mass spectrometry for cells expressing wildtype or an oncogenic mutant of CBL (C384Y)
    - The data is aesthetic, showing proteins of interest highlighted in colour, a simple design and clear description in the legend
    - The data is substantive, with clearly labeled axis, a legend, a description for the statistics (the dotted line indicating pvalue less than 0.05)
    - The data is perceptual - we can easily distinguish what sites of interest were increased for WT or mutant CBL by the annotations and the colours. The information for proteins that are not relevant to the discussion is not highlighted to avoid overwhelming amounts of information (lowers the cognitive load through reducing extraneous information - could access in supplementary of data of the paper if of interest, but is not the main point). This does direct attention to particular proteins of interest. The set up as the fold change and p value comparison allow us to easily see bigger changes between WT and mutant (more different are at the extremes - left and right upper corners). The colours of the phosphosites of particular proteins also make it easy to see right away that there are different proteins with sites enriched for WT vs the mutant - for example many PI3K sites in blue are enriched with the mutant protein on the left half, while they are not with wildtype, and there are other proteins (MAPK in orange and STAT5 in purple) enriched for WT on the right half of the plot. These allow us to see the similarlity of the conditions easily.



      ```
    - How could this data visualization have been improved?  
      ```
    Bad:
    - Reduce the need to hover over different aspects of the interactive figures to see the information and convoluted charts (like over the pocket of the jeans without an axes - it is aesthetic but increases the cognitive load)
    - Reduce the amount of information included in this one infographic - it is impactful but I think had a high cognitive load and maybe too much at first glance for the limitations of the working memory.
    - It is great that they have references. It would be helpful to align references with the particular plots (or annotate them so it is easy to locate the data for the respective individual visualizations more easily).

    Good:
    - They indicate which protein phosphorylation sites of interest are highlighted for CBL, Lyn and PI3K in red, green and blue respectively. They also highlighted sites for MAPK and some purple sites for STAT5, but don't indicate those in the legend. Would be good to include them in the legend (though they focus more on the sites increased with the mutant in the paper so I understand why they wanted to highlight the three proteins they did). Maybe they could include it on the right with a coloured text based legend as they have on the left.
    - Having all of the specific phosphosites labeled for the proteins of interest is okay, but increases the complexity and adds excess details to the composition. To reduce it, they could maybe be put the specific sites a separate table. I do, however, think it is okay as is and appropriate for the publication (appropriate for the expected audience).



      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 01/26/2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
