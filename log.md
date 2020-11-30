# 100 Days Of Code - Log

### Day 1: November 9, 2020

**Today's Progress**: Laying out components for user input. Learning about date & time objects in JavaScript. Figuring out how to make the time to update in real time in realtime. Trying to collect user input from date tag.

**Thoughts:** Not sure how to apply the difference for two different dates and then apply the countdown.

**Link to work:** [Countdown Timer App](https://github.com/marcornett/countdown-timer)

### Day 2: November 10, 2020

**Today's Progress**: Setting up form with input tags. Looking into "moment" npm package that is used for parsing, validating, manipulating, and formatting dates. Reminding myself how to use one handle change method for multiple input tags using the event target name as a identifier.

**Thoughts:** Need to move further past these small issues with handling inputs in React to tackle the real issue with the date calculation.

**Link to work:** [Countdown Timer App](https://github.com/marcornett/countdown-timer)

### Day 3: November 11, 2020

**Today's Progress**: Decided to work on something different every few days to have a change. Working on a bot that can go to a website and purchase something for you. Currently have it working to open up a provided URL, click on certain buttons and input data.

**Thoughts:** I think it is pretty interesting how it works in Python. Curious if there are more efficient processes but will keep going forward.

**Link to work:** [Browser Bot](https://github.com/marcornett/browser-purchase-bot)

### Day 4: November 12, 2020

**Today's Progress**: Back to the countdown timer app. Setting up calculation to get countdown until a certain date. Trying to understand how to get the proper format of a React input tag to match the moment format.

**Thoughts:**

**Link to work:** [Countdown Timer](https://github.com/marcornett/countdown-timer)

### Day 5: November 13, 2020

**Today's Progress**: More research on solving a calculation difference with two sets of dates. Currently, found a better solution to supply the new date function with the user input date to compare to the moment date. Need to do more research with moment.

**Thoughts:** So I thought this would be little easier and I may just be over thinking it but it is a fun challenge so far. Moment seems to be an interesting tool filled with optional date modifications.

**Link to work:** [Countdown Timer](https://github.com/marcornett/countdown-timer)

### Day 6: November 14, 2020

**Today's Progress**: Refactoring to handle some confusion. Handle date change sets user input date to state. Use effect grabs current date and calculates the difference between user input date and current. Need to format date to look more presentable. Using npm package [moment-duration-format](https://www.npmjs.com/package/moment-duration-format) to get a properly formatted date. Got the two dates differences into a string.

**Thoughts:**

**Link to work:** [Countdown Timer](https://github.com/marcornett/countdown-timer)

### Day 7: November 15, 2020

**Today's Progress**: Adjusted countdown string to create an array of each unit of time to properly separate into state. Rendering timer component that has separate measurements of time. Beginning user input for time of day to get an even more accurate countdown to an event.

**Thoughts:** Glad things are moving sooner. At this stage, I will button up functionality and move on to CSS. Will draft layout ideas or search online for UI components to render a countdown timer.

**Link to work:** [Countdown Timer](https://github.com/marcornett/countdown-timer)

### Day 8: November 16, 2020

**Today's Progress**: Currently working with time input to apply to countdown date. It works on occassion so I need to figure out how to keep it consistent.

**Thoughts:** Always frustrating when you get something working and QA testing eventually shows it doesn't work as well as it should. Will refactor. Just realized there is a date time input tag so will use that to solve issue.

**Link to work:** [Countdown Timer](https://github.com/marcornett/countdown-timer)

### Day 9: November 17, 2020

**Today's Progress**: Changed input date to input date time. Looked at moment documentation to format date to match new input. I have an array that contains the amount of days, hours, minutes and seconds left to display. Currently, working on filling an array with 0s based on the date calculation to account for any missing day, hour, or minute values.

**Thoughts:** I may have gone through this in a round about way but ultimately see the finish line.

**Link to work:** [Countdown Timer](https://github.com/marcornett/countdown-timer)

### Day 10: November 18, 2020

**Today's Progress**: Looping issue while inside of a useEffect. Will address this issue with creating an object to hold key, value pair of units of time.

**Thoughts:** Use Effect sometimes still throws me off if I try to do something that I assumed to be simple but recognize that I must be more creative.

**Link to work:** [Countdown Timer](https://github.com/marcornett/countdown-timer)

### Day 11: November 19, 2020

**Today's Progress**: Completed functionality of countdown timer. Moving on to CSS.

**Thoughts:** Super excited this worked out! I do need to consider how I would handle time if requesting something before current time, I may address this at some point but need to put energy into a newer project.

**Link to work:** [Countdown Timer](https://github.com/marcornett/countdown-timer)

### Day 12: November 20, 2020

**Today's Progress**: Spent time on school studies covering Django Custom User model and extending fields.

**Thoughts:** A lot of research here. Ultimately couldn't figure out how to get the new field to show up in the Admin panel. Will do more research.

### Day 13: November 21, 2020

**Today's Progress**: Will work on CSS today for Countdown Timer App.

**Thoughts:** Shoudn't be too much. Might search for an UI library to make things simple and concise.

**Link to work:** [Countdown Timer](https://github.com/marcornett/countdown-timer)

### Day 14: November 22, 2020

**Today's Progress**: A day of CSS. Some changes to how the date was formatted to make the CSS process easier.

**Thoughts:** Simple enough work here for me. Just need to do it.

**Link to work:** [Countdown Timer](https://github.com/marcornett/countdown-timer)

### Day 15: November 23, 2020

**Today's Progress**: Downloaded npm package react-contenteditable to allow for editable field for the event header. CSS styling added.

**Thoughts:** Trying to give more character to the page.

**Link to work:** [Countdown Timer](https://github.com/marcornett/countdown-timer)

### Day 16: November 24, 2020

**Today's Progress**: Working on bot tracker in Django. Mostly have the user info setup. Querying for tickets assigned to user. Need to finish ticket status updates.

**Thoughts:** Instructions were a little confusing and may have been mislead by the demo ultimately.

### Day 17: November 25, 2020

**Today's Progress**: Finished bug tracker. Will work on CSS

**Thoughts:** Initially, this was a little rough but overall it turned out well. Manage the state of a ticket was tricky but with time it started to make more sense.

### Day 18: November 26, 2020

**Today's Progress**: Today, learning about Ruby on Rails. Hoping to learn more about bots.

**Thoughts:** Seems closer to Python than anything I know so this should be pretty approachable.

### Day 19: November 27, 2020

**Today's Progress**: Continuing with Ruby on Rails today. Learning about string methods and string interpolation.

**Thoughts:** So far so good. Will try to dive in deep quicker.

### Day 20: November 28, 2020

**Today's Progress**: Working on an Amazon clone. This project is from a tutorial that I've been watching. So far, currently on the checkout page and will get into credit card payments.

**Thoughts:** Working late tonight. Mostly just tired from coaching with students. Glad I remembered this project to have something to diversify my learning.

### Day 21: November 29, 2020

**Today's Progress**: Continued with the Amazon clone. Working the payment page by adding the swipe.js npm package to collect credit card information and validate it. Also includes a Firebase backend API using Express.

**Thoughts:** Has a lot of parts to this but the only issue is understanding swipe.js. Need to figure out how to handle authentication on either the backend or frontend.
