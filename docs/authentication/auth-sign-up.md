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
    > <strong>Authentication Sign Up</strong>
</p>

![preview of sign-up](/assets/sign-up.png)

### Traditional Sign Up
| Use Case Name | Traditional Sign Up |
| ------------ | ----- |    
| Summary: | The account is successfully created, and redirects to the role selection screen. |
| Actors: | Customer / Vendor  |
| Preconditions: | The user must be connected to the Internet.|
| Postconditions: | The account is successfully created, and the user is redirected to select their role.
| Basic Flow | **Actor Action** |
|            | 1. User enters their desired credentials into the fields. |
|            | 2. User presses the "Enter" key or the "Create Account" button. |
|            |   |
|            | **System Action** | 
|            | 2.1. Verifies and validates credentials entered by the user. |
|            | 2.2. Sends an account verification email to the entered email |
|            | 2.3. Creates the account and redirects user to the role selection screen  | 
|            |   |
| Exceptions | 1. If the account already exists in the system, an error message will display on the sign-up page (e.g: "Account already exists"), and the user will be redirected to the login page. |

<br />

### Sign Up via Google
| Use Case Name | Google Sign Up |
| ------------ | ----- |    
| Summary: | The Google account is registered in the system, and the user is redirected to the role selection screen. |
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