This is a simple email relay server that handles emails from Kavita application. By default, Kavita installations will use the Kavita hosted email service. However, if a user wants to setup their own SMTP service, then they can run their own instance of this microService.

### Setup

Once you have set up your KavitaEmail service, you can now link your Kavita instance with KavitaEmail service. Navigate to Server Settings and under Email, you can change the URL to your local service (and port if needed). Press Test to ensure it works; as of Kavita-email v0.1.15.0 and Kavita v0.7.1.35 this will send an actual test email to the admin account's email address.
