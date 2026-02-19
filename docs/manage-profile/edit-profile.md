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
    </a> > <a href="/docs/manage-profile.md">Vendor Profile Management</a>
    > <strong>Edit Profile Details</strong>
</p>

### Edit Profile Details
| Use Case Name | Edit Profile |
| ------------ | ----- |    
| Summary: | The vendor edits the details in their profile (e.g: operating hours, business name, contact info, etc.). |
| Actors: | Vendor |
| Preconditions: | The vendor must be a verified seller. |
| Postconditions: | The user view is updated with the details updated by the vendor.
| Basic Flow | **Actor Action** |
|            | 1. Vendor navigates to their profile. |
|            | 2. Vendor clicks the "Edit Profile" button. |
|            | 3. Vendor fills up the necessary details to be edited. |               
|            | 4. Vendor clicks the "Save" button. |
|            | **System Action** | 
|            | 2.1. The system transfers the vendor to the Edit Profile Screen |
|            | 4.1 The system updates the database with the edited details|
|            |   |
| Exceptions | 1. If the user is not verified, a page will prompt the vendor to wait for verification. |
|           | 2. If the vendor inputs data in the wrong field (e.g: text in a numeric field), an error message will inform the vendor of this. |

<br />

---
<p align="center">© 2026 <a href="#">Buybites</a></p>