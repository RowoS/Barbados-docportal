| **Site Map** |
| ------------- |
| [Project Homepage](/project-homepage.md) |
[Authentication](/docs/authentication.md) |
[Vendor Profile Management](/docs/manage-profile.md) |
[Vendor Search](/docs/search-vendor.md) |
[Order Tracking](/docs/track-order.md) |
[Payment Processing](/docs/process-payment.md) |
[Review and Rating System](/docs/rate-and-review.md) |
[Vendor Communication](/docs/message-vendor.md) |
---

<p>
    <a href="/project-homepage.md">
        Project Homepage
    </a> > <a href="/docs/authentication.md">Authentication</a>
    > <strong>Authentication Sign In</strong>
</p>

![preview of sign-in](/assets/sign-in.png)

### Traditional Login
| Use Case Name | Traditional Login |
| ------------ | ----- |    
| Summary: | The user succesfully logs in to their respective dashboards. |
| Actors: | Customer / Vendor / Admin |
| Preconditions: | The user must have a registered account|
| Postconditions: | The user is logged in successfully redirected to their respective dashboards.
| Basic Flow | **Actor Action** |
|            | 1. User enters their credentials into the fields. |
|            | 2. User presses the "Enter" key or the "Login" button. |
|            |   |
|            | **System Action** | 
|            | 2.1. Verifies credentials entered to the credentials stored in the database. |
|            | 2.2 Redirects user to respective dashboard |
|            |   |
| Exceptions | 1. If the user is not registered, an error message will display on the login page. (e.g: "Account does not exist") |
|           | 2. If credentials entered are incorrect, an error message will be displayed above the input fields.

<br />

### Login via Google
| Use Case Name | Google Login |
| ------------ | ----- |    
| Summary: | The user succesfully logs in to their respective dashboards. |
| Actors: | Customer / Vendor |
| Preconditions: | The user must have a Google account|
| Postconditions: | The user is successfully redirected into the role selection page.
| Basic Flow | **Actor Action** |
|            | 1. User presses the Google button. |
|            | 2. User selects a Google account |
|            |   |
|            | **System Action** | 
|            | 1.1 Redirects the user to the Google OAuth page |
|            | 2.2 Redirects user to the role selection page |
|            |   |
| Exceptions | 1. If the process is interrupted (e.g: user goes back to login page without finishing the process), the account will not be registered, and the user will be redirected to an error page. |


---
<p align="center">© 2026 <a href="#">Buybites</a></p>