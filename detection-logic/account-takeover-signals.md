# Account Takeover Risk Signals

## Common Indicators
Potential account takeover activity may involve one or more of the following signals:

- Multiple failed login attempts followed by a successful login
- Login from a new or unrecognized device
- Login from an unusual geographic location
- Impossible travel between login events
- Password reset followed by rapid account changes
- MFA reset, bypass, or enrollment changes
- Changes to contact information shortly after login
- New payee, bank, or withdrawal destination added
- Unusual transaction behavior after authentication
- Access to the account at an unusual time
- Session behavior that differs from the user's normal pattern

## High-Risk Combinations
Risk increases when multiple signals occur together, such as:
- failed logins + successful login + device change
- password reset + MFA change + funds movement
- unusual login location + account profile update

## Detection Principle
A single signal may be benign. Multiple related signals in sequence are more likely to indicate account takeover risk.
