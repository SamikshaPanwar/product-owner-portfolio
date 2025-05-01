# User Stories - KYC/AML Customer Onboarding

## 1. Upload Identity Documents
**As** a customer,  
**I want** to upload my identity documents during onboarding,  
**So that** my identity can be verified for account creation.

**Acceptance Criteria:**
- System must accept government-issued ID uploads (Passport, Driver’s License).
- Users must receive immediate upload confirmation or error feedback.
- Allowed file formats: JPG, PNG, PDF.

---

## 2. Real-Time Document Validation
**As** a system,  
**I want** to validate uploaded documents for completeness and clarity,  
**So that** only valid documents are submitted for KYC checks.

**Acceptance Criteria:**
- System must detect blurry/incorrect uploads and prompt re-upload immediately.
- Invalid uploads must not proceed to verification.

---

## 3. Progress Tracking
**As** a customer,  
**I want** to see a progress bar during onboarding,  
**So that** I know how many steps are completed and what's left.

**Acceptance Criteria:**
- Progress must update in real-time after each completed step.
- Display percentage completion.

---

## 4. AML Watchlist Screening
**As** a system,  
**I want** to screen customer information against AML watchlists,  
**So that** high-risk profiles can be flagged for review.

**Acceptance Criteria:**
- Integrate with external watchlist APIs (OFAC, PEP lists).
- Flag high-risk matches for manual compliance review.
