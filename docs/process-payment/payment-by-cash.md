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
    </a> > <a href="/docs/process-payment.md">Payment Processing</a>
    > <strong>Payment by Cash</strong>
</p>

### Payment by Cash

| Use Case Name | Pay through Cash |
| ------------ | ----- |    
| Summary: | The system processes the order to be paid in cash during pick-up. |
| Actors: | Customer, Vendor |
| Preconditions: | The customer orders from the vendor's store. |
| Postconditions: | The details of payment, as well as the order are sent to the vendor for further processing.
| Basic Flow | **Actor Action** |
|            | 1. Customer creates an order from a vendor. |
|            | 2. Customer selects the "Cash on Delivery" option for the payment options. |               
|            | 3. Customer places the order for processing by the vendor. |               
|            | **System Action** | 
|            | 3.1 The system creates the order with the necessary details. |
|            |  3.1.2 The system adds the order to the customer's and the vendor's list of current orders. |
|            | |
| Exceptions | 1. If the vendor refuses the order, or the customer cancels the order, there will be no payment made.  |
|            | |
<br />

---
<p align="center">© 2026 <a href="#">Buybites</a></p>