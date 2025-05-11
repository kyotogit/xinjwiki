## Start Local Development Server

To start the local development server and preview your wiki site:

```bash
mkdocs serve
```

This will start a local development server at http://127.0.0.1:8000/. You can view your site in your web browser and see changes in real-time as you edit the documentation.

## Deploy the wiki to GitHub 

- Create own repository on GitHub  
- After completing the corresponding Git operations locally, push to the remote repository:

```bash
git push origin main
```

- Enter the `my-wiki` directory and deploy:

```bash
mkdocs gh-deploy
```

- ✅ Once deployed, you can view your site at:  
  [https://kyotogit.github.io/xinjwiki/](https://kyotogit.github.io/xinjwiki/)
