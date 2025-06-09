# 🐾 Furry Friend - PocketBase Backend Setup (Quick Guide)

1. **Create a PocketBase Cloud Account:**  
   Go to [pocketbase.io/cloud](https://pocketbase.io/cloud) and sign up for a free account.

2. **Create a New Project:**  
   Follow the prompts to create your PocketBase project in the cloud.

3. **Import the Database Schema:**  
   In the PocketBase Cloud dashboard, go to **Settings** → **Import collections** and upload the `pb_schema.json` file from this repository.

4. **Get Your API URL:**  
   Copy your PocketBase Cloud API URL (e.g. `https://your-project-id.pocketbase.io`).

5. **Connect the Frontend:**  
   In your React app's `.env` file, set:
   ```env
   REACT_APP_POCKETBASE_URL=https://your-project-id.pocketbase.io
   REACT_APP_FRONTEND_URL=https://your-frontend-url.com
   ```
   Restart your frontend dev server if needed.

6. **Done!**  
   Your frontend is now connected to PocketBase Cloud. You can use all features (login, pets, accessories, etc) out of the box.

---

## 🔑 Admin Login
To manage your backend, log in at `https://your-project-id.pocketbase.io/_/` with your admin credentials.

## 📦 Schema File
The `pb_schema.json` file is included in this repository. Use it to import all collections and fields in one step.

## 💡 Need Help?
- See [PocketBase Cloud Docs](https://pocketbase.io/docs/cloud/)
- Or ask in the [PocketBase Discord](https://discord.gg/pocketbase)
