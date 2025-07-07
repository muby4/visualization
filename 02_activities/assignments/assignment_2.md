# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```


# Good Data Visualization

Visualization Title: “Global Carbon Emissions by Country”
Source: Our World in Data – https://ourworldindata.org/co2-emissions

### Why this is a good visualization:
      
This visualization shows CO₂ emissions by country using a clean, interactive world map with the ability to filter by year. Here are three key reasons it's effective:

1. **Clarity and Simplicity**: The visual uses a choropleth map where darker shades indicate higher emissions. The legend is intuitive, and the user can hover over a country for exact values. This follows Edward Tufte’s principle of minimizing “chartjunk” and maximizing data-ink ratio.

2. **Context and Comparison**: The time slider at the bottom allows users to see changes over time. This enables storytelling by showing how emissions evolve and differ across nations — a core principle of narrative data visualization (Segel & Heer, 2010).

3. **Accessibility**: The color scheme is colorblind-friendly (using blue gradient tones), and the site is designed responsively for different screen sizes, aligning with accessibility principles (Ware, 2012).

In sum, this visualization makes complex global data easy to understand through interactivity, geographic context, and consistent design choices.



### How could this data visualization have been improved?  

1. **Add per capita data toggle**: While total emissions are useful, a per capita option would add equity context, helping users understand that large countries emit more simply due to population size.

2. **Narrative highlights**: Including annotations or key takeaways (e.g., “China surpassed the U.S. in 2006”) could guide users toward insights more effectively, in line with storytelling best practices.

These enhancements would further improve the visualization’s ability to inform and engage a wide audience.


# Bad Data Visualization

Visualization Title: “Top Smartphone Brands 2021”
Source: Found on Pinterest; original creator unknown

### Why this is a bad visualization:
This pie chart attempts to show smartphone market share by brand in 2021, but it fails in several critical ways:

1. **Misuse of Pie Chart**: Pie charts are notoriously difficult to interpret when there are many slices or when the size differences are small (Cleveland & McGill, 1984). This chart includes 8+ brands, all similarly sized, making it nearly impossible to visually compare shares accurately.

2. **3D Distortion**: The 3D “exploding” effect introduces visual distortion — parts of the pie look larger due to perspective rather than actual data. This violates Tufte’s principle of truthful representation and adds unnecessary “chartjunk.”

3. **Poor Color Choices**: Each brand is represented with a bright, saturated color (e.g., red, green, purple), many of which are not distinguishable to colorblind users. There is no accessible color scheme or alternative labeling (e.g., data table), which makes the chart non-inclusive.

4. **Lack of Source and Context**: The chart does not cite its data source or explain its methodology. Without this, viewers cannot judge its reliability or understand what the data truly represent (units, timeframe, geographic region).

5. **No Labels or Legends**: Several slices are unlabeled or only labeled with percentages (e.g., “12%”) without stating which brand it refers to, making the chart ambiguous and user-unfriendly.

This visualization fails to meet basic standards of clear, ethical, and inclusive data communication.


### How could this data visualization have been improved? 

1. **Use a bar chart instead**: Bar charts are much more effective for comparing categories (Few, 2004). They allow direct comparisons along a common axis and are easier to interpret, especially when there are many values.

2. **Eliminate 3D effects**: A flat, 2D chart avoids distortion and increases clarity. Removing unnecessary embellishments improves focus on the data itself.

3. **Include clear labels and source**: Adding precise brand names, values, and a reliable data source ensures transparency and helps build trust.

4. **Improve color accessibility**: Use a color palette accessible to colorblind viewers (e.g., Color Universal Design or ColorBrewer palettes), or use pattern fills to differentiate sections.

By applying these principles, the visualization could transform from misleading to informative and inclusive.








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
* Submission Due Date: `23:59 - 06/07/2025`
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
