# Hamster Hotel

### Kassandra Spacek / Santiago Montanez / Gianpaolo Reinares
### 11/8/2024
# "Challenge - Puppy Restaurant"
### Description: 
In this project, you will take the following mockup and make it into a fully functioning and fully responsive website.

https://xd.adobe.com/spec/5c97cdf9-bda2-47f1-7c8f-27c7fd5963dd-2aa6/

Your Project must be using GitHub and you need to make sure each person has their own branch. Also be sure to include your Git Hub Link.

This is a group project, so you will submit a 1 page peer review for each of your group mates. You will also write a 1 page self-reflection on how you think you did.

Your Project must be fully responsive and each member of the team must submit the entire project.

> Notes: 


### _GitHub Repository Link:_
[Puppy Restaurant GitHub Repository Link](https://github.com/Kass-S/Puppy-Restaurant.git)


This has been Peer Reviewed By: Karen Cadavos
> Comments:
> *Overall*
1. Responsiveness: Great use of Bootstrap’s built-in responsiveness for handling content! I also appreciate the custom navigation menu you created. However, since you’re already using Bootstrap, you might consider utilizing the Bootstrap Navbar component. It would save time and ensure that your navigation menu adapts responsively across different screen sizes with less custom work.
2. Content Alignment:  All pages except the index, I noticed that the footer, and header have alignment issues with the main content sections. For instance, when viewed at a width of 1920px, the header and footer sections appear wider than the main content, causing a misalignment. Ensuring consistent width and alignment across all sections will improve the design’s cohesion
3. Footer: On mobile screens, the company logo in the footer retains its desktop size, making it look disproportionately large compared to the rest of the footer content. Consider resizing the logo for smaller screens so it fits better within the mobile layout.

*Specific Pages*

1. Index Page: The footer is slightly misaligned with the section directly above it; it’s pushed inward more than the content above. Adjusting this alignment will improve the visual flow of the page.
2. About Page: In the “Team” section, the middle column images are shorter than those in the left and right columns, causing misalignment with the text section that follows.  I also noticed that you’re using multiple classes like About-Page-Card-One, About-Page-Card-Two, etc., mainly to reset the padding to 0.For better responsiveness, it would be more efficient to consolidate these into a single class if they’re performing the same function—this reduces repetition in your code.
3. Catering Page: In the “Catering Services” section, the text column is shorter than the adjacent image column. After inspection, there appears to be a 12px bottom padding affecting the text section. It’s worth checking to see where this padding is coming from and adjust as needed to achieve better alignment with the image.

These adjustments will enhance the responsiveness, alignment, and maintainability of the website. Great job overall!
