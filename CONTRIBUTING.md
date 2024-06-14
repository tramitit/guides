# How to contribute

We're grateful for your interest in participating in Tramitit's efforts to reduce the
burden of bureaucracy.
Please follow our guidelines to ensure a smooth contribution process.

Your course of action will depend on your objective, but generally, you should start by creating an issue.

The methods laid out herein all require a GitHub account, which you can create [here](https://github.com/join).
Other alternatives is using the contact form on our website https://tramitit.com/contact or via the Disqus comments on each post.

## Reporting an issue or proposing new content

You can create an issue on [Tramitit/guides's GitHub issue tracker](https://github.com/tramitit/guides/issues). Here are some steps to take:

1. Quickly search the existing issues using relevant keywords to ensure your issue hasn't been addressed already.
2. If your issue is not listed, create a new one. Try to be as detailed and clear as possible in your description.

- If you've noticed a mistake or want to propose a new article to add, you're finished! We'll try to address it as soon as possible.
- However, if you're willing to be the one solving the issue, that would be even better! In such instances, you would proceed by preparing a [Pull Request](#submitting-a-pull-request).

## Submitting a pull request

We're excited that you're eager to contribute to Tramitit.
To contribute, fork the `main` branch of this repository and once you are satisfied with your edit create a [Pull Request](https://github.com/tramitit/guides/pulls).

Note that we primarily maintain the English version of each article, if, if what you want to fix is possible to fix in the English version that is preferred.
But we are happy to receive contributions in all languages!

Here's the process for making a contribution:

Click the "Fork" button at the upper right corner of the [repo page](https://github.com/tramitit/guides) to create a new GitHub repo at `https://github.com/USERNAME/guides`, where `USERNAME` is your GitHub ID.

You can now make the edit in the GitHub user interface or by cloning the repository to your local machine and edit it using a text editor.

### Through the GitHub user interface

See a step by step guide on https://tramitit.com/contribute/.

In summary navigate to the file you want to change, and press edit. We link directly to this page from the hosted version on https://tramitit.com/guides.
This will prompt you to "Fork this Repository", which you should do.
You make your change in the editor that appears, press commit, and then "Create pull request" as it appears.

### With local edits

Then, `cd` into the directory where you want to place your new fork and clone it:

```shell
git clone https://github.com/USERNAME/guides.git
```

Next, navigate to your new guides fork directory and mark the main tramitit/guides repository as the `upstream`:

```shell
git remote add upstream https://github.com/tramitit/guides.git
```

Once you're happy you should push your changes

```
git add en/spain/appointment_request_for_immigration_office.md
git commit -m "Updated the appointment request for immigration office with new information"
git push -u origin main
```

You can now open a pull request on [GitHub](https://github.com/tramitit/guides/pulls) with your changes.
