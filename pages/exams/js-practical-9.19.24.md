---
title: Exam 1 - Practical
subtitle: Modern JavaScript
hide-nav: true

live: https://fvtc.software/fvtc/exams/js-practical-9.19.24
repository: https://github.com/fvtc/courses
---

# Exam 1 - Practical

For this exam, you will add "Save" functionality to a webpage that allows users to enter their name and choose a color for the background. When the user clicks the "Save" button, the name and color should be saved to local storage. When the page is reloaded, the name and color should be retrieved from local storage and displayed on the page, along with the last saved date.

<details open>
	<summary class="video">Show/Hide Video</summary>
	<div class="video-container">
		<iframe src="https://www.youtube.com/embed/ChTLrYfmKRw" width="100%" height="100%" frameborder="0"
			allowfullscreen allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture">
		</iframe>
	</div>
</details>

## Clone the Repository

Start by opening Git Bash in a directory of your choosing, then run the following command:

```bash
git clone https://github.com/FVTC/js-color-page.git && cd js-color-page && code .
```

This will clone the repository and open it in Visual Studio Code.

## Instructions

Next, open the `index.htm` file and find the footer section. Replace the text "(replace with your name)" with your name, and save it.

Your task is to add the following functionality to the page by modifying the `site.js` file:

1. When the user clicks the "Save" button, the name, hue, and lastAccess date should be saved to local storage. There is already code that gets the data from local storage, so make sure to use the same key. (10 points)

2. When the user clicks the "Save" button, change the text of the button to "Saved!" for 2 seconds, then change it back to "Save". (5 points)

3. When the page loads, set the initial value of the input elements (name and hue) to the values retrieved from local storage. (5 points)

4. When the page loads, set the text of the "welcomeH1" and "timeP" elements to display the following message: "Welcome back {name}!" and "Your last visit was on {lastAccess}". (5 points)


# Submission

For submission, zip (compress) the folder containing your project and submit it to Blackboard. Do not push your code to GitHub!