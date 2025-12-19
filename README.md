# Ex.05 Book Front Cover Page Design
# Date:5/12/2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>

    
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;800&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .book-cover {
            position: relative;
            width: 90%;
            max-width: 420px;
            aspect-ratio: 3/4;
            
            background: url("cover_1.png") center/cover no-repeat;
            color: #fff;
            padding: 2rem;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            border-radius: 12px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4);
            overflow: hidden;
        }

      
        .wave {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            height: 120px;
            background: url("data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 1440 320'><path fill='%23ffffff22' d='M0,192L80,213.3C160,235,320,277,480,266.7C640,256,800,192,960,176C1120,160,1280,192,1360,208L1440,224L1440,320L1360,320C1280,320,1120,320,960,320C800,320,640,320,480,320C320,320,160,320,80,320L0,320Z'></path></svg>") no-repeat;
            background-size: cover;
            opacity: 0.7;
        }

        .header {
            text-align: center;
            z-index: 2;
            position: relative;
        }

        .header h1 {
            font-size: 1.8rem;
            font-weight: 800;
            line-height: 1.3em;
            text-transform: uppercase;
        }

        .header h2 {
            font-size: 0.9rem;
            font-weight: 400;
            letter-spacing: 3px;
            margin-top: 0.5rem;
            text-transform: uppercase;
            opacity: 0.9;
        }

        .footer {
            display: flex;
            justify-content: space-between;
            align-items: center;
            z-index: 2;
            position: relative;
        }

        .footer .tagline {
            font-size: 0.9rem;
            font-weight: 600;
            text-transform: uppercase;
        }

        .author {
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }

        .author img {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            border: 2px solid white;
        }

        .author span {
            font-size: 0.8rem;
            font-weight: 600;
        }


        @media (max-width: 480px) {
            .header h1 {
                font-size: 1.4rem;
            }

            .footer .tagline {
                font-size: 0.75rem;
            }
        }
    </style>
</head>

<body>

    <div class="book-cover">
        <div class="header">
            <h1>Echoes of the Forgotten Seas</h1>
            <h2>A Journey Beyond the Waves</h2>
        </div>

        <div class="footer">
            <div class="tagline">Deep Sea</div>
            <div class="author">
                <span>By TONY </span>
                <img src="author.png" alt="Author">
            </div>
        </div>

        <div class="wave"></div>
    </div>

</body>

</html>

```
# OUTPUT:
<img width="1919" height="835" alt="book" src="https://github.com/user-attachments/assets/9b25e9a1-301b-4d90-bbb5-810d4034e30d" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
