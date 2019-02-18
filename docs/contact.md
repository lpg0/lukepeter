---
layout: page
title: About
---
<!DOCTYPE html>
<html>
<style>

input[type=submit] {
  width: 100%;
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

div {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
</style>
<body>

<h3>Using CSS to style an HTML Form</h3>

<div>
  <form action="https://formspree.io/lukepg98@gmail.com" method="POST">
  
    <label for="name">Your Name</label>
    <input type="text" name="name" id="name" placeholder="Your Name" required>
    
    <label for="email">Email</label>
    <input type="email" id="email" name="_replyto" placeholder="Your Email" title="Enter your email address">
  
    <label for="comments">Message</label>
    <textarea name="comments" id="comments" placeholder=""></textarea>
  
    <input type="submit" value="Send">
</form>
</div>

</body>
</html>

