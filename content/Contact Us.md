---
title: "Contact Us"
date: 2020-10-15
weight: 1
---
<div class="container">
  <form name="contact"method="POST" data-netlify="true">
    <label for="fname">Your Name</label>
    <input type="text" id="fname" name="name" placeholder="Your name..">
    <label for="StudentID">Student ID</label>
    <input type="text" id="StudentID" name="StudentID" placeholder="a1234567">
    <label for="lname">Email</label>
    <input type="text" id="email" name="email" placeholder="Your Email address..">
    <label for="reason">Reason for contact:</label>
    <select id="reason" name="reason">
      <option value="apply">I would like to apply for the internship</option>
      <option value="eoi">I would like to express interest in other opportunities</option>
      <option value="other">Other reasons</option>
    </select>
    <label for="subject">Subject</label>
    <textarea id="subject" name="subject" placeholder="Write something.."></textarea>
    <br>
    <input type="submit" value="Submit">
  </form>
</div>