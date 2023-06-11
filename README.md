## EXP 09 - BIRTHDAY CARD

## AIM:

To create a Birthday card using HTML and CSS

## ALGORITHM:

1. Set up the basic structure of your HTML document and include the CSS stylesheet.

2. Design the layout of your birthday card using HTML elements such as < div >, < h1 >, < p >, < img >, and < span >. 

3. Add a container < div > to hold the entire birthday card content.
  
4. Use paragraph tag to disply the personalised greeting. Add an image element to display a birthday-themed image.

## CODE:

### BIRTHDAY.HTML:
```
<!DOCTYPE html>
<html>
    <head>
        <style>
            .card-image
             {
                background-image: url("plan.avif");
                height:750px;
                background-position: center;
                background-repeat: no-repeat;
                background-size: cover;
                position: relative;
             }

            .card-text
             {
                 text-align: center;
                 position: absolute;
                 top: 50%;
                 left: 50%;
                 transform: translate(-50%, -50%);
                 color: #000000;
            }
        </style>
    </head>
    <body>
    <div class="card-image">
    <div class="card-text">
        <h1 style="font-size:70px">HAPPY BIRTHDAY </h1>
        <h2>
            You are a wonderful person.
            <br/>
            Wishing you a joyful birthday with full of blessing!!
        </h2>
        <h1 style="font-size:40px">Have a great birthday &#10084</h1>
    </div>
    </div>
    </body>
</html>
```


## OUTPUT:
![image](https://github.com/swethamohanraj/Exp--9-Create-a-Birthday-card-using-HTML-and-CSS/assets/94228215/e438c8a2-1642-4a06-9398-8879fdea4127)




## RESULT

So,  a birthday card is created using CSS and HTML.
