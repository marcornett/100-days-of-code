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

### Day 22: November 30, 2020

**Today's Progress**: Started a project today. Twitter clone in Django. Working on setting up models for user, tweets, and notifications.

**Thoughts:** Need to think about a user can follow another and should be mostly good after that.

**Link to work:** [Twitter Clone](https://github.com/kenzie-se-q4/twitterclone-marcornett)

### Day 23: December 1, 2020

**Today's Progress**: Twitter clone. Worked on user follow functionality. Added a field to each user that relates to the user object itself and can add another user to a list of users.

**Thoughts:** Still confused even though it is working and will go back to research what I did in my user model.

**Link to work:** [Twitter Clone](https://github.com/kenzie-se-q4/twitterclone-marcornett)

### Day 24: December 2, 2020

**Today's Progress**: Twitter clone. Rendering out all tweets as well as tweets the user is following on the homepage. Also, getting notifications to disappear after being viewed.

**Thoughts:** I am using HTML files that are reusable so I'm passing around titles to appropriately have everything labeled.

**Link to work:** [Twitter Clone](https://github.com/kenzie-se-q4/twitterclone-marcornett)

### Day 25: December 3, 2020

**Today's Progress**: Working on mostly template layout in HTML and CSS. Using the Nes.CSS framework for the look and feel of a video game.

**Thoughts:** Glad I got a lot done in a short time to have the application looking good so far.

**Link to work:** [Twitter Clone](https://github.com/kenzie-se-q4/twitterclone-marcornett)

### Day 26: December 4, 2020

**Today's Progress**: Finishing touches on the functionality. Want anonymous users, even if they don't have an account, be able to view tweets and user profiles but locking them from certain functionality. Also, have a list of recent users being displayed. Also, heavy amount of CSS was completed.

**Thoughts:** It's look and really proud of this! Some CSS weirdness from the Nes.CSS framework but I have it all working as intended. It also looks really good.

**Link to work:** [Twitter Clone](https://github.com/kenzie-se-q4/twitterclone-marcornett)

### Day 26: December 5, 2020

**Today's Progress**: Worked on the Amazon clone. Finished up the Stripe.js feature to validate a card payment and it is to the account on stripe.com.

**Thoughts:** Had issues getting the post request authenticated on the backend due to an issue with my setup of the environment variable but figured it out. Was a little concerning.

**Link to work:** [Amazon Clone](https://github.com/marcornett/amazon-clone)

### Day 27: December 6, 2020

**Today's Progress**: Worked on few issues with Stripe.js. Had to solve non integer issue. Not sure if it is completely solved. I believe I need to round the integer so it doesn't get passed in as a floating point number.

**Thoughts:** The issue seemed to not be straight forward at the beginning but started to make more sense as I worked on it.

**Link to work:** [Amazon Clone](https://github.com/marcornett/amazon-clone)

### Day 28: December 7, 2020

**Today's Progress**: Learned about converting function-based views to class-based views.

**Thoughts:** Not too confusing but Django offers other class-based views with extra functionality that I will look into.

### Day 29: December 8, 2020

**Today's Progress**: Just covered more in Django today. Studying through past concepts to solidify learning.

**Thoughts:** Django has some weirdness to figure out when it comes to making a model. It can be sort of confusing on how a table is being made in the database when it comes to relating one model to another via foreign keys or one to many relationships.

### Day 30: December 9, 2020

**Today's Progress**: Picking up studies with Ruby. Also, studied PostgreSQL. Making databases and tables, modifying information.

**Thoughts:** Ruby is still feeling similar to Python. So far the only difference is a little in the syntax of if else statements. Also this use of an unless operator.

### Day 31: December 10, 2020

**Today's Progress**: Working with Haslib in Python to generate and validate keys.

**Thoughts:** Seems a little familiar to NPM package I used before so I understand the concept. Just need to figure out I will handle it in Python.

### Day 32: December 11, 2020

**Today's Progress**: More Haslib research.

**Thoughts:** Not finding the right info here. Sort of using the same module but not solving the issue with the function for verification. It can't receive any parameters.

### Day 33: December 12, 2020

**Today's Progress**: Covered more in Python with Haslib.

**Thoughts:** Might have to go different way with validation.

### Day 34: December 13, 2020

**Today's Progress**: Today I'm learning more about Ruby. Soon I'll get into loops and iterators.

**Thoughts:** Learning a little about checking for info in strings and replacing characters.

### Day 35: December 14, 2020

**Today's Progress**: Make up day for missed day. Working in Ruby to learn more.

**Thoughts:** Working with loops is slightly similar to Python.