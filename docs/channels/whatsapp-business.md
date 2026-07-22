# WhatsApp Business (Official API) — Usage Tips

Use your OpenMax AI employee on the official WhatsApp Business Platform (Cloud API) — a verified business number your customers can message from their everyday WhatsApp app. Built for customer-facing business messaging at scale.

> New here? See the [WhatsApp Business Deployment guide](../getting-started/channel-deployment#whatsapp-business) to connect your business number first.

> **WhatsApp Business vs. WhatsApp:** This channel uses Meta's **official Cloud API** — you verify a business phone number by OTP, with no phone or QR linking. The [WhatsApp](./whatsapp) channel links a regular WhatsApp account via QR code instead. Choose this one for official, customer-facing business use.

## Basic Usage

### Direct Messages
Customers send a message to your business number from their normal WhatsApp app — no special command needed. The first person to DM the number becomes the **Owner** with full access.

### Group Chats
Not supported — the official WhatsApp Business Cloud API is **1:1 (DM) only**. If you need group chat support, use the [WhatsApp](./whatsapp) channel instead.

## Best Use Cases

### Customer-Facing Support
The official API is built for business-to-customer messaging:
- Answer FAQs and product questions instantly, around the clock
- Triage and route incoming requests
- Serve customers on the app they already use — no install needed

### Official Business Presence
- Your business display name is shown to customers, backed by Meta's official platform
- No linked phone to keep online — the connection is server-to-server and stays up on its own
- Delivery and read status is tracked for outbound messages

## Pro Tips

**24-hour window**: WhatsApp allows freeform replies within 24 hours of the customer's last message. Outside that window, only pre-approved **template messages** can be sent — the AI employee handles this automatically.

**Media in, media out**: Customers can send images, documents, audio, and video — the AI employee receives them and can reply with text, images, and documents.

**Owner**: The first person to DM the business number becomes the Owner, who always has full access regardless of access settings.

**Access control**: By default only the Owner can DM the number. Adjust the DM policy (owner / allowlist / open) to open it up to customers or a team.

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Bot not responding | Confirm the WhatsApp Business card shows **Connected** in the employee detail page, then send another message |
| Replies not arriving after a long pause | The 24-hour customer-service window has likely closed — send a new message from the customer side to reopen it |
| Can't add the bot to a group | Group chats are not supported by the official Cloud API — this channel is 1:1 only |
| Others can't message the bot | By default only the Owner can chat. Enable Allowlist or Open mode to grant access |
| Want to disconnect | Click the **Disconnect** button on the WhatsApp Business card in the employee detail page |
