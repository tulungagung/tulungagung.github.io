---
layout: page
title: Contact
permalink: /contact/
show-in-menu: yes
active: active
---


I would like to hear from my readers.

<form id="contact-form" class="form" action="https://formspree.io/f/xbjqzaen" method="POST" enctype="multipart/form-data">
        <ul class="contact-ul">
            <li class="contact-li">
                <label class="contact-label" for="full-name">Name:</label>
                <input type="text" placeholder="Your name" id="full-name" class="contact-input" name="name" tabindex="1"/>
            </li>
            <li class="contact-li">
                <label class="contact-label" for="email-address">Email:</label>
                <input type="email" placeholder="Your email" id="email-address" class="contact-input" name="_replyto" tabindex="2"/>
            </li>
            <li class="contact-li">
                <label class="contact-label" for="message">Message:</label>
                <textarea class="contact-textarea" placeholder="Your message" class="contact-input" rows="4" id="message" name="message" tabindex="3"></textarea>
            </li>
            
        </ul>
        <input type="submit" value="Send" id="submit"/>
        <input type="hidden" name='_subject' id="email-subject" />
        
</form>

<style>
form {
    width: 100%;
}
.contact-li {
    list-style: none;
}

.contact-input {
    border:none;
    border-bottom: 1px solid #eee;
    transition-duration: 0.3s;
    width: 100%;
    background-color: transparent;
}

.contact-input:focus {
    outline:none;
    border-bottom: 1px solid #514A9D;

}

.contact-label {
    display: block;
}

ul.contact-ul {
    margin: 0;
    padding: 10px;
    width: 100%;
}

#submit {
    border:none;
    background-color: #514A9D;
    padding: 5px 15px;
    color: #eee;
    opacity: 0.8;
}

#submit:hover {
    opacity: 1;
    cursor: pointer;
}


#contact-form {
    border: 1px solid #aaa;
    display: inline-flex;
    margin-bottom: 1em;
}

</style>
