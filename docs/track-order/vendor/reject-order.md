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
    </a> > 
    <a href="/docs/track-order.md">
        Order Tracking
    </a> >
        <a href="/docs/track-order.md">
        Process Order Requests
    </a> >
     <strong>Reject Order</strong>
</p>

### Reject Order

| Use Case Name | Reject Order |
| ------------ | ----- |    
| Summary: | The vendor rejects the order request from the customer to process. |
| Actors: | Vendor |
| Preconditions: | An order request has been made to the vendor. |
| Postconditions: | The order request is rejected, and is classified as a "Cancelled" order.
| Basic Flow | **Actor Action** |
|            | 1. Vendor navigates to the order page using the "Order" tab. |
|            | 2. Vendor clicks the actions icon. |
|            | 3. Vendor selects "Decline Order" |               
|            | **System Action** | 
|            | 1.1 The system navigates to the order page.|
|            | 2.1 The system displays the action buttons modal.|
|            | 3.1 The system classifies the order as a "Cancelled Order".|
|           | |

<br />
---
<p align="center">© 2026 <a href="#">Buybites</a></p>