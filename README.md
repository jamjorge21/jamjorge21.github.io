<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Password Generator</title>
    <link rel="stylesheet" href="hw.css" />
  </head>
  <body>
   
    <div class="wrapper">
      <header>
        <h1>Password Generator</h1>
      </header>
      <div class="card">
        <div class="card-header">
          <h2>Generate a Password</h2>
        </div>
       
        <div class="content">
            
            <br />
            <input type="text" id="display">
            
            <div id="length"></div>
        </div>
       
       
        <div class="card-body">
            
            <textarea 
            readonly
            
            id="password"
            placeholder="Your Secure Password"
            aria-label="Generated Password"
          ></textarea>
        </div>
        <br />
        <input type="range" min="0" max="8" name="slider" id="slider">
        <br />   
        <div class="card-footer">
            <button onclick="generate()"class="btn">Generate</button>        </div>
      </div>
    </div>
    <script src="hw.js"></script>
  </body>
</html>
