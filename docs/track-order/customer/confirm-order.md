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
    > <strong>Confirm Order Received</strong>
</p>

### Confirm Order Received

| Use Case Name | Confirm Order Received |
| ------------ | ----- |    
| Summary: | The customer indicates that the order has been received by them. |
| Actors: | Customer |
| Preconditions: | The order has been processed by the vendor. |
| Postconditions: | The order shall be marked as "Completed".
| Basic Flow | **Actor Action** |
|            | 1. Customer navigates to order page through the "Delivery" tab |
|            | 2. Customer clicks the "To Receive" tab. |
|            | 3. The customer presses the action menu icon. |
|            | 4. The customer clicks the "Order Received" button. |
|            | **System Action** | 
|            | 1.1 The system navigates to the order page.|
|            | 2.1 The system retrieves and displays the orders to be received by the customer.|
|            | 4.1 The system classifies the order as "Completed". |
|           | |

---
<p align="center">© 2026 <a href="#">Buybites</a></p>