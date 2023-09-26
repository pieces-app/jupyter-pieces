# jupyter-pieces

[![Github Actions Status](/workflows/Build/badge.svg)](/actions/workflows/build.yml)
Pieces for Developers is a code snippet management tool powered by AI.

# Elevate Your Jupyter Experience with Pieces

<div class="nav">
    <a href="https://docs.pieces.app/extensions-plugins/jupyterlab" style="display: inline-block; text-decoration: none; border-radius: 4px;">Docs</a>		<a href="https://pieces.app" style="display: inline-block; text-decoration: none; border-radius: 4px;">Learn More</a>
</div>

## Your Guide to Getting Started with Pieces for Developers Jupyter Extension

#### 1. Save your first snippet

- To save a snippet, highlight the text, right-click, and select "Save to Pieces."

![Save to Pieces via Menu](https://storage.googleapis.com/pieces_multimedia/PROMOTIONAL/PIECES_FOR_DEVELOPERS/JUPYTER/MACOS/RIGHT-CLICK_SAVE/16X9/PIECES_FOR_DEVELOPERS-JUPYTER-RIGHT-CLICK_SAVE-MACOS-16X9-9_22_2023.GIF)

**Additional ways to save**

- Click the Pieces Save button within any code block.

![Save to Pieces via Button](https://storage.googleapis.com/pieces_multimedia/PROMOTIONAL/PIECES_FOR_DEVELOPERS/JUPYTER/MACOS/SAVE_TO_PIECES/16X9/PIECES_FOR_DEVELOPERS-JUPYTER-SAVE_TO_PIECES-MACOS-16X9-9_21_2023.GIF)

#### 2. Find & use your snippets

- To access your saved snippets, click on the Pieces icon in your left sidebar.

  ![Search Your Pieces](https://storage.googleapis.com/pieces_multimedia/PROMOTIONAL/PIECES_FOR_DEVELOPERS/JUPYTER/MACOS/SEARCH_AND_INSERT/16X9/PIECES_FOR_DEVELOPERS-JUPYTER-SEARCH_AND_INSERT-16X9-MACOS-6_22_2023.gif)

#### 3. Share your Snippets

- Collaborate with others with ease using shareable links for your snippets

![Share you Snippets](https://storage.googleapis.com/pieces_multimedia/PROMOTIONAL/PIECES_FOR_DEVELOPERS/JUPYTER/MACOS/SNIPPET_BUTTON_SHARE/16X9/PIECES_FOR_DEVELOPERS-JUPYTER-SNIPPET_BUTTON_SHARE-16X9-MACOS-6_22_2023.gif)

#### 4. Copilot

- Ask questions about your notebook, generate code relevant to what you are working on, and more with the Pieces Copilot
- Suggested queries are automatically generated for your ease of use
- Choose between Local and Cloud LLM runtimes (i.e Llama2, GPT)
- Quickly link to relevant notebooks
  ![Pieces Copilot](https://storage.googleapis.com/pieces_multimedia/PROMOTIONAL/PIECES_FOR_DEVELOPERS/JUPYTER/MACOS/GLOBAL_COPILOT/16X9/PIECES_FOR_DEVELOPERS-JUPYTER-GLOBAL_COPILOT-MACOS-16X9-9_26_2023.GIF)

### Maximize productivity with our Flagship Desktop App

Utilize the Pieces [Flagship Desktop App](https://pieces.app) in combination with our Jupyter Plugin to streamline your workflow and enhance your development productivity.

- Get back in flow with our Workflow Activity View
- Save time with In-Project Snippet Discovery
- Enjoy real-time and scope-relevant suggestions
- Extract and use code and text from screenshots

![Save to Pieces via Button](https://storage.googleapis.com/pieces_multimedia/PROMOTIONAL/PIECES_FOR_DEVELOPERS/JUPYTER/MACOS/WITH_DESKTOP_APP/16X9/PIECES_FOR_DEVELOPERS-JUPYTER-WITH_DESKTOP_APP-MACOS-6_22_2023.png)

<div class="nav">
    <h3>Socials</h3>
</div>
<div class="nav">
    <a href="https://discord.gg/5AN7rVXEES" style="display: inline-block; text-decoration: none; border-radius: 4px;">Discord</a>		<a href="https://www.youtube.com/@getpieces" style="display: inline-block; text-decoration: none; border-radius: 4px;">YouTube</a>		<a href="https://twitter.com/@getpieces" style="display: inline-block; text-decoration: none; border-radius: 4px;">Twitter</a>		<a href="https://www.linkedin.com/company/getpieces" style="display: inline-block; text-decoration: none; border-radius: 4px;">LinkedIn</a>		<a href="https://www.facebook.com/getpieces" style="display: inline-block; text-decoration: none; border-radius: 4px;">Facebook</a>
</div>

## Requirements

- JupyterLab >= 4.0.0

## Install

To install the extension, execute:

```bash
pip install jupyter-pieces
```

## Uninstall

To remove the extension, execute:

```bash
pip uninstall jupyter-pieces
```

## Contributing

### Development install

Note: You will need NodeJS to build the extension package.

The `jlpm` command is JupyterLab's pinned version of
[yarn](https://yarnpkg.com/) that is installed with JupyterLab. You may use
`yarn` or `npm` in lieu of `jlpm` below.

Create and activate your conda environment:

```bash
conda create -n jupyterlab-ext --override-channels --strict-channel-priority -c conda-forge -c nodefaults jupyterlab=4 nodejs=18 git copier=8 jinja2-time

conda activate jupyterlab-ext
```

Then:

```bash
# Clone the repo to your local environment
# Change directory to the jupyter-pieces directory
# Install package in development mode
pip install -e "."
# Link your development version of the extension with JupyterLab
jupyter labextension develop . --overwrite
# Rebuild extension Typescript source after making changes
jlpm build
```

You can watch the source directory and run JupyterLab at the same time in different terminals to watch for changes in the extension's source and automatically rebuild the extension.

```bash
# Watch the source directory in one terminal, automatically rebuilding when needed
jlpm watch
# Run JupyterLab in another terminal
jupyter lab
```

With the watch command running, every saved change will immediately be built locally and available in your running JupyterLab. Refresh JupyterLab to load the change in your browser (you may need to wait several seconds for the extension to be rebuilt).

By default, the `jlpm build` command generates the source maps for this extension to make it easier to debug using the browser dev tools. To also generate source maps for the JupyterLab core extensions, you can run the following command:

```bash
jupyter lab build --minimize=False
```

### Development uninstall

```bash
pip uninstall jupyter-pieces
```

In development mode, you will also need to remove the symlink created by `jupyter labextension develop`
command. To find its location, you can run `jupyter labextension list` to figure out where the `labextensions`
folder is located. Then you can remove the symlink named `jupyter-pieces` within that folder.

### Packaging the extension

See [RELEASE](RELEASE.md)
