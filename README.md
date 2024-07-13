# Notes!

You can clone this project to build base for your Django Project.                           <br/>

### Feature list.
<ul>
<li> Account Signup & Signin   </li>
<li> Forget password & Reset  password </li>
<li> Send Email (need to configure SMTP setting)</li>
<li> Templates, Static setup.</li>
</ul>

### Runserver
python manage.py runserver --settings=core.settings.dev                                     <br/>

<!-- common commands -->
python manage.py makemigrations --settings=core.settings.dev                                <br/>
python manage.py migrate --settings=core.settings.dev                                       <br/>
python manage.py createsuperuser --settings=core.settings.dev                               <br/>


## CONFIGURATIONS
<small>(You need to create .env files and copy the bellow code and setup)</small>           <br/><br/>

JWT_SECRET_KEY = "your-secret-key"                                                          <br/>

#### #Email Config                                                                          <br/>
EMAIL_BACKEND = " "                                                                         <br/>
EMAIL_HOST = " "                                                                            <br/>
EMAIL_PORT = " "                                                                            <br/>
EMAIL_USE_SSL = True                                                                        <br/>
EMAIL_HOST_USER = " "                                                                       <br/>
EMAIL_HOST_PASSWORD = " "                                                                   <br/>
DEFAULT_FROM_EMAIL = " "                                                                    <br/>