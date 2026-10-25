# Posts

Images: `results.png` for LinkedIn, `x-post.png` for X.

---

## LinkedIn

Your phone is probably running dozens of apps you never asked for.

Ad feeds, pre-installed Facebook apps, trackers, and apps that keep waking the phone in the background, all eating your battery.

You can clean this up yourself. No root, no tech skills. Just a USB cable, your laptop and Claude Code.

Plug the phone in and ask in plain English: "analyse my phone, debloat it and remove power-draining apps."

It works on any Android phone. Here's what it did on my Realme GT 6:
→ Read the battery stats and found the real culprits. Two apps had woken my phone over 1,100 times since the last restart
→ Removed 53 apps: ad feeds, Facebook stubs, trackers, duplicates I'd forgotten about
→ Blocked 5 apps from running in the background. They still work when I open them
→ Ran a security check: no spyware, no hidden admin apps, mic only used while apps were on screen
→ Took SMS access away from 10 shopping apps that could read my bank OTPs

The result after one day:
🔋 Screen-on time per charge: 5h 44m → 7h 17m
📵 Background wake-ups from those two apps: 0

The best part: it asked before every change, kept an undo script, and gave honest numbers. When a first 2-hour reading looked worse, it went back to the full-day data instead of claiming a win.

One tip: check its list before saying yes. Two apps I actually use went too, and I had to reinstall them from the Play Store.

Everything I changed, the security checks and the undo script:
👉 https://github.com/muniraja96/realme-gt6-debloat

Try it on your phone and tell me how many apps you got rid of.

#AI #ClaudeCode #Android #Productivity

---

## X

Your Android phone is full of apps quietly draining the battery.

Plug it into your laptop, give Claude Code one prompt, and it will:
• find what's waking your phone
• remove the bloat
• block background drainers
• run a security check

My Realme GT 6: 53 apps gone, screen-on time 5h 44m → 7h 17m 🔋

No root. Undo script included.

https://github.com/muniraja96/realme-gt6-debloat
