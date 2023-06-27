# html-first
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="saurabh.css">
</head>
<body>
   
  <!--form-->
 <div class="con">
 <form action=""></form>
 <h1 >payment form </h1>
<h2>contact info</h2>
<p>name: <input type="text"name="name"required></p><!--jaruri hota ahi-->
<fieldset>
  <legend>gender</legend>
<p>
  male  <input type="radio"  name="gender"id="">
  female <input type="radio" name="gender"id="">
</p>
<p>
   Address <textarea name="address"cols="29" rows="10"></textarea>
</p>
<p>Email: <input type="email"name="email" id="email"></p>
<p>pincode <input type="number" name="pincode" id="pincode"></p>
<p>job: <input type="checkbox" name="job"id="job"></p>
<hr>
<h2>payment</h2>
<p>card type:
  <select name="card_type" id="card_type">
    <option value="">select a card type</option>
    <option value="visa">visa</option>
    <option value="master card">master card</option>
    <option value="rupay">rupay</option>
  </select>
</p>
<p>
  card number: <input type="number"name="card_number"id="card number">
</p>
<p>
  exp date <input type="date" name="exp_date"id="exp_date">
</p>
<p>
  cvv <input type="password"name="cvv"id="cvv">
</p>
<p>
  <input type="submit"value="pay_now">
</p>
  </fieldset>
  </div>
</body>
</html>
