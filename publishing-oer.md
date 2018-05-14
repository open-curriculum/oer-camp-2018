# Publishing OER with Git Pages

## Exporting from HAX

1. Once you are finished editing, click on the back arrow, to take you to "Recent Projects". ![generate build](/assets/Screen Shot 2018-05-14 at 5.30.56 PM.png)
2. Under the right "more" menu (3 dots), click on "Generate build" to export the content into a folder, called `docs`: ![generate build button](/assets/Screen Shot 2018-05-14 at 12.05.41 PM.png)
3. The docs folder will look like this: ![docs](/assets/Screen Shot 2018-05-14 at 5.42.17 PM.png)
4. Open GitHub Desktop App, and commit the changes.
![First commit](/assets/Screen Shot 2018-05-14 at 12.08.34 PM.png)
5. Now push the changes to GitHub
![push](/assets/Screen Shot 2018-05-14 at 12.10.00 PM.png)
6. Your GitHub repo should look like this:
![repo directory](/assets/Screen Shot 2018-05-14 at 5.51.51 PM.png)

## Enabling Git Pages

1. To enable Github to serve pages in your repo to the Web, you will need to enable some settings. Go to the "Settings" page: ![settings page](/assets/Screen Shot 2018-05-14 at 12.10.46 PM.png)
2. Scroll down to the "GitHub Pages" section. Under "Source," Choose "Master Branch /docs folder" from the dropdown and hit "Save". This setting means that any folder called `docs` will be accessible via a url: ![choose docs folder](/assets/Screen Shot 2018-05-14 at 12.19.43 PM.png)
3. You will now see a url where you can access your webpage. Copy this URL: ![git pages url](/assets/Screen Shot 2018-05-14 at 3.09.48 PM.png)
4. Now, let's add the URL to the front page of the repo, so others can find it. Go to the front page of the repo and click "Edit" on the far right: ![edit](/assets/Screen Shot 2018-05-14 at 12.27.42 PM.png)
5. In the website section, paste in your copied URL from the settings page: ![Add url](/assets/Screen Shot 2018-05-14 at 12.27.35 PM.png)

## Configuring Git Pages

1. There is one extra step to get Git Pages working properly. We have to add an empty file called `.nojekyll` to the repository. Click on "Create new file": ![Create new file](/assets/Screen Shot 2018-05-14 at 12.20.33 PM.png)  
2. Type `.nojekyll` into the name file field. ![add no jekyll file name](/assets/Screen Shot 2018-05-14 at 3.13.17 PM.png)
2. Scroll down and click on Commit new file: ![Create new file](/assets/Screen Shot 2018-05-14 at 12.20.48 PM.png)
3. You now have your directory set up properly. [See this example](https://github.com/virtual-michael-collins/oer-writing-assignment):
![properly configured directory](/assets/Screen Shot 2018-05-14 at 3.17.03 PM.png)
4. Congrats! It can take a few minutes for the website to resolve. Visit the Git Pages URL to see if everything worked properly.

