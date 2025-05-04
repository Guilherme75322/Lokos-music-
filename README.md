# Lokos-music-
Lokos desenhos digital Studio 
# Import from GitHub

> Learn how to create a **Replit App** from your GitHub repository code.

## Import your GitHub repository

⏰ *Estimated time: 2 minutes*

You can import your GitHub repositories and turn them into Replit Apps to
run, test, and deploy your code.

Import your GitHub repository using one of the following methods:

* **Rapid import**: add a public GitHub repository to a Replit URL to start the import
* **Guided import**: Enter the repository details from the Replit home screen

<Frame>
  <img src="https://mintlify.s3.us-west-1.amazonaws.com/replit/images/getting-started/github_import_preview.png" alt="Preview of GitHub repository import in Replit" />
</Frame>

Log into Replit and follow the steps in one of the import methods in the following sections.

## Rapid import

<Frame>
  <iframe src="https://www.youtube.com/embed/m2sI_LVNZe8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen />
</Frame>

Rapid import works instantly with public repositories.
Combine the Replit import URL with your GitHub repository URL to start the import process.

<Accordion title="Import using rapid import" defaultOpen={true}>
  1. Copy the repository GitHub URL, starting with `github.com`.

  2. Type `https://replit.new/` in the browser address bar and paste your copied GitHub URL at the end (no spaces).

     **Example**:

     GitHub repository URL: `https://github.com/exampleUser/my-app`

     Import URL: `https://replit.new/github.com/exampleUser/my-app`

  3. Press Enter to start the automatic import process.
</Accordion>

## Guided import

Guided import steps you through the process of selecting a repository to import
and supports public and private repositories.

<Accordion title="Import using guided import" defaultOpen={false}>
  1. Navigate to <a href="https://replit.com/" target="_blank">[https://replit.com](https://replit.com)</a>.

  2. Select <img class="icon-svg" src="https://mintlify.s3.us-west-1.amazonaws.com/replit/images/shared/buttons/create-app-icon.svg" /> **Create App** from the left dock.

  <Frame>
    <img src="https://mintlify.s3.us-west-1.amazonaws.com/replit/images/getting-started/homepage_app.png" alt="Replit homepage import interface" />
  </Frame>

  3. Select the **Import from GitHub** tab.

  <Frame>
    <img src="https://mintlify.s3.us-west-1.amazonaws.com/replit/images/getting-started/connect_your_account.png" alt="Replit homepage import interface" />
  </Frame>

  4. Select <img class="icon-svg" src="https://mintlify.s3.us-west-1.amazonaws.com/replit/images/shared/chain-link.svg" alt="link icon" /> **From URL**.

  5. Paste the complete GitHub repository URL in the text field.
     If the import tool can read the repository at the URL, it displays the repository description. Otherwise, it displays an error message.

     The following screenshot shows an example of the repository preview:

     <Frame>
       <img src="https://mintlify.s3.us-west-1.amazonaws.com/replit/images/getting-started/quickstart-example-import.png" alt="Replit homepage import interface" />
     </Frame>

  6. Configure your privacy settings and select **Import from GitHub** to start the automatic import process.
</Accordion>

## Configure and run your app

During the import process, Replit attempts to set your app's language, dependencies, and workflow.
If your app doesn't run as expected, Replit offers the following workspace tools to help you resolve the issues:

* **Agent**: Diagnose and fix setup issues using AI-powered assistance.
* **Configure Repl**: Configure your app's language, dependencies, and workflow.
* **Secrets**: Securely add environment variables your app depends on.

## Continue your journey

Now that you've set up your app, learn more about what you can do with your Replit App from the following resources:

* [Private & Personal Repositories](replit-workspace/using-git-on-replit/private-repo): Set up access to private repositories
* [Make your Replit App Public](/replit-app/collaborate#make-your-replit-app-public): Share your Replit App as a Template for others to remix
* [Replit Deployments](https://docs.replit.com/category/replit-deployments): Publish your Replit App to the cloud with a few clicks
* ["Run on Replit" badge](/replit-workspace/using-git-on-replit/running-github-repositories-replit): Add a badge for your GitHub repository `README.md` file that lets others import your repository with one click
* [Secrets](/replit-workspace/workspace-features/secrets): Securely store sensitive information, including API keys and database credentials
