# Online resume with Jekyll

I made this resume with Jekyll, using Sass in the CSS. I choose Jekyll because I can deploy it in Github Pages easily and totally free.

In [Jekyll Docs](https://jekyllrb.com/docs/step-by-step/01-setup/) you have a step by step tutorial. I used in Windows with WSL with no problems. It is really easy to follow, but in my [DEVs page](https://dev.to/biancapereira) I pretend to post a simple to follow tutorial about the process.

## Using the resume theme

1. Fork and clone the repo in your workspace.
`git clone https://github.com/your_user/resume.git`

2. Install Ruby and after it install Jekyll ([here is a tutorial](https://jekyllrb.com/docs/installation/)).

3. You have to run `jekyll build` to build the `_site` folder.

4. Run Jekyll.
`jekyll serve`

5. Access it in your `localhost:4000`.

## Folder structure

|  Name  |  Description  |
| ------------ | ------------ |
|  `_data`  | Database files in **.yml**. Includes contact, education, profile and social data.  |
|  `_experience`  | Experience collection. Every file contains working experience in markdown. **order** means the order of appearance in the view.  |
|  `_includes`  | Have the template for contact, education, experience, profile and social views. |
|  `_layout`  | Contains the only layout of the page: default. |
|  `assets`  | Includes the CSS and all the images from the theme. |

## License

You can find the MIT license in the [LICENSE](LICENSE) file. You can use and edit this files wherever you want, but remember to always maintain the credits.

## Resources

- [Jekyll Docs](https://jekyllrb.com/docs/)
- [Social icons](https://www.iconfinder.com/iconsets/logos-and-brands-1)
- [Contact icons](https://www.iconfinder.com/iconsets/heroicons-ui)