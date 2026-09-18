📸 Lumo (约拍) — a photographer × model booking platform

Lumo is a two-sided marketplace app that connects photographers and people who want to be photographed (约拍). Browse and match, book a shoot, chat, and receive the delivered photos — the full booking loop in one product.

Built as a working prototype of my own startup idea.

✨ What it does
Two-sided platform — separate flows for photographers (register, portfolio, availability) and clients (browse, match, book)
Swipe-to-match — discover photographers/models through a card-matching interface
Full booking loop — request → confirm → chat → shoot → delivery, with an order/status flow
17 connected screens — onboarding, login/signup, role select, home, booking, chat, confirm, delivery, portfolio, availability, orders, messages, profile, and more
Mobile-first design — built to feel like a real consumer app
🛠️ Built with
Single-page app with multi-screen routing (17 views)
Vanilla JavaScript state management + event-driven UI
HTML / CSS, mobile-first responsive layout
Google Fonts (Archivo, Hanken Grotesk, Space Mono)
Developed with an AI-assisted / rapid-prototyping workflow
⚙️ Setup / How to run

This is a self-contained static web app — no build step, no dependencies, no API keys required.

Option A — just open it:

Download index.html
Open it in any modern web browser (Chrome, Safari, etc.)

Option B — run a local server (optional):

bash
# from the project folder
python3 -m http.server 8000
# then open http://localhost:8000 in your browser

Environment: none required. An internet connection is only used to load Google Fonts.

💡 Why I built it

Demand for photo-shoot booking (约拍) is large, but it happens ad hoc through one-to-one DMs on social apps — there is no dedicated platform connecting the two sides. I wanted to take that idea and actually build it into a working, multi-screen product rather than leaving it as a pitch.

🚧 Status

Actively in development. Core screens and the booking flow are built; next steps include payments and a real backend.

<sub>Built by Ricky Zhao · github.com/RickyLGD</sub>
