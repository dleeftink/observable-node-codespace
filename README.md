# Observable Codespaces starter

This repository contains the basic prerequisites to get started with Observable Framework on Github Codespaces (Alpine Linux + Node).

1. Sign in to your GitHub account.
2. Open https://github.com/dleeftink/observable-node-codespace (this repo) in your browser.
3. Select `Use this template` > `Open in a codespace`.

![](https://docs.github.com/assets/cb-77734/mw-1440/images/help/repository/use-this-template-button.webp)

## Start making changes

Wait for the codespace to be built and the setup scripts to finish running (this may take some time). 
- After succesfully setting up the environment, codespaces should
automatically open `index.md` to the left and a preview pane to the right.
- Additionally, a popup might open asking you to trust the live server destination.

![](https://raw.githubusercontent.com/dleeftink/observable-node-codespace/main/setup.png)

You can edit the `index.md` contents, after which the content changes are reflected (with a slight delay) in the preview pane.

If updates stop being reflected in the preview pane, refresh the page. If updates aren't propagated after refreshing, execute `CTRL/CMD + C` in the terminal after which you can restart the live server using `npm run obs`.
- If you accidentally close the preview pane, you can re-open this by navigating to the `Ports` tab on the bottom half of the screen and hovering the `Forwarded Address` item. Click the `Preview in Editor` icon that shows on hover to re-open the live preview inside your codespace.

> For more information on getting started, visit the [Observable Framework Documentation](https://observablehq.com/framework/getting-started).

## Create a new dashboard

You can create new dashboards ('sub-repositories') as follows:

1. Locate to the `Terminal` tab and `cd` to the `/workspace/observable-codespace` directory if not already there.

2. Run the `npm init @observable` command.
    - If this is your first time running this command, you will be prompted to install `create`. Type `y`.

3. Follow the CLI to create the sub-reposistory and additional template files.
