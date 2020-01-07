---
layout: page
title: Contatti
lang: fr
ref: contacts
permalink: /fr/contacts
tags: [contatti]
comments: false
---

<div>
    <form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/roberto+it@reale.me" method="post">
        <fieldset id="fs-frm-inputs">
            <label for="full-name">Nome</label>
            <input type="text" name="name" id="full-name" placeholder="Nome" required="">
            <label for="email-address">Email</label>
            <input type="email" name="_replyto" id="email-address" placeholder="email@domain.tld" required="">
            <label for="message">Messaggio</label>
            <textarea rows="5" name="message" id="message" required=""></textarea>
            <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
        </fieldset>
        <input type="submit" value="Submit">
    </form>
</div>
