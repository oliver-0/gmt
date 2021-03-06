# gmt

## How to create a Portfolio content Pull Request

1. Open [this file creation page](https://github.com/oliver-0/gmt/new/master/content/portfolio/) in a new tab
2. Enter a relevant filename, ending in `.md`, e.g. `TimConLAN-showreel.md`
3. Paste the following template into the body of the file:
    ```
    ---
    title: Title goes here
    youtubeEmbed: https://www.youtube.com/embed/AAAAAAAAAAA
    # make sure youtubeEmbed url is formatted as `/embed/`, not `watch?v=`
    tags: []
    # tags are a word or words separated with a comma and a space, e.g.: `[commentary, broadcast consulting, Starcraft II]`
    #
    # body content below is rendered using Markdown - see https://www.markdownguide.org/cheat-sheet/ for basic syntax
    # for a new paragraph, use a line break
    # for a new line within a paragraph, use <br> at the end of previous line (instead of 2 whitespace characters, for best compatibility)
    ---
    
    Template body text.

    New paragraph, with **bold text** and *italic text*.<br>
    Newline example (the `<br>` on the previous line puts this text on a new line within the paragraph)
    ```
4. replace `title`, `youtubeEmbed`, `tags` (if wanted), and the body text below with appropriate content
5. At the bottom of the page, create a **new branch** for this commit and start a pull request.  
    For readability, please rename the branch to something relevant - the same as the file name, if you like (e.g. `TimConLAN-showreel`)
    
I will be notified by email, and upon approval of the Pull Request, your content will be published.

You can preview your Pull Request once it has finished processing (~2min) - the github-actions bot will post a preview url in the comments of your Pull Request, so look out for that!

Example Pull Request:

![Example Pull Request image](/.github/example-PR.PNG?raw=true "Example Pull Request")
