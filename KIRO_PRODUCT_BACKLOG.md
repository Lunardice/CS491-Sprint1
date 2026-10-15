# CampusCycle — Product Backlog

A campus-only second-hand marketplace web app for Pace University students. Built with React and Firebase. Supports **UN SDG 12 (Responsible Consumption and Production)** by extending the life of goods and keeping items out of landfills.

**Legend**
- **Size:** S (small, ~1-2 days) · M (medium, ~3-5 days) · L (large, ~1-2 weeks)
- **Priority:** High (MVP / core value) · Medium (important, post-MVP) · Low (nice-to-have)

---

## 1. Accounts & Student Verification

| # | User Story | Size | Priority |
|---|-----------|------|----------|
| 1 | As a prospective user, I want to sign up with my Pace University email so that only verified students can access the marketplace. | M | High |
| 2 | As a new user, I want to receive and confirm an email verification link so that my account proves I belong to the campus community. | S | High |
| 3 | As a returning student, I want to log in and stay signed in across sessions so that I don't have to re-authenticate every visit. | S | High |
| 4 | As a user who forgot my password, I want to reset it via my student email so that I can regain access to my account securely. | S | High |
| 5 | As a student, I want to create and edit a profile with my name, photo, and campus so that other students know who they're dealing with. | M | Medium |
| 6 | As a student, I want to see another user's verified-student badge and rating so that I can trust who I'm trading with. | S | Medium |

## 2. Listings & Photos

| # | User Story | Size | Priority |
|---|-----------|------|----------|
| 7 | As a seller, I want to create a listing with a title, description, price, and condition so that buyers understand what I'm offering. | M | High |
| 8 | As a seller, I want to upload multiple photos of my item so that buyers can see its real condition before committing. | M | High |
| 9 | As a seller, I want to assign a category to my listing so that it appears in the right place for buyers browsing. | S | High |
| 10 | As a seller, I want to edit or delete my listing so that I can keep my listings accurate and current. | S | High |
| 11 | As a seller, I want to mark an item as "sold" or "claimed" so that it no longer shows as available. | S | High |
| 12 | As a seller, I want to save a listing as a draft so that I can finish posting it later. | S | Low |
| 13 | As a buyer, I want to view a full listing detail page with all photos and info so that I can decide whether to reach out. | S | High |
| 14 | As a seller, I want to see how many views my listing has received so that I know how much interest it's generating. | S | Low |

## 3. Freecycle Mode (Free Items)

| # | User Story | Size | Priority |
|---|-----------|------|----------|
| 15 | As a giver, I want to list an item as "free" in Freecycle mode so that I can give away things I no longer need instead of trashing them. | M | High |
| 16 | As a buyer, I want to filter for Freecycle (free) items so that I can find things offered at no cost. | S | High |
| 17 | As a giver, I want free items to be clearly badged as "Free" so that students instantly recognize no-cost offers. | S | High |
| 18 | As a student, I want to claim a free item so that the giver knows it's reserved for me. | M | Medium |
| 19 | As a giver, I want to set a claim deadline on a free item so that unclaimed items return to the pool for others. | S | Low |

## 4. Search, Browse & Filter

| # | User Story | Size | Priority |
|---|-----------|------|----------|
| 20 | As a buyer, I want to search listings by keyword so that I can quickly find a specific item. | M | High |
| 21 | As a buyer, I want to filter listings by category so that I can browse only the kinds of items I care about. | S | High |
| 22 | As a buyer, I want to filter by price range (including free) so that I only see items within my budget. | S | High |
| 23 | As a buyer, I want to sort results by newest, price, or condition so that I can prioritize what matters to me. | S | Medium |
| 24 | As a buyer, I want to filter by item condition so that I can find items that meet my quality expectations. | S | Medium |
| 25 | As a buyer, I want to save a search or favorite a listing so that I can return to items I'm interested in. | M | Low |

## 5. Messaging Between Students

| # | User Story | Size | Priority |
|---|-----------|------|----------|
| 26 | As a buyer, I want to message a seller directly about a listing so that I can ask questions and arrange a trade. | L | High |
| 27 | As a student, I want to see all my conversations in one inbox so that I can keep track of ongoing trades. | M | High |
| 28 | As a student, I want to receive a notification when I get a new message so that I can respond promptly. | M | Medium |
| 29 | As a student, I want to report or block another user so that I can protect myself from harassment or scams. | M | Medium |
| 30 | As a student, I want messages tied to a specific listing so that the conversation has clear context. | S | Medium |

## 6. Safe Campus Pickup

| # | User Story | Size | Priority |
|---|-----------|------|----------|
| 31 | As a student, I want to choose from a list of designated safe campus pickup locations so that exchanges happen in public, secure spots. | M | High |
| 32 | As a buyer and seller, I want to agree on a pickup location and time within our chat so that the handoff is coordinated. | M | Medium |
| 33 | As a student, I want to see pickup locations on a campus map so that I can easily find where to meet. | M | Low |
| 34 | As a student, I want to confirm when a pickup is completed so that the trade is marked done for both of us. | S | Medium |

## 7. Impact Tracker (SDG 12)

| # | User Story | Size | Priority |
|---|-----------|------|----------|
| 35 | As a student, I want to see a personal impact counter of items I've kept out of landfills so that I feel the environmental value of reusing. | M | High |
| 36 | As a student, I want to see a campus-wide impact dashboard so that the whole community can see our collective sustainability effort. | M | Medium |
| 37 | As a student, I want to see an estimated CO₂ or waste saved based on items reused so that the SDG 12 impact feels tangible. | M | Low |
| 38 | As a student, I want to earn sustainability badges for reuse milestones so that I'm motivated to keep participating. | M | Low |
| 39 | As an administrator, I want to view aggregate impact metrics so that I can report CampusCycle's contribution to SDG 12 goals. | M | Low |

## 8. Trust, Safety & Administration

| # | User Story | Size | Priority |
|---|-----------|------|----------|
| 40 | As an administrator, I want to review reported listings and users so that I can remove abusive content and keep the marketplace safe. | M | Medium |
| 41 | As a buyer, I want to leave a rating and review after a completed trade so that other students can judge a seller's reliability. | M | Medium |
| 42 | As a student, I want the app to be responsive and accessible on mobile and desktop so that I can use it however I'm browsing campus. | M | High |

---

## Suggested MVP Scope (High priority)

The following stories form a shippable first release that delivers the core SDG 12 value loop — verified students listing, finding, and exchanging second-hand and free items safely on campus:

- **Verification:** 1, 2, 3, 4
- **Listings:** 7, 8, 9, 10, 11, 13
- **Freecycle:** 15, 16, 17
- **Search/Filter:** 20, 21, 22
- **Messaging:** 26, 27
- **Safe pickup:** 31
- **Impact:** 35
- **Platform:** 42
