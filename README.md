# SITE Capstone Project

SITE Course Year: **2025**  
Cohort: **FutureTech LaunchPad (FTL)**  

**Team Member Names:**  
- Lilliana Cantero
- Sarvesh Tiku
- Paola Negrón

**Mentor Names:**  
- Jackson Herrick , Temporary stand in for Alfa Salva (Sarvesh Tiku)
- Yiyu Lin, Temporary stand In for Chockalingam Viswanathan (Paola Negrón)
- Maria Rivera (Lilliana Cantero)

**Project Code Repository Links**
- Frontend Repo: [[https://github.com/YourOrg/re-moda-frontend](https://github.com/Re-Moda/Re-Moda-Frontend)]  
- Backend Repo: [[https://github.com/YourOrg/re-moda-backend](https://github.com/Re-Moda/Re-Moda-Backend)]

---

## Project Overview

**Re: Moda** is an AI-powered “Digital Closet & Outfit Generator” that helps users catalog the clothes they already own, experiment with new outfit combinations via natural-language prompts, and receive personalized upcycling or donation recommendations for items they’re not wearing. On the consumer side, users upload photos of their garments, and the app classifies each piece, lets them generate outfit collages (“What should I wear to a beach wedding?”), and even try virtual edits like hemming or color-blocking. On the business side, fashion brands and sustainable retailers can access a dashboard and APIs to view aggregated usage trends, demand-forecast insights, and partner-ready upcycling kits for slow-moving inventory.

**Deployment Website:** [https://placeholder-for-now.com](#)

### Open-source libraries used

- **Frontend**
  - React / React Native
  - Tailwind CSS / NativeWind
  - react-easy-crop
- **Backend**  
  - Node.js + Express
  - Prisma (ORM)
  - Multer (file uploads)
- **ML Microservice**
  - Python + FastAPI  
  - PyTorch / TensorFlow (vision & diffusion models)  
  - CLIP
- **Infrastructure & DevOps**  
  - Docker / Docker Compose
  - GitHub Actions 
  - AWS S3, RDS (Postgres), CloudFront 

---

## Planning Directory

All of our project planning lives in `planning/`:

- **project_proposal.md** — problem statements, solution brainstorm, feature lists  
- **system_design.md** — PERN-stack architecture & ML microservice design  
- **wireframes/** — Figma export links and PNGs  
- **roadmap.md** — week-by-week sprint plan  

---

## Ideation Summary

### Themes  
1. **Wardrobe Management & Personal Style**  
2. **AI-Driven Outfit Visualization**  
3. **Sustainable Fashion & Upcycling**

### Problem Statements  
1. **“Many people own dozens of clothing items but rarely wear more than 20% of them, and struggle to remember what’s in their closet when planning outfits.”**  
2. **“DIY fashion-lovers find it hard to imagine how simple edits (hemming, color blocking, patches) will look on their actual garments before committing time and materials.”**  
3. **“Consumers are motivated to be more sustainable but lack personalized suggestions for when to upcycle or donate items that have gone unworn for months.”**

Despite growing consumer awareness around sustainability, the United States still discards over 11.3 million tons of post-consumer textiles into landfills each year—nearly 7.7 % of all municipal solid waste—while only a tiny fraction is actually recycled (just 0.1 % of clothing collected by charities). Fast-fashion consumption has exacerbated the crisis: the average American throws away 81.5 pounds of clothing annually, and garments are kept for half as long as they were two decades ago, leading to the rapid turnover of wardrobes and mounting environmental impacts (water use, greenhouse-gas emissions, microplastic release etc.) Without intuitive, accessible tools to guide individuals in upcycling and mindful wardrobe management, this cycle of overconsumption and waste will continue, straining landfill capacity and depleting scarce resources.

### Target Audience

Our platform is designed for urban, sustainability-minded Millennials and Gen Z (ages 18–35) in the United States, a demographic that:

- **Buys new clothing frequently** — 36 % of Gen Z purchases new apparel at least once a month 
- **Faces high wardrobe turnover** — On average, they discard over 81.5 pounds of clothing per person each year
- **Embraces repair and reuse** — 57 % already repair or repurpose garments due to cost-of-living pressures, indicating a readiness to adopt upcycling solutions 
- By meeting users where they are—with a simple mobile/web interface that transforms “old” clothing into inspiring, shareable upcycling ideas—we empower this audience to reduce waste, extend garment lifecycles, and join the circular-fashion movement.

### Solutions Brainstorm (Top Pick: “Closet Search” with NL Prompts)  
- **Closet Search:** natural-language queries (e.g. “Office casual, rainy day”) to auto-generate 3–5 outfit collages from your uploaded items.  
- **Virtual Try-On Studio:** apply edits (crop hem, add ruffles, recolor) live on garment photos.  
- **Dormancy Alerts:** flag items unworn for 60+ days and offer upcycling or donation suggestions.
- By meeting users where they are—with a simple mobile/web interface that transforms “old” clothing into inspiring, shareable upcycling ideas—we empower this audience to reduce waste, extend garment lifecycles, and join the circular-fashion movement.


### Core Feature List  
1. **Item Upload & Categorization**  
2. **Natural-Language Outfit Prompts**  
3. **Outfit Generation & Preview**  
4. **Save & Share Collages**  
5. **Basic Analytics & Dormancy Alerts**  

_Optional Add-Ons:_ Style Challenges, Community Gallery, AR Previews

---

## System Design Overview
<img width="936" height="883" alt="Screenshot 2025-07-11 at 16 17 38" src="https://github.com/user-attachments/assets/2645b915-66fe-4082-bf44-63e61c89699c" />

### Architecture Diagram  
<img width="1083" height="825" alt="Screenshot 2025-07-11 at 16 18 00" src="https://github.com/user-attachments/assets/6a89cad6-9f8a-4a27-9bdf-2eb52eb411e4" />
<img width="1370" height="755" alt="Screenshot 2025-07-11 at 16 18 18" src="https://github.com/user-attachments/assets/f86d5241-fa03-453c-a3be-058cd0b74a4f" />

### Trello Board
<img width="1426" height="719" alt="Screenshot 2025-07-11 at 16 18 45" src="https://github.com/user-attachments/assets/cea9ef3d-f47d-4af9-9694-27708491e0bf" />
