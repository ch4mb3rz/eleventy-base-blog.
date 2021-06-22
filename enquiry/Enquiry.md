---
layout: layouts/base.njk
title: Enquiry
templateClass: tmpl-base
eleventyNavigation:
  key: Enquiry
  order: 5
---

<form name="contact" method="POST" data-netlify="true" style="display: flex;align-items: center;flex-direction: column; margin:20px;">
  <p>
    <label>First Name: <input type="text" name="name" /></label>   
  </p>
    <p>
    <label>Last Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>