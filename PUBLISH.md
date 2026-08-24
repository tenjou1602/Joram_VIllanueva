# Publish Your Portfolio Online

Your site is built and ready. Follow these steps to put it live on GitHub Pages.

## 1. Create empty repos on GitHub

Go to [github.com/new](https://github.com/new) and create these (no README):

| Repo name | Folder to push from |
|-----------|---------------------|
| `portfolio` | `Desktop\Portfolio+OJT` |
| `student-concern-tracking` | `Desktop\Student Concern tracking system\Student Concern tracking system` |
| `motortrade-dashboard` | `Desktop\program\motortrade_db` |
| `flutter303` | Already exists — no action needed |

## 2. Push each project

```powershell
# Portfolio (your live website)
cd "c:\Users\Pc\Desktop\Portfolio+OJT"
git remote add origin https://github.com/tenjou1602/portfolio.git
git push -u origin main

# ConcernTrack
cd "c:\Users\Pc\Desktop\Student Concern tracking system\Student Concern tracking system"
git remote add origin https://github.com/tenjou1602/student-concern-tracking.git
git push -u origin main

# MotorTrade
cd "c:\Users\Pc\Desktop\program\motortrade_db"
git remote add origin https://github.com/tenjou1602/motortrade-dashboard.git
git push -u origin main
```

## 3. Enable GitHub Pages (portfolio only)

1. Open `https://github.com/tenjou1602/portfolio`
2. **Settings → Pages**
3. Source: **Deploy from branch**
4. Branch: **main** / **/ (root)**
5. Save

Your site will be live at: **https://tenjou1602.github.io/portfolio/**

## 4. Preview locally anytime

```powershell
cd "c:\Users\Pc\Desktop\Portfolio+OJT"
python -m http.server 8080
```

Open: http://localhost:8080
