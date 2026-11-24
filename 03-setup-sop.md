# 03 · Setup SOP: Meta partnership ads

How a whitelisted creator ad goes from "agreed" to "live" on Meta.

> Meta renames and moves these screens often. This SOP covers the decisions and order of steps; confirm the exact clicks in Meta's Business Help Centre (search "partnership ads") before you set up.

---

## Before you start

- [ ] Rights agreed in writing ([`01-rights-checklist.md`](./01-rights-checklist.md))
- [ ] Creator has a **professional (creator or business) Instagram account**, set to public
- [ ] Your ad account, Page and Instagram account are connected in your business portfolio
- [ ] Conversion tracking is working (pixel / Conversions API / app events / lead form)
- [ ] The landing page matches what the creator says in the video

---

## Step 1 · Choose the permission type

| You want to… | Use |
|---|---|
| Promote **one specific post** | **Content-level** permission: the creator shares a partnership ad code for that post, or enables brand partners to boost it |
| Promote **several pieces over the partnership** | **Account-level** permission: request it through Meta's partnership ads tools; the creator approves it |

**Rule of thumb:** if you expect to test more than one piece of content with a creator, ask for account-level permission up front.

---

## Step 2 · Creator posts and grants permission

1. Creator posts the content and **tags your brand as a paid partner**, so the paid partnership label shows.
2. Creator grants the agreed permission:
   - **Content-level:** shares the partnership ad code with you, or turns on the setting that lets brand partners boost the post
   - **Account-level:** accepts your permission request
3. Log the code or approval, and the date, in your rights record.

---

## Step 3 · Build the ad in Ads Manager

1. **Create a campaign** with an objective that supports partnership ads (e.g. Leads, App promotion, Sales, Traffic).
2. **Ad set:** budget, audience, placements and schedule. **Set the end date to the last day of the usage window.**
3. **Ad level:**
   - Turn on **Partnership ad**
   - Add the creator's content: paste the **ad code**, or select the partner and post if you have account-level access
   - Check the **identity**: creator first, brand second (both show in the ad header)
4. Add your **ad copy, CTA and destination URL** with UTMs.
5. **Preview every placement**, especially Reels and Stories safe zones.
6. **Publish.**

### Naming convention
```
[Brand]_[Objective]_WL_[Creator]_[Hook]_[Format]_[Date]
e.g. AppX_Installs_WL_creatorname_HookA_Reel_2026-11
```

### UTMs
```
utm_source=meta&utm_medium=paid_social&utm_campaign=[campaign]&utm_content=wl_[creator]_[hook]
```

---

## Step 4 · First 72 hours

- [ ] Ad approved and delivering on all intended placements
- [ ] Conversions recording in Ads Manager **and** your analytics
- [ ] Comments moderated as agreed
- [ ] Spend pacing against plan
- [ ] Usage end date in your calendar

---

## Common setup problems

| Problem | Likely cause |
|---|---|
| Can't find the creator's post | Wrong permission type, expired code, or the post is no longer public |
| Ad stops delivering | Creator deleted, archived or made the post private, or revoked permission |
| Ad rejected | Paid partnership label missing, or ad policy issue in the creative |
| Conversions not showing | Tracking not set up on the destination, or UTMs missing |
