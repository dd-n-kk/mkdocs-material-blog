# mkdocs-material-blog

Template of a blog made with Material for MkDocs

## Usage

1. Use this template to create a new repository.

2. Replace filler values (`MY_NAME`, `MY_BLOG`, etc.)
   in `LICENSE`, `mkdocs.yml`, and `docs/.authors.yml`.

3. Set up or remove the giscus comment system:

    - To remove the comment system, delete:
        - `overrides/`
        - `docs/posts/.meta.yml`

    - To properly set up a giscus comment system (your repository has to be public):
        1. In repository Settings → General → Features, enable Discussions.
        2. In repository Discussions → Categories, create a New Category
            (e.g. "giscus comments") with Announcement as the Discussion Format.
        3. [Install giscus app](https://github.com/apps/giscus) for your repository.
        4. [Configure and create a giscus script](https://giscus.app) for your repository,
            and use it to replace the stub in `overrides/partials/comments.html`.
        5. Refer to [Material for MkDocs documentation][1] for a detailed guide.

4. Adjust `mkdocs.yml` to your liking.

[1]: https://squidfunk.github.io/mkdocs-material/setup/adding-a-comment-system/
