# DJ Room (GitHub Pages)

Deploy steps (for **Patongkoduo**):

1. Create repo: `dj-room` (Public).
2. Put the single file **index.html** at repo root (lowercase filename).
3. Go to **Settings → Pages** → Source: `Deploy from a branch` → Branch: `main` (root) → Save.
4. Your site will be live at: `https://Patongkoduo.github.io/dj-room/`

### Firebase setup
- In Firebase Console → Authentication → **Authorized domains**, add:
  - `Patongkoduo.github.io`
- Enable **Anonymous sign-in** (Authentication → Sign-in method).
- Replace `firebaseConfig` placeholders in `index.html` with your project values.
