This lab website based on Aharoni lab site https://github.com/Aharoni-Lab/Aharoni-Lab.github.io

# Instructions for updating / maintaining website

- After making changes, commit and push changes to github, then wait for a few minutes for changes to propagate to live site. 
- If you want to generate a local version before pushing to github, [install jekyll via homebrew](https://jekyllrb.com/docs/installation/macos/), then cahnge directory into this git repo, then run `bundle install`, then run `bundle exec jekyll serve`  and navigate to http://localhost:4000 to see the local preview.

## Home

- To update the home page, edit the [/index.md](https://github.com/bergmanlab/bergmanlab.github.io/blob/main/index.md) file
- To add a banner image, place it as `/assets/images/banner.png`
- To add a page to the navigation bar, add it to "main" in [/_data/navigation.yml](https://github.com/bergmanlab/bergmanlab.github.io/blob/main/_data/navigation.yml)

## Lab Personnel
- For people, keep their info updated in the [/_data/people.yml](https://github.com/bergmanlab/bergmanlab.github.io/blob/main/_data/people.yml) file
- If including an image of the person, place the image in the `/People` folder
- To add a person to the "People" page, add `{% include person.html name='INSERT_NAME_HERE' %}` to the appropriate section of the [/People/index.md](https://github.com/bergmanlab/bergmanlab.github.io/blob/main/People/index.md) file

## Research, Publications, and Join

- These pages can be edited at their respective /FOLDER/index.md files.

## Blog

- To create a blog post, add it to the /_posts/ folder as a md file with the name YYYY-MM-DD-POSTNAME.md.
- make sure to keep a blank `tagline: " "` in the header to prevent the body of the post from showing up in the header.

