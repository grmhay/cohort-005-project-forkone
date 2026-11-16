# Cadence

An online course platform where learners buy courses, watch lessons, and can ask for their money back shortly after buying.

## Language

### People

**Learner**:
Someone enrolled in a course, whether through their own Purchase or a Team Seat.
_Avoid_: Student (that is the account role, not the relationship to a course), user

### Buying

**Purchase**:
One payment for a course, owned by whoever paid. Buying again after a Refund makes a new Purchase.
_Avoid_: Order, transaction

**Team Purchase**:
A Purchase of several Team Seats on one course, owned by the team admin who paid for them.

**Team Seat**:
One place on a Team Purchase, handed out as a coupon code. A Team Seat is claimed when a Learner redeems its coupon code; a Learner on a Team Seat has no Purchase of their own.
_Avoid_: Redeemed seat (codes are redeemed, seats are claimed)

### Refunds

**Refund Request**:
The owner of a Purchase's written ask to have it refunded, which is Requested until a platform Admin approves or declines it. A Purchase has at most one Refund Request, whatever its outcome.
_Avoid_: Refund (for the request itself), Cancellation, Reversal, Chargeback

**Refund**:
The money returned to the owner of a Purchase when its Refund Request is approved. Approval also takes back what was bought: the owner's enrollment in the course, or, for a Team Purchase, its unclaimed Team Seats. A declined Refund Request refunds nothing.
_Avoid_: Reversal, Chargeback

**Refund Eligibility**:
Whether a Refund Request may be raised on a Purchase, judged at the moment it is raised: within the Refund Window, the Purchase's owner has watched under two hours and completed under half the lessons of the course, and — for a Team Purchase — no Team Seat has been claimed. Watch time and completion are the owner's own, counted across all their Purchases of the course.

**Refund Window**:
The fourteen calendar days after a Purchase, inclusive of the fourteenth day, during which a Refund Request may be raised.

**Refund Amount**:
What a Refund returns: always the amount paid on the Purchase, never the course's current price.

**Chargeback**:
A payment dispute a cardholder raises with their bank, outside our approval. Not a Refund Request.
