# Cadence

An online course platform: instructors publish courses, students enroll and learn, and teams buy access in bulk.

## People

**Student**:
A person taking a course.
_Avoid_: Learner, user (outside admin contexts)

**Buyer**:
The person who paid for a Purchase. A Buyer of Seats may never take the course themselves.
_Avoid_: Purchaser

## Access and payment

**Purchase**:
A payment for a course, either for the Buyer's own access or for a batch of Seats.
_Avoid_: Order

**Enrollment**:
A Student's access to a course. It comes from a Purchase or from claiming a Seat.

**Seat**:
One place on a team's Purchase, which a single Student can Claim to get an Enrollment.
_Avoid_: Coupon, licence, team licence

**Code**:
The single-use code that identifies a Seat and lets a Student Claim it.
_Avoid_: Coupon code

**Claim**:
To use a Seat's Code to take that Seat and gain an Enrollment.
_Avoid_: Redeem

**Refund**:
A Student's request to get their money back for a Purchase, reviewed by hand and then approved or declined. It is always for the amount paid on that Purchase.
_Avoid_: Cancellation, Reversal, Chargeback

## Learning

**Question**:
One item in a quiz.

**Comment**:
A message a Student or instructor posts on a lesson.
_Avoid_: Question, Discussion
