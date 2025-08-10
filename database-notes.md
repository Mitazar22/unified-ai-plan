# UNIFIED AI Database Notes (From Bubble Auto-Generate)

## User Type
- email (text, built-in)
- activity_logs (list of texts)
- subscription_id (text)
- credits (number, default 0) - Add if missing
- last_updated (date) - Add if missing

## Credit Type
- amount (number)
- user (User)
- creator (User)
- modified_date (date)
- created_date (date)
- slug (text)
- transaction_id (text) - Add for Razorpay ref
- type (text, e.g., "prepaid") - Add

## Subscription Type
- [List fields from screenshot or add: plan_id (text), status (text), user (User)]

## Transaction Type
- [List fields: amount (number), date (date), user (User)]

## AIAgent Type
- [List fields: name (text), niche (text, e.g., "e-commerce")]

## ResponseCache Type (Custom Add)
- query (text)
- response (text)
- user (User)

## ActivityLog Type (Custom Add)
- user (User)
- action (text)
- date (date)

Notes: Trimmed extras like BubbleAIGeneratedAssets. Use for credit deduction (run agent → update Credit amount).
