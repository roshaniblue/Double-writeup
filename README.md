# Double-writeup
Official writeup and solution guide for The Double — an OSINT CTF challenge.
# The Double — OSINT CTF Writeup

**Category:** OSINT  
**Difficulty:** Medium

## Challenge Overview

The Double is a fictional OSINT challenge involving two online identities that appear almost identical. They share similar photographs, captions, posts, and digital information.

The objective is to determine which identity is fake by investigating the available digital evidence.

## Intended Learning

This challenge focuses on:

- Social media OSINT
- Cross-platform verification
- Digital identity investigation
- Evidence provenance
- Identifying copied information
- Using independent sources to verify an identity

The main lesson is that repeated information does not necessarily mean independent confirmation.

---

## Solution

### 1. Compare the Instagram Profiles

Start by comparing the two Instagram profiles.

Both profiles contain the same photographs and captions, making them appear almost identical.

However, the posts are deliberately arranged in different orders.

Instead of comparing the position of posts, compare them using:

- Caption
- Date
- Time
- Photograph

This reveals that the same underlying posts exist on both accounts.

### 2. Cross-Check Other Platforms

Next, investigate the corresponding fictional Facebook and X profiles.

The same information appears across multiple platforms.

At first this may seem like confirmation that both identities are legitimate. However, the information could simply have been copied.

Therefore, duplicated information should not be treated as independent evidence.

### 3. Investigate Using the Terminal

The simulated terminal provides OSINT-style investigation tools.

Use the available username and registry queries to investigate both identities.

The results reveal connections between the accounts and the same fictional organization.

However, this still does not independently prove which identity is genuine.

### 4. Investigate the Work Contacts

Both profiles contain work contact information.

Instead of choosing one profile based on appearance, investigate both addresses.

This provides a new avenue for independent verification.

### 5. Verify the Email Addresses

Open the fictional Gmail interface and send the same verification message to both work addresses.

One address successfully exists and returns a response.

The other produces a delivery failure indicating that the address does not exist.

This provides the independent clue needed to identify the fabricated identity.

---

## Final Flag

```text
flag{lisa123-21:30}
