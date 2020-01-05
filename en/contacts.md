---
layout: page
title: Contacts
lang: en
ref: contacts
permalink: /en/contacts
tags: [contacts]
comments: false
---

<div>
    <form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/roberto+en@reale.me" method="post">
        <fieldset id="fs-frm-inputs">
            <label for="full-name">Your Name</label>
            <input type="text" name="name" id="full-name" placeholder="Your Name" required="">
            <label for="email-address">Email Address</label>
            <input type="email" name="_replyto" id="email-address" placeholder="email@domain.tld" required="">
            <label for="message">Message</label>
            <textarea rows="5" name="message" id="message" required=""></textarea>
            <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
        </fieldset>
        <input type="submit" value="Submit">
    </form>
</div>
