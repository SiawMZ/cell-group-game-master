# How to Update Your Website

Because your project is now linked to GitHub and Vercel, updating your live website is incredibly easy! Vercel is set up to automatically deploy any new changes pushed to your GitHub repository.

Whenever you make a change to your code (like adding new questions to `questions.js` or changing the styling in `code.html`), follow these three steps in your VS Code terminal to update the live site:

1. **Stage your changes:** This tells Git which files you want to include in the update.
   ```bash
   git add .
   ```

2. **Commit your changes:** This saves the update locally with a descriptive message so you remember what you changed.
   ```bash
   git commit -m "Describe your changes here, e.g., added new charades questions"
   ```

3. **Push to GitHub:** This uploads your local changes to your remote GitHub repository.
   ```bash
   git push origin main
   ```

That's it! As soon as the `git push` finishes, Vercel will automatically detect the new code and start deploying it. You can watch the deployment progress on your Vercel Dashboard, but usually, it takes less than a minute for your live website to reflect the new changes!
