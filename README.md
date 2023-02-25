php artisan make:mail SignupEmail (run this command)

in build function you pass the view that we need to used as templatae.

go to mailtrap to send emails.you need to use mailtrap to send emails from local server.
you have smptp username and password you need to use them to send email.
change mail_host username port in env file.

add verification code and verification status in user table.

create mailable class for laravel to send emails

php artisan make:mail SignUpMail   to create mailable class

create mailtrap.io account for sending email careate your account and you will creentials to use for sending email and recieving an email also

add email sender subject and data in mail class which you created using command line

create static function in new controller so it is easy for you
