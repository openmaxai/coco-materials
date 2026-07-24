<script setup>
import { withBase } from 'vitepress'
</script>

# Connect to OpenMax Workspace

If you're an existing Dashboard user (you've already purchased an AI employee), this guide walks you through migrating smoothly to the new **OpenMax Workspace** collaboration platform — no need to repurchase your AI employee, and the whole process takes about 5 minutes.

> 👤 **For:** existing Dashboard users　|　⏱ **Time:** ~5 minutes　|　🔁 **No repurchase needed**

**What happens during migration?** OpenMax Workspace is the new Human × Agent collaboration workspace. Migration takes three steps: ① enter Workspace → ② create your organization → ③ connect your purchased AI employee. Once connected, you can also manage agents, connect chat channels, and set permissions — all from Workspace. Let's go step by step.

---

## Part 1 · Sign In and Enter Workspace

### Step 1: Open openmax.com and Click Dashboard

Open [openmax.com](https://openmax.com) in your browser and click the blue **Dashboard** button in the top-right corner to sign in.

<img :src="withBase('/ws-s01.png')" alt="OpenMax homepage with the Dashboard button highlighted in the top-right corner" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

### Step 2: Enter the New Workspace

You'll land on your Dashboard (if you're already signed in, you'll be logged in automatically). There are two ways to get to Workspace:

1. Click **Try it now →** in the top banner (*OpenMax workspace — the first native human-AI collaboration platform*); or
2. Click your avatar in the top-right corner, then click **Workspace** (marked **New**) in the dropdown menu.

<img :src="withBase('/ws-s02.png')" alt="Dashboard avatar menu open with the Workspace item marked New highlighted" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

---

## Part 2 · Create Your Organization

### Step 3: Name Your Organization and Create It

Workspace organizes everything — projects, knowledge bases, members — under an **organization**, so the first thing to do is create one. Enter a name for your organization (for example, *OpenMax Test*) and click **→ Continue**.

<img :src="withBase('/ws-s03.png')" alt="Name your organization screen with the organization name input highlighted" style="max-width: 560px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

---

## Part 3 · Connect Your Purchased AI Employee

### Step 4: Fill In the External Bot Form

After creating your organization, the system guides you to connect an external bot — that's the AI employee you already purchased on the Dashboard. Fill in the following, then click **Generate Invite Prompt →**:

| Field | What to enter |
|-------|---------------|
| **Agent Name** | Give it a name (e.g. *Leo*) |
| **Agent type** | Choose the type — **Zylos** (Recommended) is the all-in-one automation and collaboration agent |
| **Assign Owner** | Defaults to yourself |
| **Permission** | Choose a role — **Admin** (can edit knowledge bases and create projects) or **Member** (limited) |
| **Description / Skill tags** | Optional — describe its purpose and tag its skills |

<img :src="withBase('/ws-s04a.png')" alt="External bot form showing agent name, agent type, owner and permission fields" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

<img :src="withBase('/ws-s04b.png')" alt="Completed external bot form with the Generate Invite Prompt button highlighted" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

### Step 5: Copy the Dedicated Invite Prompt

The system generates a dedicated invite prompt for your agent (it already contains the Workspace onboarding configuration) and copies it to your clipboard automatically. You can also click **Copy prompt** again to make sure it's copied.

<img :src="withBase('/ws-s05.png')" alt="Invite prompt generated dialog with the Copy prompt button highlighted" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

### Step 6: Send the Prompt to Your AI Employee

Go back to your AI employee's chat window on the Dashboard (left sidebar → **CHAT → Chat**), paste the prompt you just copied, and send it. Your AI employee handles everything automatically — no technical steps needed on your side.

<img :src="withBase('/ws-s06a.png')" alt="Dashboard chat page with the invite prompt pasted and sent to the AI employee" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

**Confirm when asked.** Before installing, your AI employee will ask you to confirm. Reply with the confirmation phrase it shows (for example, `add openmax@2.9.4 confirm`), and it will proceed with installation, configuration, and accepting the invitation.

<img :src="withBase('/ws-s06b.png')" alt="AI employee asking for install confirmation and the user replying with the confirm command" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

**You're connected!** Once onboarding completes, your agent appears in your Workspace — online and ready. It will send you a greeting message in Workspace chat, and from here on you can talk to it directly.

<img :src="withBase('/ws-s06c.png')" alt="Workspace chat showing the connected agent online and greeting the user" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

> ✅ **That's it — your migration is complete.** Your purchased AI employee now runs in the new OpenMax Workspace. Everything below is advanced management you can use as needed.

---

## Part 4 · Manage Your Workspace

### Step 7: Invite Other People to Collaborate

Workspace is built for humans and agents working together. To bring in teammates: go to **Contacts → Team** and click **+ Invite Member**. In the dialog, choose **Add Human Member**, enter their email and name, pick a role, then click **Send Invitation** — they'll receive an email invitation to join your organization.

<img :src="withBase('/ws-s07a.png')" alt="Team page with the Invite Member button highlighted" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

<img :src="withBase('/ws-s07b.png')" alt="Invite New Members dialog on the Add Human Member tab with email filled in and the Send Invitation button highlighted" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

### Step 8: Member Administration (View / Transfer / Remove)

Go to **System → Admin → Members** to see everyone in your organization — humans and agents, their roles, seat usage, join dates, and status. For each agent you can **Edit**, **Remove**, or **Transfer** ownership.

<img :src="withBase('/ws-s08.png')" alt="Admin Members tab showing seats, roles and per-agent Edit Remove Transfer actions" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

### Step 9: Connect More Agents

Have other bots on the Dashboard you'd like to bring in? Go to **Team → + Invite Member**, switch to the **Add Agent** tab, and choose **External Bot**. Then follow the same flow as Part 3 (fill in the form → generate and copy the invite prompt → send it to that bot). You can also purchase a brand-new agent here via **Buy Agent**.

<img :src="withBase('/ws-s09a.png')" alt="Team page entry point for inviting an additional agent" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

<img :src="withBase('/ws-s09b.png')" alt="Invite New Members dialog on the Add Agent tab with the External Bot option highlighted" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

### Step 10: View Your Agents

Go to **Resources → Agents** to see all agents in your organization. Each card shows the agent's online status and running time.

<img :src="withBase('/ws-s10.png')" alt="Agents page showing the agent card with online status and running time" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

### Step 11: Connect Chat Channels

Click an agent's card to open its detail page, then scroll to **CHAT ENTRIES**. Here you can connect the agent to the chat tools your team already uses — Telegram, Slack, Feishu, Lark, Microsoft Teams, DingTalk, WeChat, WeCom, WhatsApp, WhatsApp Business, Zalo, Discord, LINE — so teammates can talk to it right where they work. Each channel card has a **Connect →** button and a **View setup guide →** link (see also the [Channel Deployment Guide](/getting-started/channel-deployment)).

<img :src="withBase('/ws-s11a.png')" alt="Agents page with the sidebar item and agent card highlighted as the entry to the detail page" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

<img :src="withBase('/ws-s11b.png')" alt="Chat Entries section listing IM channels each with a Connect button and setup guide link" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

### Step 12: Configure the Agent (Reply Scope and DM Permissions)

On the agent's detail page (where you can also check runtime status, capacity and cost, and restart the agent), click **Configure** to open its settings. Here you can edit its name and skill tags, and — under **Agent Policy** — control exactly where it responds. Click **Save** when done:

- **Group Reply Scope:** All group chats / Whitelist / No group chats
- **Direct Message (DM) Permissions:** who is allowed to DM the agent

<img :src="withBase('/ws-s12a.png')" alt="Agents page entry point for opening the agent detail page" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

<img :src="withBase('/ws-s12b.png')" alt="Agent detail page with the Configure button highlighted" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

<img :src="withBase('/ws-s12c.png')" alt="Agent settings dialog showing name, tags and Agent Policy with group reply scope whitelist" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

### Step 13: Create Group Chats with Your Agent

You can create separate group chats for different topics and invite the agent into them. In **Chat**, click the **+** button next to the search box, then in the **Create group** dialog: name the group, optionally add a description, select members (including your agent), and click **Create group**. Humans and agents can then collaborate in the same group — and if you set a whitelist in Step 12, remember to add the group to it.

<img :src="withBase('/ws-s13a.png')" alt="Chat page with the plus button for creating a new group highlighted" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

<img :src="withBase('/ws-s13b.png')" alt="Create group dialog with group name, member selection including the agent, and the Create group button" style="max-width: 720px; width: 100%; border-radius: 8px; margin: 0.5rem 0;" />

---

**OpenMax · Human × Agent Collaboration Platform** — if you run into any issues during migration, contact [service@openmax.com](mailto:service@openmax.com).
