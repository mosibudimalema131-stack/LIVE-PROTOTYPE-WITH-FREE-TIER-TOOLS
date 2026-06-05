How to use it:

Configure a loan in the Scout Agent panel — adjust the amount, savings score, harvest cycle, and risk flag to simulate different scenarios
Click "Run Simulation" — watch the workflow execute step-by-step with real logic:

Amounts < KES 15,000 with no risk flags → Guardian auto-approves
Risk flags (low or high) or amounts ≥ KES 15k → HUNT handoff to Hunter Agent
High fraud patterns → escalation with fraud alert badge


GUARD Safety Rails fire at every step — bias blocks, fraud alerts, and audit trail entries are generated live
PRIDE Loop indicators track which phase each agent is in (Prepare → Run → Inspect → Decide → Execute)
When routed to Hunter, you become the human-in-the-loop — click Approve or Decline to complete the flow
The Audit Trail on the final screen shows a timestamped log suitable for compliance

Three scenarios to try:

KES 12,000 + No risk + Harvest aligned → Scout→Guardian auto-approve
KES 20,000 + Low risk → Scout→Guardian→Hunter manual review
KES 8,000 + High fraud pattern → Fraud alert → Hunter escalation
You said: how do i share the prototypehow do i share the prototype9:00 AMClaude responded: You can share it a few ways:You can share it a few ways:
Easiest — share the conversation link
Click the Share button (top-right of this chat) → "Share conversation." Anyone with the link can view and interact with the prototype directly in their browser, no account needed.
Export as a standalone HTML file

Click the download icon on the prototype widget (top-right corner of the widget itself)
That saves it as an .html file you can host anywhere — GitHub Pages, Netlify Drop, or just email/attach it

Embed it
If you downloaded the HTML file, you can drop it into any web project or paste it into a tool like Netlify Drop (free, instant hosting) and share the generated URL.
The share conversation link is the quickest option for most cases — the prototype stays fully interactive for whoever opens it.You said: how hot on githubhow hot on github9:03 AMClaude responded: Here's the quickest path:Here's the quickest path:
1. Create a repo on GitHub
Go to github.com/new, name it something like agent-pride-prototype, set it to Public, click Create repository.
2. Add your HTML file

Download the prototype first (download icon on the widget)
Rename the file to index.html
In your new repo, click Add file → Upload files and drop it in
Commit the file

3. Enable GitHub Pages

Go to Settings → Pages in your repo
Under Source, select Deploy from a branch
Choose main branch, / (root) folder
Click Save

4. Get your live URL
After ~60 seconds, GitHub Pages gives you a public URL like:
https://yourusername.github.io/agent-pride-prototype
That's a permanent, shareable link — anyone can open it and interact with the full prototype, no login required.You said: HOW TO CREATE A TOKEN ON GITHUBHOW TO CREATE A TOKEN ON GITHUB9:09 AMClaude responded: A "token" on GitHub usually means one of two things — which do you need?A "token" on GitHub usually means one of two things — which do you need?You said: HOW TO GET URLHOW TO GET URL9:17 AMClaude responded: After you enable GitHub Pages, the URL appears right on the Pages settings screen.After you enable GitHub Pages, the URL appears right on the Pages settings screen. Here's exactly where to find it:

Go to your repo on GitHub
Click Settings (top menu of the repo)
Scroll down to Pages in the left sidebar
Your URL is shown in a green box at the top of that page — it looks like:

https://yourusername.github.io/agent-pride-prototype
If the green box isn't there yet — it takes about 60–90 seconds after you first enable Pages. Just refresh the Settings → Pages screen after a minute and it will appear.
Once you see it, that's your permanent shareable link — copy and send it to anyone.You said: COPY THE LINK FOR PROTOTYPE YOU CREATEDCOPY THE LINK FOR PROTOTYPE YOU CREATED9:20 AMClaude responded: I'm not able to generate or access URLs — I only created the prototype code inside this chat, it doesn't have a hosted link yet.I'm not able to generate or access URLs — I only created the prototype code inside this chat, it doesn't have a hosted link yet.
To get a shareable link, pick the quickest option:
Option 1 — Share this conversation (30 seconds)

Click the Share button at the top-right of this chat
Copy the link — anyone can open it and use the prototype immediately

Option 2 — Host it yourself (2 minutes)

Download the prototype (download icon on the widget)
Go to netlify.com/drop
Drag and drop the index.html file
Netlify instantly gives you a public URL like https://random-name.netlify.app

Option 1 is the fastest if you just want to share it right now.Want to be notified when Claude res
