<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>Muskurahat</title>

    <style>
        body {
            background-color: #ffffff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: yellow;
            padding: 10px;
            text-align: center;
        }
        .main-content {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }
        .panda-image {
            width: 300px;
            height: 300px;
            background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQvp0WIXgH0uWeaHbyuvOIndESWW3LAGInv7_U1nGuItmn4cnJBxyOYuMVKQ968LY_Tmig&usqp=CAU.jpg'); /* Add your panda image path here */
            background-size: cover;
            background-position: center;
            border: 5px solid #d4a265; /* Tea pattern border color */
            border-radius: 50%;
            margin-bottom: 20px;
        }
        .tabs {
            display: flex;
            justify-content: center;
            margin-bottom: 20px;
        }
        .tab {
            padding: 10px 20px;
            background-color: #f1f1f1;
            border: 1px solid #ccc;
            cursor: pointer;
            margin: 0 5px;
        }
        .tab:hover {
            background-color: #ddd;
        }
         
         
         
    </style>
</head>
<body>
    <div class="header">
        <h1>Hello Kanjoos , Welcome to chhotu panda's creation ! </h1>
    </div>
    <div class="main-content">
        <div class="panda-image"></div>
        <div class="tabs">
            <div class="tab">Home</div>
            <div class="tab">Help</div>
            <div class="tab">Features</div>
            <div class="tab">Options</div>
        </div>
        <div>
            <button>  <a href="indexp.html">Log In</a>
            </button> <!-- Add your login button -->
        
            <!-- Add more user-specific login options as needed -->
        </div>
        <div class="blog-content">
            <!-- Add a section for user-written blog posts -->
        </div>
        <div class="word-document-interface">
            <!-- Add a word document-like interface with features -->
        </div>
    </div>
