# Pro-103
https://teachablemachine.withgoogle.com/models/yREUEgek9/
<html>
    <head>
        <title>Image recognition</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
    
        <script src="https://cdnjs.cloudflare.com/ajax/libs/webcamjs/1.0.26/webcam.js"></script>
    
       <link rel="stylesheet" href="style.css">
       <script src="main.js"></script>
      
      </head>

      <body>
          <div class="cointainer" style="background-color: khaki;">
            <center>
                <br><br>

                <h1>FACE RECOGNITION WEB APP</h1>

                <br><br>

                <h3>Model is trained to identify the following object: </h3>

                <label style="background-color:chartreuse ; width: 550px; border-radius: 6px;">Father</label>

                <br><br>

                <label style="background-color:chartreuse ; width: 550px; border-radius: 6px;">Mother</label>

                <br><br>

                <label style="background-color:chartreuse ; width: 550px; border-radius: 6px;">Brother</label>

                <br><br>

                <label style="background-color:chartreuse ; width: 550px; border-radius: 6px;">Me</label>

                <br><br>

                <label>Webcam View - </label>
                
                <br>
                <div id="camera"></div>
                <br><br>
                <div id="result"></div>
                <br><br>
                <button onclick="take_snapshot();" class="btn btn-success"> Capture Image</button>
                <br><br>
                <button onclick="check();" class="btn btn-danger"> Identify Image</button>
                <br><br>

                <p style="font-size: 22px;">Object : <span id="result_object_name"></span>  </p>
                <p style="font-size: 22px;">Accuracy : <span id="result_accuracy_name"></span> </p>

                <br><br>
            </center>
        </div>
      </body>
</html>
