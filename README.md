## SimplyBuilder GitHub Pages Starter Project    


### go to: `settings/pages`

### change sources to: `Github Actions`

### configure the custom domain if applicable.

### customize the file: `.github/workflows/deploy-to-pages.yml`

By default, it comes to carry out the process **manually**, and can perform tag deployment, to facilitate rollback.      
But if you prefer, you can uncomment **lines 6 and 7**, to carry out the automatic process during the push to the default branch.      
**line 43** refers to the same directory described in **line 12** of `vite.config.js`


### execute manual deployments, selecting branch or tag or track the progress of manual or automated deployments in the `Actions` tab of your repository

### Now your project is live at the url configured in `settings/pages`. Change your files as you wish and make your deployments automatic or controlled.