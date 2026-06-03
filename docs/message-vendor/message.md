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
    </a> > <a href="/docs/message-vendor.md">Message Vendors</a>
    > <strong>Message</strong>
</p>

### Message
| Use Case Name | Message |
| ------------ | ----- |    
| Summary: | The customer messages the vendor through the chat function; the vendor may also communciate to that customer |
| Actors: | Customer, Vendor |
| Preconditions: | The customer must initiate the conversation with the vendor. |
| Postconditions: | The vendor receives the message sent by the customer.
| Basic Flow | **Actor Action** |
|            | 1. Customer navigates to a vendor profile. |
|            | 2. Customer clicks the "Chat with Store" button. |
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