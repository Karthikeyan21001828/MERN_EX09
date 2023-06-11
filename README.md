# Exp -9 Create a Birthday card using HTML and CSS
## AIM:
To write html & css code to create birthday card.
## PROCEDURE:
### STEP 1:
Create a html code for the birthday card.
### STEP 2:
Make style for the birthday card using css.
### STEP 3:
Link the css with html by link tag
### STEP 4:
Verify the output by running the birthday card in any web browser. 
## PROGRAM:
### HTML:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Birthday Card</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <div class="card">
      <img src="card.jpg" alt="Birthday Image">
      <h1 class="title">Happy Birthday!</h1>
      <p class="message">Wishing you a day filled with laughter, love, and lots of cake!</p>
      <p class="signature">Best wishes,</p>
      <p class="signature">From Karthikeyan</p>
    </div>
  </body>
</html>
```
### CSS:
```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    background-color: #f9f3ec;
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }

  .card {
    background-color: #fff;
    border-radius: 20px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.3);
    max-width: 600px;
    padding: 40px;
    text-align: center;
  }

  .title {
    font-size: 40px;
    margin-bottom: 20px;
    color: #ef5b5b;
    text-shadow: 2px 2px #f6cacc;
  }

  .message {
    font-size: 28px;
    margin-bottom: 30px;
    line-height: 1.5;
    color: #4a4a4a;
  }

  .signature {
    font-size: 24px;
    margin-top: 30px;
    color: #4a4a4a;
  }

  img {
    max-width: 100%;
    border-radius: 50%;
    margin-bottom: 30px;
  }
```
## OUTPUT:
![image](https://github.com/Karthikeyan21001828/MERN_EX09/assets/93427303/4d54a1cb-0852-4698-87af-cc1bbdc48f0c)

## RESULT:
html & css code to create birthday card has been created and output has been verified.
