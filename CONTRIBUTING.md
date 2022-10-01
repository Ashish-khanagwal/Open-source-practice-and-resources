# Contribution Guide
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com)
[![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v1/open-source.svg)](https://github.com/firstcontributions/open-source-badges)

## Resource Qualification
Resources have to be in the form of links. Allowed resources can be videos, articles, tutorials, or anything similar. It has to be helpful, whether as a tool to be used or as a source of information.

Here are some rules to follow when adding a resource: 

* single blog posts are not accepted. This is simply because if single blog posts are allowed then this list would be endless. There could be some exceptions, like if the single post is very extensive or includes details that are hard to find elsewhere. If the resource you're adding falls under the exception then please detail that in the PR
* If you want to add multiple links of the same topic under the same website, just include a general link that might lead to all these links. For example, instead of adding multiple Youtube videos under the same series, add the playlist link.
* Take the time to make sure the resource has not been already added as it saves the maintainers time when reviewing your pull request.
* Take the time to make sure the resource has not been already added as it saves the maintainers time when reviewing your pull request.


# How to Contirbute

## By using GitHub GUI

 1. Fork the repository  

 ![fork repo](https://user-images.githubusercontent.com/75534912/189517485-d55527ac-9691-4a06-ab4c-d062eb9f2b0f.jpg)

 2. Edit the README.md file

 ![6](https://user-images.githubusercontent.com/75534912/189521460-97bf6f77-6e72-4507-aea0-7dee9deb1630.jpg)

 3. Find the correct category for your resource. For example: If it's a JavaScript tutorial, you need to add it under Javascript. If the category does not exist, you can add it under Index. Resources are added in alphabetical order, except for Other which should stay at last.

 4. To add a new category, add a list item with the name of the category and the URL to it (hash of the slug of the name). For example:

```markdown
- [New Category](#new-category)
```

 5. Once you find or add the correct category, add the new resource at the end of the list. It should have the title and the link to the resource. For example:
 
 ```markdown
 - [Web-3](https://learnweb3.io/)
 ```

You also have to add an emoji before the file name that represents what the resource is. Here are the list of emojis we use:

| Emoji        | Description                                      | Emoji Key       |
|--------------|--------------------------------------------------|-----------------|
|:books:       |Blogs/List of tutorials                           |`:books:`        |
|:file_folder: |Documentation                                     |`:file_folder:`  |
|:speaker:     |Podcast                                           |`:speaker:`      |
|:hammer_and_wrench:      |Tools/Softwares/Roadmaps               |`:hammer_and_wrench:`|
|:video_camera:|Video Resource (Youtube, video course, etc...)    |`:video_camera:` |
|:bulb:        |Ideas/Suggestions                                 |`:bulb:`         |

* Once you're done, scroll to the bottom of the list to commit the change. Make sure the title of the commit is relevant. For example: Added How to Contribute under New Category.

* Follow the steps to create pull request
---

## If you want to use GIT CLI, Then follow along!

* Fork the repository  
![fork repo](https://user-images.githubusercontent.com/75534912/189517485-d55527ac-9691-4a06-ab4c-d062eb9f2b0f.jpg)

* copy the url and clone the repository in your local directoy using **Git bash Terminal**, command to clone the repo `git clone <copied url>`
![2](https://user-images.githubusercontent.com/75534912/189518091-a59611bb-e9de-4c48-ad41-fbc420f9c672.jpg)
* `cd Open-source-practice-and-resources` use this command in git bash to naviage to the directory
* Make sure to create new branch by hitting `git checkout -b <your-branch-name>` command
* then, Open README.md in text editor:
  * In notepad => `notepad.README.md`
  * In VsCode => `code README.md`

**Then platform is all yours, add resources/content you want but in a good way don't rush, if you find any difficulty ask in the server for help.**

Don't know how to write in GitHub README.md file, have a look on link 👉	
[GitHub Writting](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

* After adding resources save the file in text editor. navigate to your **Git bash terminal** and hit command `git add .` to add all your changes
* now, you have to commit the changes. so, use `git commit -m "any-name"`

![3](https://user-images.githubusercontent.com/75534912/189518667-877d00e6-c3ed-4a12-8d04-f38790dd873c.jpg)

* Now, its time to push your changes => `git push origin <your-branch-name>`

![4](https://user-images.githubusercontent.com/75534912/189518703-d2219677-57f0-4148-95fd-fc907c45b935.jpg)

* come to the repository's home page you'll, and hit on Compare and Pull request.

![5](https://user-images.githubusercontent.com/75534912/189518817-166a2a12-eb70-422a-995b-a613968b4c2b.jpg)

* And then, some checks will perform by the GitHub and if you sucessfully did it, your pull request get submitted and then, maintainers will review your request and will merge it.
