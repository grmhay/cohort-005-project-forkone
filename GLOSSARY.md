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
One place on a Team Purchase, handed to a Learner by a coupon code. A Learner on a Team Seat has no Purchase of their own.

### Refunds

**Refund Request**:
The owner of a Purchase's written ask to have it refunded, which is Requested until a platform Admin approves or declines it. A Purchase has at most one Refund Request, whatever its outcome.
_Avoid_: Refund (for the request itself), Cancellation, Reversal, Chargeback

**Refund**:
The money returned to a learner when their Refund Request is approved. An approved Refund Request also ends the learner's enrollment in the course; a declined one refunds nothing.
_Avoid_: Reversal, Chargeback

**Refund Eligibility**:
Whether a Refund Request may be raised on a Purchase, judged at the moment it is raised: within the Refund Window, the Learner has watched under two hours and completed under half the lessons, and — for a Team Purchase — no Team Seat has been claimed. Watch time and completion count across all of a Learner's Purchases of the course.

**Refund Window**:
The fourteen calendar days after a Purchase, inclusive of the fourteenth day, during which a Refund Request may be raised.

**Refund Amount**:
What a Refund returns: always the amount paid on the Purchase, never the course's current price.

**Chargeback**:
A payment dispute a cardholder raises with their bank, outside our approval. Not a Refund Request.
