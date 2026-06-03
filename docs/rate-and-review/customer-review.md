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
    </a> > <a href="/docs/rate-and-review.md">Review and Rating System</a>
    > <strong>Customer Reviews Store</strong>
</p>

### Customer Reviews Store
| Use Case Name | Customer Reviews Store |
| ------------ | ----- |    
| Summary: | The customer leaves a rating and a review (optional) that is displayed in the vendor's review page.  |
| Actors: | Customer |
| Preconditions: | The customer has completed an order from the vendor that is being given a review. |
| Postconditions: | The review is saved and is displayed in the vendor's review page.
| Basic Flow | **Actor Action** |
|            | 1. Customer confirms that order has been received. |
|            | 2. Customer clicks "Review" button. |
|            | 3. Customer types in message and clicks the Send button. |               
|            | **System Action** | 
|            | 1.1. The system navigates the customer to the vendor profile page |
|            | 2.1. The system navigates the customer to the chat conversation page with the vendor.
|            | 3.1 The system sends the contents of the chat to the vendor, creating a chat history.|
|            |   |
| Exceptions | 1. If the connection is abruptly cut or interrupted before message is sent, the message will fail to send.  |
|           | |

<br />

---
<p align="center">© 2026 <a href="#">Buybites</a></p>