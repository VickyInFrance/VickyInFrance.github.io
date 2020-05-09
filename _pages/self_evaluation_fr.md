---
layout: splash
title: Auto-evaluation
permalink: /fr/self-evaluation/
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/Giez.png
excerpt: >
  <p style="color:rgba(255,0,0,0);">  _ </p>
last_modified_at: 2019-10-04T10:54:48-04:00
ref: self_evaluation
lang: 1
---

<!-- modify this form HTML and place wherever you want your form -->


<form 
  id="fs-frm" 
  name="survey-form" 
  accept-charset="utf-8" 
  action="https://formspree.io/xyynzzkn" 
  method="post">
  <fieldset id="fs-frm-inputs">
    <label for="full-name">Full Name</label>
    <input type="text" name="name" id="full-name" placeholder="First and Last" required="">
    <label for="email-address">Email Address</label>
    <input type="email" name="_replyto" id="email-address" placeholder="Email" required="">
    <label for="qcm">Begining of the QCM:</label>
    <fieldset id="1">
      1. This new boss never 
        <select name="ans1" required="">
        <option value="Select" selected="" disabled="">Choose</option>
      	<option value="1_a">is agree</option>
      	<option value="1_b">agrees</option>
      	<option value="1_c">is agreeing</option>
      	<option value="1_d">is agreed</option>
      </select>
      with anything new.
    </fieldset>
    <fieldset id="2">
      2. Tom's car is full of books I'm afraid, so there
        <select name="ans2" required="">
        <option value="Select" selected="" disabled="">Choose</option>
      	<option value="2_a">won't be</option>
      	<option value="2_b">hadn't been</option>
      	<option value="2_c">weren't</option>
      	<option value="2_d">is</option>
      </select>
      enough room for you
    </fieldset>
  <input type="submit" value="Send Responses">

