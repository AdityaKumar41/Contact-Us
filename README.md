<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>User Store Form</title>
  </head>
  <style>
    body{
        background-color: rgb(0, 0, 0);
    }
    h3 {
      font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
      color: chartreuse;
      font-size: 40px;
      text-transform: uppercase;
      display: inline-block;
      border-bottom: 4mm ridge rgba(211, 220, 50, .6);
      justify-content: center;
    }
    .formhtml {
      position: sticky;
      border-radius: 25px;
      top: 50%;
      left: 21%;
      height: 700px;
      width: 900px;
      background-color: rgb(67, 171, 67);
      text-align: center;
      margin: -25px 0 0 -25px;
    }
    .inputt{
        margin-top: 32px;
        padding: 20px;
        width: 500px;
        font-size: larger;
        border-radius: 25px;
    }
    .contactus{
        justify-content: center;
        text-align: center;
    }
    .btnn{
        padding: 10px 60px;
        font-size: 20px;
        color: rgb(0, 0, 0);
        background-color: rgb(234, 234, 234);
        cursor: pointer;
        font-family: Sans-serif;
        font-weight: 800;
        border-radius: 25px 10px;
    }
    .btnn:hover{
        background-color: #e4c31d;
        border-radius: 10px 25px;
    }

  </style>
  <body>
    <div class="contactus">
      <h3>Contact Us</h3>
      <form action="action.php" class="formhtml">
        <p><input class="inputt" type="text" placeholder="first Name." required="fill the box" /></p>
        <p><input class="inputt" type="text" placeholder="Second Name" required /></p>
        <p>
          <input class="inputt" type="email" required placeholder="exampel@gmail.com" />
        </p>
        <p>
          <input class="inputt" type="text" required="fill the box" placeholder="write something...." />
        </p>
        <p><input class="btnn" type="submit" name="" id=""></p>
      </form>
    </div>
  </body>
</html>
