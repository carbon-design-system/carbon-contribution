## Overview

Thank you for contributing to Carbon! Below you will find a quick overview of all the assetcs in this folder as well as the steps for contriubting a component to Carbon.

## Component Contributing Template

### Example Folder

This folder contains images and example markdown files for Carbon's Select component. Use this as a model when writing the content for your contributed component. To see the original atboards for the Select images open the Sketch file in the Sketch folder. 

### Contribution Folder

##### Markdown Folder
This folder contains template markdown files for both the style and usage tab documentation. For style and usage content examples check out the markdown files in thes examples folder.

Once you are ready to export your images from Sketch, save them in the `images` folder. This will ensure that your images appear in the markdown rendering when you add the image markdown into the file. 

If you need a markdown editor, we recommend a [MacDown](https://macdown.uranusjr.com/) for mac users and [Typora](https://typora.io/) for PC users.

##### Sketch Folder
The Sketch file makes it easy to create spec'ed images for component documentaiton. The Getting Started page contains guidelines for Carbon image creation. The Example page contains example artboards of the spec'ed Select component. The Image Template page contains all the image sizes that Carbon uses for image documentation. The Style and Usage pages are where you will paste the image template artboards and create your own examples. 

There is also a sketch palette for Carbon specs in this folder. To use this palette you need to download the [Sketch Palette's pluggin](https://github.com/andrewfiorillo/sketch-palettes) and enable it in Sketch.


## Heavy Contribution Process

#### 1. Open an issue proposing the new component

Create an issue in the [carbon-components](https://github.com/carbon-design-system/carbon-components) repo. The following must be included in the issue in order to be reviewed by Carbon:

Issue title should be formatted as `Contribution: New component name`.

The issue description should include the following:

* Name of component that contributor wants to add
* The research supporting and reasoning behind the proposed change
* Screen shot(s) of the proposed design and states
* Cloud link to the sketch file and/or PR of the coded component
* Names of the contributing designer(s) & developer(s) working on this contribution (GitHub handles are best)

A Carbon team member will label the issue as `contributing`.

#### 2. Carbon will reach out to set up a meeting with all contributors

One designer and one developer from the Carbon team will be in this meeting. The following will be reviewed:

* The research showing why Carbon needs this addition/change
* The new component designs and its use cases
* The Carbon designer and developer will determine if the new component should be brought into the main design library or into one of the add-on repos
* (If necessary) Carbon will give feedback on requests for changes, updates, etc. and set up a follow-up meeting(s) to review again

#### 3. Creating website assets

If the proposed component is being brought into the main library, the contributor will utilize the [Heavy Contribution Template]() to create all necessary images and documentation assets for the component's style and usage tabs. The instructions for the sketch template and markdown files can be found in the `ReadME.md` file in the template folder. It is strongly recommended that contributors review the Carbon [production guidelines](https://github.com/carbon-design-system/design-system-website/wiki/Production-guidelines) before creating style and usage images. 

#### 4. Submission and review

Once all template assets have been complete, zip the entire Heavy Contribution Template folder and save it to Box (or your preferred cloud storage). Add a link to the zipped folder to the original GitHub issue. Please make sure the link permissions are set so anyone can view and download the folder. The Carbon team will do another review of all images and documentation for the style and usage content. If it does not meet the Carbon standard the contributor may be asked to make changes before it is given final approval.

#### 6. Create a PR

Once Carbon has made the final approval, the contributor needs to submit their changes to our repos. The first PR needs to be made to the [carbon-components repo](https://github.com/carbon-design-system/carbon-components) to add the code for the new component. The second PR needs to be made to the [design-system-website repo](https://github.com/carbon-design-system/design-system-website) to add the new component section. The component folder should be added into `src > content > components`. Make sure the folder follows the  `component-name` naming structure and includes the following:

- `images` folder with component asset images
- style.md
- usage.md
- code.md

Please make sure to include the initial issue number and link in both PR's. If you do not know how to make a PR, view our [instructions](https://github.com/carbon-design-system/design-system-website/wiki/Creating-a-PR).


#### 7. The Carbon team will review the PR

For the final review, a Carbon developer and designer will review the contributor's PR's. If any changes need to be made they will comment on the PR, if its ready to go they will approve the PR and merge it as it fits the Carbon roadmap. 
