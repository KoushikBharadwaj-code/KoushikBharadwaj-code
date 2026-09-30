# Koushik Bharadwaj S

**CS @ SRMIST** · Building things that break in interesting ways, then fixing them.

I care about the parts of software most people skip — what happens when two requests hit the same row at once, when an API starts throttling you mid-feature, when "it works on my machine" isn't good enough. I'd rather spend an extra day on a system that doesn't quietly corrupt data than ship something that looks done.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/koushik-bharadwaj-65a528329/)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/Koushik_Bharadwaj/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:skoushikbharadwaj@gmail.com)

---

### What I've actually shipped

**SlotSync — a booking system that refuses to double-book**
The problem: two people hit "book" on the same slot within milliseconds of each other. Most demo booking apps just... let that happen. SlotSync uses Firestore transactions with retry logic to make sure it can't — race conditions resolved at the data layer, not papered over in the UI.
`Next.js` `React` `Firestore` `TypeScript`

**RxGuard — catching dangerous prescriptions before they happen**
Built for a real failure mode: patients seeing multiple specialists who don't talk to each other, ending up on conflicting or duplicate medications. RxGuard flags drug-drug interactions and timing conflicts, with a TypeScript model (discriminated unions, not string-typed chaos) built to make bad states unrepresentable.
`Next.js` `React` `TypeScript` `Tailwind`

**Gusto Meets — shipping inside a real startup, not a solo repo**
Intern engineering work for a live product (terrace rentals by the hour). Integrated a Gemini API into an existing chatbot — when I hit persistent rate-limiting in production, I didn't just wait it out, I built a keyword-matching fallback covering ~15 topic categories so the bot degrades gracefully instead of dying. Also wrote the technical spec for the camera/photo-storage pipeline: Expo Camera SDK, Supabase Storage, Postgres schema, RLS policies.
`React` `Gemini API` `Supabase` `PostgreSQL`

---

### Stack

![](https://skillicons.dev/icons?i=ts,js,react,nextjs,nodejs,py,c,cpp,mysql,firebase,html,css,git,github)

---

### Numbers, not vibes

![](https://github-readme-stats.vercel.app/api?username=KoushikBharadwaj-code&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117&title_color=58A6FF&icon_color=58A6FF&text_color=8b949e)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=KoushikBharadwaj-code&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58A6FF&text_color=8b949e)

---

If you're looking at this because of a resume or an application — the two projects above aren't toy tutorials, they're built around the specific way real systems fail. Happy to walk through either one.

[GitHub](https://github.com/KoushikBharadwaj-code) · [LinkedIn](https://www.linkedin.com/in/koushik-bharadwaj-65a528329/) · [LeetCode](https://leetcode.com/Koushik_Bharadwaj/)
