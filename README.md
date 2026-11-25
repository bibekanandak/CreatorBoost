# ⚡ CreatorBoost — Social Growth & Micro-Task Engagement Web App

**Live Demo:** [https://creatorbost.netlify.app](https://creatorbost.netlify.app)

CreatorBoost is a mobile-first, serverless web application designed to help content creators organically grow engagement through a verified peer-to-peer micro-task economy and referral rewards.

## 🚀 Key Features
* **Dual-Wallet Ledger System:** Separates free earned **Reward Points** (from completing video watch/comment tasks) from UPI-purchased **Paid Ad Credits** (for launching promotional campaigns).
* **Anti-Abuse & Streak Engine:** Enforces 1-user-1-claim task deduplication and IST timezone-synced 7-day daily streak bonuses (`+10,000 Pts`).
* **Two-Tier Viral Referral System:** Automated URL attribution (`?ref=UID`) awarding `+1,000 Pts` on the invitee's first verified task and `+49,000 Pts` upon completing a 7-day streak.
* **Role-Based Admin Control Panel:** Real-time moderation dashboard for approving task proofs, verifying UPI UTR payment requests, managing order statuses (`Pending → Processing → Completed/Refunded`), and deleting live tasks.

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3 (Custom Dark UI, Flexbox/Grid), Vanilla JavaScript (ES6+)
* **Backend & Database:** Google Firebase Authentication & Cloud Firestore (Real-Time `onSnapshot` listeners)
* **Hosting:** Netlify CI/CD
