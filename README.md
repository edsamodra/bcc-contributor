# [BCC-Contributor](https://github.com/edwinsamodra/bcc-contributor)

## Brief Story
Someone just finished creating a website to document BCC contributors in 2022. Since the creator wanted new contributors to create PR for the first time, the author didn't write all the names of the contributors themselves. However, giving contributors the freedom to do it themselves.

## Demo
[https://bcc-contributor.netlify.app](https://bcc-contributor.netlify.app)

## Objectives

- Make a contribution to an open source project.
- Get more comfortable in using GitHub.

## Who is this for?

- This is for absolute beginners.
- It is for those with a little more experience but who want to make their first open source contribution.

## What am I going to contribute?

![Contributor Card](https://i.ibb.co/g6x5yDB/contributor.png 'Contributor Card')

You are going to contribute a card just like this one to this [project's web page](https://bcc-contributor.netlify.app). It will include your name, picture, a short description, your Instagram profile URL handle, and Github link.
You will make a copy of the card template inside the HTML file and customise it with your own information.

## Contribute Overview
 1️⃣ [Fork this repository](#fork-this-repository) <br />
 2️⃣ [Create a new branch](#create-a-new-branch) <br />
 3️⃣ [Clone the repository](#clone-the-repository) <br />
 4️⃣ [Open the directory file in the VSCode](#open-the-directory-file-in-the-vscode) <br />
 5️⃣ [Copy the card template and make changes](#copy-the-card-template-and-make-changes) <br />
 6️⃣ [Commit and push your changes](#commit-and-push-your-changes) <br /> 
 7️⃣ [Submit a PR](#submit-a-pr) <br />
 8️⃣ [Celebrate!](#celebrate) <br />
 9️⃣ [See your card](#see-your-card)
 
## Contribute
> Get your hand dirty


---

### Fork this repository
Click **Fork** to copy this repo to your github account

| ![Fork](https://i.ibb.co/DVHdP6d/fork.png 'Fork') |
| :------------------------------------------------ |

---

### Create a new branch
A branch is a way to keep your changes separate from the main part of the project called `Master`. For example if things go wrong and you are not happy with your changes you can simply delete the branch and the main project won't be affected. <br />
So, you can click "Create branch: ..." like the picture below

| ![Create a new branch](https://i.ibb.co/4Snpx7r/create-branches.png 'Create a new branch') |
| :------------------------------------------------ |

---

### Clone the repository
Copy the URL and open your terminal. Then write command like the picture below

| ![Clone](https://i.ibb.co/kXNjH4B/clone.png 'Clone')     |
| :------------------------------------------------------- |
| ![Clone](https://i.ibb.co/TBz2tfr/clone-2.png 'Clone 2') |

---

### Open the directory file in the VSCode
First, open the directory using VSCode

| ![Open Directory](https://i.ibb.co/KNNZnWK/dir.png 'Open Directory') |
| :------------------------------------------------ |


Then, change the active branch "main" to the branch you created. Command : ``` git checkout <YOUR-BRANCH> ```

| ![Checkout](https://i.ibb.co/X23nDG5/checkout.png 'Checkout') |
| :------------------------------------------------ |

---

### Copy the card template and make changes
You can copy the card template from here. Then put the code file after ```</div>``` belongs to ```<div class="card">```

```html
<!-- Copy from this line -->
<div class="card">
    <div class="card-header">
        <img src="YOUR_PICTURE_URL" />
    </div>
    <div class="card-body">
        <span class="tag tag-teal">Your Departement</span>
        <h3>YOUR_NAME</h3>
        <p>
            YOUR_SHORT_DESCRIPTION
        </p>
        <div class="sosmed">
            <a href="https://github.com/YOUR_USERNAME">
                <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="github logo">
            </a>
            <a href="https://instagram.com/YOUR_USERNAME">
                <img src="https://www.fiveacrefarms.com/wp-content/uploads/2019/04/instagram.png" alt="instagram logo">
            </a>
        </div>
    </div>
</div>
<!-- Until this line -->
```

You can use another color for your tag. This is color code in the style.css. So, you can customization on tag color freely.
```html
<style>
    .tag-teal {
        background-color: #47bcd4;
    }
    
    .tag-purple {
        background-color: #5e76bf;
    }

    .tag-pink {
        background-color: #cd5b9f;
    }
</style>
```

After that, make any changes to your template. Make sure your changes are only in the index.html file.

| ![Changes](https://i.ibb.co/NmLStx7/changes.png 'Changes') |
| :------------------------------------------------ |

---

### Commit and push your changes
To commit and push your changes. Follow the command below
```
git add .
git commit -m "<YOUR-MESSAGE-COMMIT>"
git push -u origin <YOUR-NEW-BRANCH>
```

| ![Commit and Push](https://i.ibb.co/zVVBMZJ/commit-and-push.png 'Commit and Push')            |
| :-------------------------------------------------------------------------------------------- |

---

### Submit a PR
Click **Compare & pull request** to copy this repo to make pull request from your branch to main branch.

If the text ```Able to merged``` is visible that means, your changes do not create conflict. So, you can click **Create pull request** after write a comment.

| ![Github notification](https://i.ibb.co/XSvFLtq/gh-commit-and-push.png 'Github notification') |
| :-------------------------------------------------------------------------------------------- |
| ![Create Pull Request](https://i.ibb.co/41kT0tP/pull-request.png 'Create Pull Request')       |

---

### Celebrate!
Congratulation! you have been able to make a pull request. Wait for an update from the owner to see if the PR you have created is merged or rejected.

---

### See your card

If the owner has approved your pull request, you can check to [this link](https://bcc-contributor.netlify.app/).

---

## Contributing
Thank you for considering contributing our Repository! The contribution guide can be found in the [Contribution Guidelines](https://github.com/edwinsamodra/bcc-contributor/blob/main/CONTRIBUTING.md).

## Reference and Resource
- [Skynapse - Contribute To This Project](https://github.com/Syknapse/Contribute-To-This-Project)
- [UpKoding - Komunitas](https://github.com/upkoding/komunitas)

## Disclaimer
For educational purposes only, not commercial.

## Thank You
Thanks for the random repos which have good documentation on README.md and CONTRIBUTING.md. So I can write this markdown clearly.
