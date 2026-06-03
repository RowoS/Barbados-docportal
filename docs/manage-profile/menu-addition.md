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
    > <strong>Update Menu</strong>
</p>

### Update Menu
| Use Case Name | Update Menu |
| ------------ | ----- |    
| Summary: | The vendor updates the menu that is shown to customers, whether it is to add to the menu or to delete items from the menu. |
| Actors: | Vendor |
| Preconditions: | The vendor must be a verified seller. |
| Postconditions: | The user view is updated with the details updated by the vendor.
| Basic Flow | **Actor Action** |
|            | 1. Vendor navigates to their profile. |
|            | 2. Vendor clicks "Menu" button on the sidebar. |
|            | 3. Vendor presses the "Edit Menu" button |               
|            | 4. Vendor updates what is necessary, either editing menu items, adding menu items, or deleting them. |
|            | 5. Vendor clicks the "Save" button. |
|            | **System Action** | 
|            | 2.1. The system transfers the vendor to the Edit Menu Screen |
|            | 5.1 The system updates the database with the edited details|
|            |   |
| Exceptions | 1. If the user is not verified, a page will prompt the vendor to wait for verification. |
|           | 2. If the vendor inputs data in the wrong field (e.g: text in a numeric field), an error message will inform the vendor of this. |
|           |3. If the vendor goes offline during the process, the an error page will display, and details edited will not be retained. |
|           | |

<br />

---
<p align="center">© 2026 <a href="#">Buybites</a></p>