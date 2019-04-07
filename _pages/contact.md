---
title: "Contact me"
permalink: /contact/
header:
  overlay_image: /assets/images/seal-contactme.jpg
read_time: false
comments: false
share: false
author_profile: false 
related: false
---

   <div class="col-sm bg-light text-info font-weight-bold px-5 py-4 rounded shadow">
            <h3 class="text-secondary mb-4 font-weight-light">You can email me by clicking <a href="mailto:david.welkie@gmail.com">here</a></h3>
     Or you can simply fill out the form below!
     
     <form action="https://formspree.io/david.welkie@gmail.com" method="POST" id="contact-form">
                <div class="form-group">
                    <label for="name">Your Name</label>
                    <input id="name" type="text" name="name" class="form-control" required>
                </div>
                <div class="form-group">
                    <label for="email">Your Email</label>
                    <input id="email" type="email" name="_replyto" class="form-control" required>
                </div>
                <div class="form-group">
                    <label for="budget">Subject</label>
                    <input id="subject" type="text" name="subject" class="form-control" required>
                </div>
                <div class="form-group">
                    <label for="message">Your message, compliment, idea, or request :-)</label>
                    <textarea id="message" name="message" class="form-control" rows="3"></textarea>
                </div>
                <input type="hidden" name="domain" id="domain"/>
                <input type="hidden" name="_subject" value="Someone used your webpage contact form!"/>
                <input type="submit" value="Send" class="btn btn-info btn-lg">
            </form>
        </div>
