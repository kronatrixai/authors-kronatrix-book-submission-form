# authors.kronatrix Book Submission Form

## GitHub account

Owner:

`kronatrixai`

Repository name:

`authors-kronatrix-book-submission-form`

Repository URL:

`https://github.com/kronatrixai/authors-kronatrix-book-submission-form`

Default GitHub Pages URL before the custom domain is active:

`https://kronatrixai.github.io/authors-kronatrix-book-submission-form/`

## Repository description

A responsive authors.kronatrix form that prepares an organised email submission containing an author's name, purchase links and social profiles, with clear instructions to attach the book cover and full interior PDF.

## Custom domain

`submit-your-book.kronatrix.co.uk`

The included `CNAME` file already contains this domain.

## GoDaddy DNS record

Create this record under `kronatrix.co.uk`:

- Type: `CNAME`
- Name: `submit-your-book`
- Value: `kronatrixai.github.io`
- TTL: `1/2 Hour` or the default value

Do not include `https://`, the repository name or the full custom domain in the Value field.

## GitHub Pages setup

1. Create the repository using the owner `kronatrixai`.
2. Use the repository name `authors-kronatrix-book-submission-form`.
3. Keep the repository **Public**.
4. Do not add a README, `.gitignore` or licence during repository creation because this package already includes the required files.
5. Upload every file from this package directly into the repository root.
6. Open **Settings**.
7. Open **Pages**.
8. Under **Build and deployment**, choose **Deploy from a branch**.
9. Select branch **main** and folder **/(root)**.
10. Press **Save**.
11. Under **Custom domain**, enter `submit-your-book.kronatrix.co.uk`.
12. Enable **Enforce HTTPS** when available.

## Required author submission details

- Author or pen name
- Book cover image attached to the email
- Full interior PDF attached to the email

Purchase and social links are optional. Authors can add as many as needed using dropdown menus.

## Email recipient

`authors.kronatrix@gmail.com`

## Live ebook preview example

`https://the-identity-paradox.corneliusaurelius.com/`


## Lighthouse optimisation update

This version addresses the failures shown in the uploaded mobile and desktop
Lighthouse reports:

- Removed the distorted decorative image element that failed the image
  aspect-ratio audit.
- Added right-sized logo images.
- Prevented smooth scrolling during the initial page load.
- Removed expensive backdrop filters and mask rendering.
- Prevented the decorative guardian image from downloading on mobile.
- Reduced the decorative guardian image dimensions and file size.
- Deferred rendering of below-the-fold content.

To obtain 100 for Best Practices, GitHub Pages must have **Enforce HTTPS**
enabled and Lighthouse must be run against:

`https://submit-your-book.kronatrix.co.uk/`


## Visual update

The decorative Authors.Kronatrix guardian background image has been removed from the website.
