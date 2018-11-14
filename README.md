# Holo-UI-Tools
A repository for information, tools, components, etc. for building Holo user interfaces.

## Documentation

### HOLO Brand Guidelines

**Note:** The brand guidelines were developed initially for corporate media.  Not all specifications in the HOLO Brand Guidelines apply to UI development.

* [HOLO Brand Guidelines (pdf)](documents/HOLO_Brand_Guidelines.pdf)

The following sections are a distillation and summary of some key points to consider.  This is not exhaustive.  Be sure to get familiar with the full HOLO Branding Guidelines as well.

#### Logo and Usage

##### **Section:** PRIMARY LOGO (p. 7)

Several logos are included in the `images/official_logos/` folder.

Example:

<img src="images/official_logos/Holo_Primary_Logo_Black.png" alt="Holo Primary Logo Black" width="300px"/>

##### **Section:** LOGO APPLICATION DON’TS (p. 11)
> * DO NOT DISTORT
> * DO NOT ALTER THE LOGO SHAPE
> * DO NOT USE UNSPECIFIED COLORS
> * ENSURE LOGO FIDELITY


#### Color

##### **Section:** SOLID COLOR PALETTE (p. 13)

> ![#00838D](https://placehold.it/15/00838D/000000?text=+) `#00838D `
> 
> ![#3A277A](https://placehold.it/15/3A277A/000000?text=+) `#3A277A `
> 
> ![#1da9c7](https://placehold.it/15/1da9c7/000000?text=+) `#1da9c7 `
> 
> ![#4E5568](https://placehold.it/15/4E5568/000000?text=+) `#4E5568 `
> 
> ![#000000](https://placehold.it/15/000000/000000?text=+) `#000000 `


##### **Section:** SHADES AND TINTS (p. 14)

> To add more variety shades and tints can be derived from the brand color palette.


#### Typography

##### **Section:** BRAND SPECIFIC TYPOGRAPHIC FAMILY (p. 17)

> The HOLO font is 
> 
> ![font/Raleway-200.v12.png](font/Raleway-200.v12.png)
> 
> Specimen: [https://fonts.google.com/specimen/Raleway?selection.family=Raleway](https://fonts.google.com/specimen/Raleway?selection.family=Raleway)

Font weights and further typographic instructions (alignments, etc.) are specified in the HOLO Branding Guidelines.
 

### HOLO Manual of Style

* TBD


## Code

This section is for actual code and code libraries relevant to Holo UI development.

### Current Tools

#### Internal 

The current primary internal tools are (The goal is to have UI code for the following tools):

##### Submodules

The following are submodules of this git repository

1. an empty 'scaffold' app framework
  * [https://github.com/Holo-Host/hc-react-redux-framework](https://github.com/Holo-Host/hc-react-redux-framework)
2. a separate library of just the reusable Holo UI components themselves
  * goes here
3. the 1) empty 'scaffold' app framework from above, but that also includes the 2) Holo UI components library from above
  * goes here
 
The following are some key things to remember about using git repositories with submodules:

1. When you clone a repository with submodules use `git clone --recursive <project url>`
2. You can refresh the submodule at any time by going into the submodule folder and running `git submodule update --init --recursive`
3. When pushing to the a parent repository (like this one), be sure to force git to check that all changes to submodules have already been committed and pushed to their respective repositories first by running `git push --recurse-submodules=on-demand`
3. For reference see: [https://git-scm.com/book/en/v2/Git-Tools-Submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)


#### External

The current primary external tools are:

* React
* Redux
* Material UI
* Storybook

Additional packages and libraries support the primary tools in various ways.


