# Pre-Campaign Checklist

A practical checklist for preparing and launching
CRM campaigns based on hands-on experience as IT Project Ops.

> Tools covered: CleverTap, MoEngage, Stamps CRM System

---

## Overview

This checklist ensures every campaign is properly prepared,
reviewed, and approved before going live. Campaigns are
executed based on a pre-set schedule with content and
segmentation prepared by the marketing team.

**Key Rules:**
- Campaign request must be submitted minimum **H-2** before launch
- Internal and client approval must be completed by **H-1**
- No last-minute requests to allow proper review and minimize errors

---

## Campaign Types

| Campaign Type | Channel | Frequency | Trigger |
|--------------|---------|-----------|---------|
| Daily push notification | Push Notif | Daily | Scheduled |
| Email blast | Email | 4x/month | Scheduled |
| Voucher campaign | Push / Email | As needed | Manual |
| Bonus point | Push / Email | As needed | Manual |
| Rewards campaign | Push / Email | As needed | Manual |
| Transaction bonus | Push / Email | As needed | Transactional |
| Signup bonus | Push / Email | As needed | Event-based |
| Birthday voucher | Push / Email | Daily | Birthday trigger |
| Birthday reminder | Push / Email | As needed | Pre-birthday trigger |
| Point expiry reminder | Push / Email | As needed | Expiry trigger |
| Voucher reminder | Push / Email | As needed | Expiry trigger |

---

## Pre-Campaign Checklist

### H-2 — Request & Preparation
- [ ] Receive campaign request from marketing team
- [ ] Confirm campaign type and channel
  (push notification / email / WhatsApp)
- [ ] Confirm campaign content is ready:
  - Copy / message text
  - Images or banners (if needed)
  - CTA link or deep link
- [ ] Confirm audience segmentation is defined
- [ ] Confirm scheduled launch date and time
- [ ] Set up campaign on CleverTap / MoEngage / Stamps CRM

### H-1 — Preview & Approval
- [ ] Run campaign preview on platform
- [ ] Check content display across devices (mobile/desktop)
- [ ] Verify audience segment size and targeting
- [ ] Verify scheduled date and time
- [ ] Send preview for internal approval
- [ ] Send preview for client approval
- [ ] Collect approval confirmation from both parties
- [ ] Schedule campaign on platform after approval received

### Launch Day
- [ ] Confirm campaign is scheduled correctly
- [ ] Monitor campaign delivery after launch:
  - Sent count
  - Delivery rate
  - Open rate (for push/email)
- [ ] Flag any delivery issues to dev team if needed
- [ ] Report campaign launch status to client

---

## Automated Journey Setup

Beyond one-time campaigns, automated journeys are set up
to trigger messages based on user behavior or lifecycle events.
Content is provided by the marketing team — ops aligns
the logic and builds the journey in CleverTap.

**Estimated setup time:** ~7 days including revisions and final sign-off

### Journey Types

| Journey | Trigger | Goal |
|---------|---------|------|
| Abandoned Cart | User adds to cart but doesn't checkout | Drive checkout completion |
| Re-engagement | User inactive for X days | Bring back lapsed users |
| Post-purchase | User completes a transaction | Increase repeat purchase |
| Birthday (H-7 to H+7) | User's birthday window | Drive spending during birthday period |
| Point Expiry Reminder | Points about to expire | Encourage redemption before expiry |
| Voucher Reminder | Voucher about to expire | Encourage voucher usage |

### Journey Setup Checklist
- [ ] Receive journey brief and content from marketing team
- [ ] Align trigger logic and entry/exit conditions
  with digital marketing team
- [ ] Map out full journey flow before building:
  - Entry trigger
  - Wait / delay steps
  - Branching conditions (opened / not opened, etc.)
  - Exit conditions
- [ ] Build journey in CleverTap
- [ ] Run internal review and collect revision notes
- [ ] Revise and retest until logic is confirmed
- [ ] Get final approval from digital marketing team and client
- [ ] Set journey to live
- [ ] Monitor journey performance for first few days

---

## Common Issues & Notes

| Issue | Cause | Resolution |
|-------|-------|------------|
| Low delivery rate | Segment too narrow or inactive users | Review segment with marketing team |
| Campaign not sent | Scheduling error | Recheck schedule settings on platform |
| Wrong content sent | Not reviewed before approval | Always run preview before requesting approval |
| Late request | Last-minute submission | Remind client/marketing of H-2 rule |
| Journey not triggering | Wrong entry condition | Recheck trigger logic with digital marketing team |
| Users entering wrong branch | Incorrect branching condition | Review and fix branching logic in CleverTap |

---

## Tools Used

- **CleverTap** — push notification, email campaign & journey management
- **MoEngage** — push notification & email campaign management
- **Stamps CRM System** — internal push & email blast

---

> This template is generalized for reference purposes.
> No proprietary or confidential client data is included.
