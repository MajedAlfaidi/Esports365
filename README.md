# Esports365 — CPIS358 static web assignment

An esports results dashboard demo, inspired by score-tracking websites. Dark theme kept from the original project.

## Project structure
- `Esports365/Pages/` contains ASP.NET Core Razor Pages (`Index`, `SignUp`, `ChooseTeam`, `Home`, `Matches`, `About`).
- `Esports365/wwwroot/` contains the shared CSS, JavaScript and image.
- `docs/` contains the independent **static HTML/CSS/JS** version that can be deployed with GitHub Pages.

## Deploy to GitHub Pages
1. Upload/commit the entire repository (including `docs`) on your GitHub account as collaborator.
2. Repository **Settings → Pages → Deploy from a branch**; select **main/master** and folder **/docs**, then Save.
3. The public site opens at `https://<owner>.github.io/<repo>/`.

## Run ASP.NET locally
Requires .NET 10 SDK: `dotnet run --project Esports365/Esports365.csproj`.

## Site pages
Dashboard (`docs/index.html`), Login, Sign Up, Choose Your Favorite Team, Matches, About Us. All share navigation and image map to About Us.

## Assignment features
- HTML headings, `article`, `section`, forms, accessible labels, lists, tables, in-page navigation, a `datalist` in matches search, HTML image maps, and all-page navigation.
- External CSS plus embedded `<style>` and inline `style`; shared classes, responsive navigation, `z-index`, box shadows and borders.
- External JS adds game/team selection, saved preference, match filters, and form validation. Client-side-only demo, no live data and no backend login.

## Important: academic demonstration
All teams, match results, dates and streaming services are **fictional demo examples**. Do not represent them as live esports results.
The Login and Sign Up are visual front-end demonstrations. They do not perform secure authentication or send real passwords to a server.

## GitHub contribution credit
Each teammate should clone/pull, commit their own contributions, and push from their GitHub-linked email. A ZIP does not carry commits or contribution history. Capture a screenshot of each teammate's GitHub contribution calendar for the assignment report.
