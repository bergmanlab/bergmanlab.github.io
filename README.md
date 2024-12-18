This lab website based on Aharoni lab site https://github.com/Aharoni-Lab/Aharoni-Lab.github.io

# Instructions for updating / maintaining website

- After making changes, commit and push changes to github, then wait for a few minutes for changes to propagate to live site. If you want to generate a local version before pushing to github, run `bundle install` before pushing (I think.)

## Home

- To update the home page, edit the [/index.md](https://github.com/bergmanlab/bergmanlab.github.io/blob/main/index.md) file
- To add a banner image, place it as /assets/images/banner.png
- To add a page to the navigation bar, add it to "main" in [/_data/navigation.yml](https://github.com/bergmanlab/bergmanlab.github.io/blob/main/_data/navigation.yml)

## Lab Personnel
- For people, keep their info updated in the [/_data/people.yml](https://github.com/bergmanlab/bergmanlab.github.io/blob/main/_data/people.yml) file
- If including image of the person, place the image in the /People/ folder
- Then to add them to the "People" page, add `{% include person.html name='INSERT_NAME_HERE' %}` to the appropriate section of [/People/index.md](https://github.com/bergmanlab/bergmanlab.github.io/blob/main/People/index.md) file

## Research, Publications, and Join

- These pages can be edited at their respective /FOLDER/index.md files.

## Blog

- To create a blog post, add it to the /_posts/ folder as a md file with the name YYYY-MM-DD-POSTNAME.md

