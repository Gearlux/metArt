---
layout: page
title: Contact
permalink: /contact/
---

[//]: # https://docs.google.com/forms/d/e/1FAIpQLScqrQnKrj3VQXtsfw5afDRXDpI2UnHj3RJfLhbLFCRBu9sVoQ/viewform?usp=pp_url&entry.1830882349=testName&entry.1531678202=testMail&entry.236869878=testMessage

<script type="text/javascript">var submitted=false;</script>

<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLScqrQnKrj3VQXtsfw5afDRXDpI2UnHj3RJfLhbLFCRBu9sVoQ/formResponse?" target="hidden_iframe" onsubmit="submitted=true;">
  <label for="name">Your name:</label><br>
  <input type="text" name="entry.1830882349" size="50"><br>
  <label for="email">Email:</label><br>
  <input type="text" name="entry.1531678202" size="50"><br>
  <label for="message">Message:</label><br>
  <textarea type="text" rows="10" name="entry.236869878" cols="50"></textarea><br>
  <button class="" type="submit">Submit</button>
</form>

<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>

<script src="../assets/js/jquery.min.js"></script>
<script type="text/javascript">
$('#gform').on('submit', function(e) {
  $('#gform *').fadeOut(2000);
  $('#gform').prepend('Your submission has been processed...');
  });
</script>


