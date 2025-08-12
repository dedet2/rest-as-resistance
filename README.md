# Email Automations (Podia / ConvertKit)
Prepared: 2025-08-12

## 1) Airfare Upsell (sends after purchase)
Trigger: Tag `Booked Rest as Resistance Tour`

- Email 1 (immediate): `airfare_upsell_1.md`
- Email 2 (+48h): `airfare_upsell_2.md`
- Email 3 (+72h): `airfare_upsell_3.md`

Exit if tagged `Airfare Add-On Purchased` or `Declined Airfare`.

## 2) Welcome + What to Pack (post-purchase onboarding)
Trigger: Same tag above

- Email A (immediate): `welcome_1_confirmation.md`
- Email B (+3 days): `welcome_2_packing.md`
- Email C (+10 days): `welcome_3_predeparture.md`

## 3) Payment Plan Reminder
Trigger: Field/Tag `Payment Plan Active`
- Email: `billing_payment_plan_reminder.md` (send +7 days)

## 4) Post-Trip Loyalty & Referral
Trigger: Tag `Trip Completed`
- Email L1 ( +3 days ): `loyalty_referral_1.md`
- Email L2 ( +14 days ): `loyalty_referral_2.md`

---
All CTAs should point to your Podia checkout or a Calendly call link if preferred.
