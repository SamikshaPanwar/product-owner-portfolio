# User Stories - Price Lock Feature

## 1. Reserve Flight Price
**As** a customer,  
**I want** to reserve the current flight price for 48 hours,  
**So that** I can finalize my travel plans without worrying about price increases.

**Acceptance Criteria:**
- User can click a "Lock Price" button on the flight details page.
- User must pay a small non-refundable fee to activate Price Lock.
- A confirmation email must be sent after locking the price.
- Price must be held for the selected duration (24/48/72 hours).

---

## 2. Choose Lock Duration
**As** a customer,  
**I want** to select how long to lock the price (24, 48, or 72 hours),  
**So that** I have flexible options based on my needs.

**Acceptance Criteria:**
- Options must be shown with associated fees.
- Default duration is 48 hours if none selected.
- Longer locks cost higher fees.

---

## 3. Notify Before Expiration
**As** a customer,  
**I want** to receive a notification before my Price Lock expires,  
**So that** I can complete my booking in time.

**Acceptance Criteria:**
- Notification email must be sent 6 hours before lock expiration.
- Notification must include a direct link to complete the booking.
