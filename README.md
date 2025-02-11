# Valentines-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Valentine's Day</title>

    <style>  
        body{
            margin: 0px;
            width: 100vw;
            height: 100vh;
            overflow-y: auto;
            overflow-x:auto;
        }

        .Bg-Container{
            background-color:rgb(165, 42, 42) ;
            margin: 0px;
            width: 100vw;
            height: 100vh;
        }

        .Small-Container{
            position:absolute;
            top: 75px;
            left: 100px;
            width: 65vw;
            height: 65vh;
            background-color: rgb(178, 74,74) ;
            border-radius:35px;
        }

        .Question{
            text-align: center;
            font: bold;
            font-size: 45px;
            font-family: Cursive;
            top: 50px;
            margin-top: 60px;
        }

        .Button{
            position:relative;
            background-color: rgb(255, 160,122);
            font-size: 40px;
            top: 80px;
            left: 370px;
        }

        .button{
            position:relative;
            font-size: 10px;
            top: -340px;
            left: 540px;
        }

        .Image_FLower{
            position: relative;
            top: -220px;
            left:545px;
        }

        .Image_ME{
            position: relative;
            top: -260px;
            left: -230px;
        }
    
        @media screen and (max-width: 480px) {
            .Small-Container {
                width: 90%;
                padding: 15px;
            }

            .Question {
                font-size: 18px;
            }

            .Button, .button {
                font-size: 16px;
                padding: 8px 16px;
            }
        }
        
    </style>
</head>

<body>
    <div class = "Bg-Container">
        <div class = "Small-Container">
            <h1 class = "Question"> WILL YOU BE MY VALENTINE'S DATE ON FEBREUARY 14, 2025?</h1>
            <button class = "Button"> YEEEES </button>
            <p class = "para"> </p>
            <button class = "button"> NO</button>
            <img src = "FLOWER.png" alt = "Blue FLower" class = "Image_FLower" width = "250" height = "400"> 
            <img src = "PICKO.jpeg" alt = "ME face" class = "Image_ME" width = "300" height = "200"> 
          
        </div>
    </div>

    <script>

        const YesButton = document.getElementsByClassName("Button")[0];
        const NoButton = document.getElementsByClassName("button")[0];

        YesButton.addEventListener("click", myParagraph);
        function myParagraph(){
             window.alert("YHEEEEEEHHEEEEEEEEYY!");
             window.alert("I WUUV YOUUU <3");
             window.alert("I cannot wait na mag Feb 14. I wanna experience Valentine's Day with you agaaaain!");
             window.alert("Excited na ako ibigay mga gifts ko saiyo kahit na alam mo na most of eeeeem");
             window.alert("I WUUV YOUU, MY BEAUTIFUL WIIFUUU :>>");
            }


        NoButton.addEventListener("click", changeColor);
        function changeColor(event){
            event.target.style.backgroundColor = "yellow";
            event.target.textContent = ":<<";
            answer = window.prompt("Sure Ka Po? :<<");
                if(answer == "yes" || answer == "Yes" || answer =="YES" || answer == "yES" || answer == "yeS" || answer == "yEs" || answer == "YeS"){
                    answer1 = window.prompt("As in? Sure ka po? I mean ako na ito MUWAHMUWAH OH :<<");
                        if(answer == "yes" || answer == "Yes" || answer =="YES" || answer == "yES" || answer == "yeS" || answer == "yEs" || answer == "YeS"){
                            window.alert("Well NO CHOICE ka. AKIN KA LANG so...AKO LANG PWEDE MO KA-DATE :3");
                            window.alert("Now tap the YEEES button kasi wala ka rin namang choice mwehehhe!");
                        }
                }

                else if(answer == "NO" || answer == "no" || answer == "No" || answer == "nO"){
                    window.alert("YEHEEEEEYY MUWAAAAH");
                    window.alert("Now tap the YEEES button");
        }
    }

    </script>
</body>
</html>
