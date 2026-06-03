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
    </a> > <a href="/docs/track-order.md">Order Tracking</a>
    > <strong>Cancel Order</strong>
</p>

### Cancel Order

| Use Case Name | Search Store by Name |
| ------------ | ----- |    
| Summary: | The customer cancels an order. |
| Actors: | Customer |
| Preconditions: | An order has been made. |
| Postconditions: | The order shall be classified as "Cancelled"
| Basic Flow | **Actor Action** |
|            | 1. Customer navigates to order page through the "Delivery" tab |
|            | 2. Customer clicks the actions menu icon. |
|            | 3. Customer clicks "Cancel Order". |
|            | 4. (Optional) Customer inputs reason for cancelling order.
|            | 5. Customer confirms the cancellation.              
|            | **System Action** | 
|            | 1.1 The system navigates to the order page.|
|            | 2.1 The system displays the list of actions.|
|            | 3.1 The system navigates to the "Cancellation Reason" modal. |
|            | 5.1 The classifies the order as "Cancelled".|
|           | |
| Exceptions          | 1. If the vendor has already accepted the order request, the system will output "The order is already being processed". |


---
<p align="center">© 2026 <a href="#">Buybites</a></p>