# Loan Management App — Requirements

## Actors
- **Borrower** — applies for loans, tracks status, views EMI schedule
- **Loan Officer** — reviews, approves or rejects applications
- **Admin** — manages users, views all loans, generates reports

## User Stories

### Borrower
- As a borrower, I want to register and log in securely.
- As a borrower, I want to apply for a loan with amount, purpose and tenure.
- As a borrower, I want to view my loan status (Pending/Approved/Rejected).
- As a borrower, I want to see my repayment schedule with EMI and due dates.
- As a borrower, I want to make payments against my loan.

### Loan Officer
- As a loan officer, I want to see all pending loan applications.
- As a loan officer, I want to approve or reject a loan with a comment.
- As a loan officer, I want to view a borrower's profile before deciding.

### Admin
- As an admin, I want to manage all users and assign roles.
- As an admin, I want to view all loans across all borrowers.
- As an admin, I want to generate loan summary reports.
gi
## Loan Status Workflow
PENDING → APPROVED → ACTIVE → CLOSED
                ↓
            REJECTED