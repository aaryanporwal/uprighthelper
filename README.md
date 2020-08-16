# uprighthelper 🪑 🤖

## Description:
To have a proper posture, you need to stay upright while sitting. This website uses machine learning model to learn patterns 👣 in your posture and it helps your back by keeping you in a proper posture. This is acheived by warning you whenever you are not sitting upright with an alert sound and visual effects.
## Running the website:
 You can run the website on: https://aaryanporwal.github.io/uprighthelper/
 
 OR
 
 ### To run the website locally:
 Just clone the repo and open index.html in your browser
 1. When asked by the browser, give permission to utilize the webcam.
 2. Sit in a proper position (upright) and click the Right Position button a few times. (15-20 is usually enough). Each time you press the button it captures an image and trains the machine learning algorithm with it. So to get good results, be sure to look at different parts of the screen, lean a bit to the right/left etc.
 3. Next, sit in a wrong position, (NOT upright) and click the Wrong Position button a few times. (15-20 is usually enough). Again, try looking at different parts of the screen, etc.
4. After doing all these steps, you are ready to go. Leave the website open and it will warn you with sound/viusals whenever you start siting in a wrong posiiton.
If you think it is not working accurately enough, try adding more right position/wrong position samples to train your model better.

## Important Note: 
Note that, this website does not send any data to the web. Everything happens locally, which means YOUR data stays in YOUR machine. Whenever you refresh the page, all the captured data vanishes.
