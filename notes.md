### General Notes

- Unit Tests

- Webhooks for changes in order status
- Think about what we're gonna do with chargeback
    - Remove from company's balance, if there's any
    - What to do if there's none? Block company?

- Plan authentication
    - Use 2fa (email code)
- Chat
    - Think about how are we gonna block / unblock chat
    - Think about cache
    - Will it be real time? Instant? Websockets?
    - As we get a message, we can send an event. The front-end can read this event and update the UI. (re-think this)

- Recommendation algo


- Rating
    - (current_rating * rating_amount) + value / (rating_amount + 1);
    - rating_amount += 1;


