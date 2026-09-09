# Piyush Varma's portfolio

A simple personal portfolio built with HTML and CSS and hosted on GitHub Pages. This project began as a way to learn how to publish a website with GitHub.

## Run locally

No build tools or dependencies are required. Start a local server from the project directory:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in a browser.

## Publish with GitHub Pages

The included GitHub Actions workflow publishes the website whenever a change is
pushed to `main`.

1. Push or merge the website files into the `main` branch on GitHub.
2. Open the repository's **Settings**, then select **Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. Open the repository's **Actions** tab and select **Deploy portfolio to
   GitHub Pages**. If it has not run automatically, choose **Run workflow**.

Once the deployment finishes, the site will be available at
[`https://piyush-1898.github.io`](https://piyush-1898.github.io).

> A local commit is not visible on GitHub until it has been pushed to the remote
> repository. If GitHub still shows the old site, confirm that the latest commit
> appears on `main` and that the Pages workflow completed successfully.
