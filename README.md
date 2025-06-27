# SITE Capstone Project

SITE Course Year: **2025**  
Cohort: **FutureTech LaunchPad (FTL)**  

**Team Member Names:**  
- Lilliana Cantero
- Sarvesh Tiku
- Paola Negrón

**Mentor Names:**  
- Jackson Herrick , Stand in for Alfa Salva (Sarvesh Tiku)
- Yiyu Lin, Stand In for Chockalingam Viswanathan (Paola Negrón)
- Maria Rivera (Lilliana Cantero)
- 

**Project Code Repository Links**
- Frontend Repo: [https://github.com/YourOrg/re-moda-frontend](#)  
- Backend Repo: [https://github.com/YourOrg/re-moda-backend](#)

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

### Solutions Brainstorm (Top Pick: “Closet Search” with NL Prompts)  
- **Closet Search:** natural-language queries (e.g. “Office casual, rainy day”) to auto-generate 3–5 outfit collages from your uploaded items.  
- **Virtual Try-On Studio:** apply edits (crop hem, add ruffles, recolor) live on garment photos.  
- **Dormancy Alerts:** flag items unworn for 60+ days and offer upcycling or donation suggestions.

### Core Feature List  
1. **Item Upload & Categorization**  
2. **Natural-Language Outfit Prompts**  
3. **Outfit Generation & Preview**  
4. **Save & Share Collages**  
5. **Basic Analytics & Dormancy Alerts**  

_Optional Add-Ons:_ Style Challenges, Community Gallery, AR Previews

---

## System Design Overview

### Architecture Diagram  
