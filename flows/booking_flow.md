# Booking Flow (User → BusBuzz → Operator)

1. **User intent capture**
   - Ask: route, date, preferred time, seat type (AC/non-AC), number of seats, passenger names (optional), contact number.

2. **Availability check**
   - Query operator inventory for matching seats.
   - If unavailable, show nearest alternatives (time/class/operator).

3. **Price & discounts**
   - Present price(s).
   - Offer early-booking discount (5–10%) if applicable.
   - Mention no hidden fees; final price is rounded.

4. **Reservation request**
   - Ask user: "Confirm booking for [route, date, time, seats] at [final price]?"
   - If user confirms → send reservation to operator with user contact masked.

5. **Operator confirmation**
   - If operator confirms → provide ticket reference & instructions to user.
   - If operator declines → offer alternatives or refund flow.

6. **Post-booking**
   - Send polite booking summary and cancellation policy.
   - Log transaction for service team monitoring.
