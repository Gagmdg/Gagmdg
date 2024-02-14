<!DOCTYPE html>
<html>
  <head>
    <title>Love Message</title>
    <style>
      body {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        background-color: #f0f0f0;
      }
      .button {
        display: block;
        width: 100px;
        height: 100px;
        background-color: #ff0000;
        border-radius: 50%;
        border: none;
        color: #ffffff;
        font-size: 30px;
        line-height: 100px;
        text-align: center;
        text-decoration: none;
        cursor: pointer;
      }
      .love-message {
        display: none;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 300px;
        height: 200px;
        background-color: #ffffff;
        border: 2px solid #ff0000;
        border-radius: 10px;
        padding: 20px;
        box-sizing: border-box;
        text-align: center;
        font-size: 24px;
        font-weight: bold;
        color: #ff0000;
      }
    </style>
  </head>
  <body>
    <a href="#" class="button">Tap me!</a>
    <div class="love-message">
      <p>I love you!</p>
      <p>With all my heart and soul.</p>
      <p>You are the one who makes my life beautiful and meaningful.</p>
      <p>I am grateful for every moment we spend together.</p>
    </div>
  </body>
  <script>
    const button = document.querySelector('.button');
    const loveMessage = document.querySelector('.love-message');

    button.addEventListener('click', (event) => {
      event.preventDefault();
      loveMessage.style.display = 'block';
    });
  </script>
</html>
