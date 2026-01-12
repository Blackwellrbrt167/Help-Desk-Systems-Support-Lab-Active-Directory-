# T003_Account_Lockout_Troubleshooting

## Ticket Summary
- **Problem:**
    User account was locked following multiple unsuccessful login attempts.
- **Impact:**
    User was unable to authenticate to their domain account, preventing access to required systems and interrupting assigned work duties. 
- **Root Cause:**
    Account lockout policy triggered after exceedig the maximum allowed login attempts due to repeated authentication failures with an incorrect password.
- **Resolution:**
    Verified user identity.  Unlocked the user account in Active Directory and reset the password.  Suer was instructed to log in immediately and update their password upo first access. 
- **Prevention:**
    Educated the user on proper password management practices, including avoiding repeated failed attempts and using the organization-approved password manager to reduce future lockouts. 
