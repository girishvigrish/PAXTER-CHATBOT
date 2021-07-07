# PAXTER-CHATBOT
Created a chatbot for INDUSTRIES purpose
<!DOCTYPE html>
<html lang="en">
<head>
 
  <script src="https://www.gstatic.com/dialogflow-console/fast/messenger/bootstrap.js?v=1"></script>
  <script src="https://www.gstatic.com/dialogflow-console/fast/messenger/bootstrap.js?v=1"></script>
  <script src="https://www.gstatic.com/dialogflow-console/fast/messenger/bootstrap.js?v=1"></script>
  <script src="https://www.gstatic.com/dialogflow-console/fast/messenger/bootstrap.js?v=1"></script>
<df-messenger
  intent="WELCOME"
  chat-title="BAXTERchatbot"
  agent-id="d3e0b71d-622b-4322-ae9e-f71f43a5d651"
  language-code="en"
></df-messenger>
</style>
<!-- Jquery CDN -->
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script>
    //To minimise the height of chatbox
    $(document).ready(function() {
        window.addEventListener('dfMessengerLoaded', function (event) {
            $r1 = document.querySelector("df-messenger");
            $r2 = $r1.shadowRoot.querySelector("df-messenger-chat");
            $r3 = $r2.shadowRoot.querySelector("df-messenger-user-input"); //for other mods
            var sheet = new CSSStyleSheet;
           

            // manage box height from here
            sheet.replaceSync( `div.chat-wrapper[opened="true"] { height: 470px}`);
            

            

             
            $r2.shadowRoot.adoptedStyleSheets = [ sheet ];
        });
    });
</script>
<style>
	

  df-messenger {
    
  
      
  
           --df-messenger-bot-message:white;
       --df-messenger-input-font-color:black;
           --df-messenger-button-titlebar-color:purple;
           --df-messenger-maximized-chat-close-icon:white;
       --df-messenger-top-navbar-icon:blue;
       --df-messenger-menu-icon:yellow;
           --df-messenger-chat-background-color: #0c0b0b;
       --df-messenger-minimized-chat-close-icon-color:blue;
       --df-messenger-input-box-color:white;
           --df-messenger-font-color:black;
           --df-messenger-send-icon: #6bd12f;
           --df-messenger-minimize-icon:orange;
       --df-messenger-bot-header-rich-icon:pink;
       --df-messenger-input-placeholder-font-color:black;
       --df-messenger-chip-button:pink;
       --df-messenger-chip-color:pink;
           --df-messenger-button-speaker:pink;
           --df-messenger-button-microphone:green;
       --df-messenger-button-close-color:pink;
  
  
           --df-messenger-user-message:aquamarine;
          
  
          }
       
         
        </style>

    

 
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body style="background-color:black;">

  
</body>
</html>
