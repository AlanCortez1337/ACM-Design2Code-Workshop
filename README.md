# Lore

This is a workshop activity is meant to expose people to Figma's `devmode` feature. The purpose of this repository is meant to have a skeleton HTML website ready for people to modify the existing css file using what Figma recommends. Below will have steps on how to navigate

# Structure

In this repository are two folders labeled Maje and NatureWonder which are meant to represent two separate websites. To view the websites go to this 🔗[figma link](https://www.figma.com/file/7xIBszLJenYFiNNM9DxKdL/Website-Design?type=design&node-id=0%3A1&mode=design&t=HAqIdCxmh5zJZ19d-1) and view both mockups of the websites. This will be used as reference for the coding activity.

Once you do this then later on when using the figma plugin you can see how Figma recommends to style each section. 

# Before Coding...

1. Fork this repository
2. Open the repository in an IDE, below will have steps on how to do it using github codespaces
    - Click on the green `Code` button
    - Click on "Codespaces"
    - Click on "create codespace on main"
3. Once you have your IDE ready, install the following extensions by clicking the 4 square icon
    - Figma for VS Code
    - Live Server
4. When you install the Figma plugin you will now see on your tool bar a Figma icon. Click it and log into figma
5. After logging in open the "Design2Code Mockups" file and see how it opens the figma file on your IDE

# Coding

1. In your terminal write `cd [file name]` (I personally recommend Maje for a beginner friendly introduction).
2. Click on the respective `index.html` file for the mockup you want to use and then read through it to understand the structure of it.
3. After that, go to the styles.css file and begin trying to replicate the styles using the skeleton of the HTML file and what the Figma plugin recommends.

## Debugging and Testing

We use the `Live Server` extension to locally run the website to see how it reacts to changes live. To run this navigate your mouse to the bottom right of your vscode UI and lick on the `Go Live` button. Once you do this then a new tab will open with how your website looks! 

*Each time you save will refresh the website for you to view*

## Saving your code if you are using codespaces

Github codespaces are temporary, if you want to save your code then you have to use `git` in order to save your changes to your local repository.

If you are not familiar with using `git` then do the following steps in order and it *should* work (knock on wood)

```
git add .
git commit -m "initial commit"
git push
```

When you run those commands line by line then when you go back to your github repository you should see the changes there so that next time you can just open the codespace and get right back into it.

## When you see a...

💡  This is just a tip / explanation why things were structured a certain way.

📚 The Books is meant to be used as Labels to seperate each section.

⭐ These are TODO's which you should do when you reach them.

# Just some random notes

I just want to mention Figma devmode does not provide 1:1 accuracy to css, use Figma only as a guide to coding your projects. Also when mocking up the designs on figma sometimes when you are using auto layout or depending on how you organize your HTML. I highly recommend brushing up on CSS and HTML if this is a bit confusing to understand.

Check out the resources found at 🔗[acmcsuf.com/design2code](acmcsuf.com/design2code) to be a bit more aquainted on how to take your *designs to code*