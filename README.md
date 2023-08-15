<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <style>
    #grey {
      background-color: dimgray;
    }
    #white {
      background-color: #f7f4f4;
    }
    #yellow {
      background-color: rgb(228, 213, 14);
    }
    #black {
      background-color: rgb(12, 11, 11);
    }
    .button {
      padding: 5px 10px;
      border: 1px solid #000;
      margin: 4px;
    }
  </style>
  <body>
    <h2>Color Scheme</h2>
    <span class="button" id="grey"></span>
    <span class="button" id="white"></span>
    <span class="button" id="yellow"></span>
    <span class="button" id="black"></span>
    <script>
      const buttons = document.querySelectorAll('.button');
      const body = document.querySelector('body');

      buttons.forEach(function (but) {
       
        but.addEventListener('click', function (e) {
          
          if (e.target.id === 'grey') {
            body.style.backgroundColor = e.target.id;
          }
          if (e.target.id === 'white') {
            body.style.backgroundColor = e.target.id;
          }
          if (e.target.id === 'blue') {
            body.style.backgroundColor = e.target.id;
          }
          if (e.target.id === 'yellow') {
            body.style.backgroundColor = e.target.id;
          }
          if (e.target.id === 'black') {
            body.style.backgroundColor = e.target.id;
          }
        });
      });
    </script>
  </body>
</html>
