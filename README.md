# École 42 C project template
This is my [École 42](https://42.fr/) C project template, meant to be used for
the school's C projects.

> **Warning**
> 
> This template is contains my `libft` library.
> If you wish to use it for your 42 C projects, refer to [Using your own libft](#using-your-own-libft)

## Features
- Pre-commit norminette hook (thanks to [vcwild](https://github.com/vcwild))
- Github Workflow `build` check for CI

## Using your own libft
If you are a 42 student, you need to use your own `libft` in your C projects. To
do so, you should:

1. Clone this repository
2. Remove the `libft` git subtree (see `git-subtree(1)`) using `git rm libft`
3. Add your own libft to the `libft` folder at the project root

If you wish to add your `libft` as a git subtree:

```sh
git subtree add --prefix libft $LIBFT_REPO_URL main --squash
```
