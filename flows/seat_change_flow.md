# Seat Change Flow

1. **User requests seat change**
   - Capture original booking and preferred seat.

2. **Check availability**
   - Query operator inventory for requested seat.

3. **Price difference**
   - If upgrade → compute difference and offer payment link or accept operator terms.
   - If downgrade → apply operator rules (possible partial refund).

4. **Confirm with user**
   - Ask user to confirm the seat change & any additional fee.

5. **Operator update**
   - Submit change request to operator; on confirmation update ticket and send new summary to the passenger.
