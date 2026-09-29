# Catherine Nolasco - Portfolio for EngFlow (People Ops Manager, Temp)

A static, single-file portfolio page. `index.html` is self-contained (fonts embedded, no JavaScript).

## Publish with GitHub Pages
1. Create a new repository and upload these files to the `main` branch.
2. Go to Settings, then Pages, and deploy from the `main` branch, root folder.
3. The site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Rebuild after edits (optional)
Content lives in `src/content.py` and `src/portfolio_content.py`. The build script expects the Inter and Poppins fonts from npm:

    npm i @fontsource/inter @fontsource/poppins
    cd src && python3 build_portfolio.py standalone ../index.html

Independent portfolio styled after the EngFlow brand. Not affiliated with EngFlow.
