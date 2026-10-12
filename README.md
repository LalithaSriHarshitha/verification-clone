# AICTE & EduSkills Verification Portal Clone

Pixel-perfect clone of the AICTE & EduSkills certificate verification page with the exact details from the internship certificate and animated tick verification mark (`checked.gif`).

## Project Structure
- `index.html`: Main verification interface.
- `verify.php`: Endpoint clone matching `pages/home/verify.php?cert=...`.
- `checked.gif`: Official animated verification badge icon.
- `aicte1million2.png`: High-resolution top header banner.
- `render.yaml`: Blueprint configuration for instant 1-click deployment to [Render](https://render.com).

## Deploying to Render
1. Go to your [Render Dashboard](https://dashboard.render.com).
2. Click **New +** and select **Static Site** (or **Blueprint**).
3. Connect your repository: `LalithaSriHarshitha/verification-clone`.
4. Settings:
   - **Build Command**: *(leave blank)*
   - **Publish Directory**: `.`
5. Click **Create Static Site**.
