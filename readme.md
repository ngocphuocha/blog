<h1>Blog using laravel MVC using ajax jquery + API and using TailwinCSS</h1>
<h2>I will update version using l5repository in a future</h2>
<p>This project have function: User reset password via mail</p>

<h1 class="color:red;">Set up your .env file for using google mail service</h1>
<pre>
<code>
MAIL_DRIVER=smtp
MAIL_HOST=smtp.gmail.com
MAIL_PORT=465
MAIL_USERNAME=example@gmail.com (Your e-mail)
MAIL_PASSWORD=examplepassword (Your password e-mail)
MAIL_ENCRYPTION=ssl
</code>
</pre>
<p class="font-bold">If you using google account please turn off "2-step Verification" and turn on option "Less secure app access in Secutiry setting</p>
<p>Sending mail forgot pass and reset new password are in UserController</p>
<p>Script ajax in "app/public/js"</p>
