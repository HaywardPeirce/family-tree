# Hayward's Family Tree Repository

This GitHub repository stores "raw" genealogical information about my family history.

This information is used to build the static site where you can view this information in a readable format at [familytree.peirce.xyz](https://familytree.peirce.xyz)

## Contributing

The purpose of exposing this information through GitHub is so that others may submit additional family history information about our shared ancestry, which provides even more value for all of us and our shared relations.

The following guide outlines the basic steps for making a contribution to this repository.

Note: as this information is stored in GitHub (so that changes can be tracked in GitHub), making a contribution will require a certain level of technical knowledge.

1. Install Git and create a GitHub account. For Windows users, it's recommended to install the [GitHub desktop app](https://desktop.github.com/).

Additional resources and guides on using the GitHub desktop app can be found in their [documentation](https://help.github.com/en/desktop), and in this [video](https://www.youtube.com/watch?v=C69-s2o9wqw).

2. After creating your GitHub account, and while logged into GitHub in your browser of choice, [fork this repository](https://guides.github.com/activities/forking/). This will create an exact copy of this repository, but on your GitHub account. This guide also includes details on completing the subsequent steps in this guide, which are outlined below:
3. If you are using the GitHub desktop app, then the previous guide include details on cloning the repository you just forked.
4. With a local copy of this repository (having forked my version, and cloned ("downloaded") a copy of your own version) you can now make changes to the family history information. This can be done by importing the `family.ged` file into your genealogy software of choice ( I recommend giving [Gramps](https://www.gramps-project.org/wiki/index.php?title=Download#MS_Windows) a try).

Please note: Please see the `Editing Style Guide` below for 

5. Once you have made all the changes you would like to include, export the updated family tree back into a GEDCOM file using the same `family.ged` file name (overwrite the existing file)
6. Now, [commit and push these changes](https://help.github.com/en/desktop/contributing-to-projects/committing-and-reviewing-changes-to-your-project) (select the windows tab in the guide to see how this works on windows) to your copy of this repository on GitHub.com
7. In order for these changes to be integrated back into my copy of this repository (which is what the generated site is build from) you will need to [submit a pull request](https://help.github.com/en/desktop/contributing-to-projects/creating-a-pull-request). This will allow me to review the changes you have made, and then incorperate them into the overall set of data. Please also make sure to include a subject and body for your commit so that it's clear what information you have updated/added to the overall dataset.

Done! Once the pull request is submitted I will review it and, provided the updates meet the requirements for contributing to this repository, incorperate the changes into the master set of genealogical information. From there, the generated site will rebuild to incorperate your changes.


## Editing Style Guide

In order to make sure that the way information is added, annotated, and updated is kept as consistant as possible acorss all contributors there are a number of guidelines for formatting information. They are (currently) as follows:

### Resources
Sources of family history information are important for corroboration and verification of information. Please make sure that all attachments are included in the `Resources` folder within this repository. This will make sure that they can successfully be linked to in the final generated site. 

These resource are broken down into a number of folders which (as of writing this) include `Birth Certificates`, `Census`, and `Marriage Certificates`, and you should place files you are looking to include in this repository in the relevant folder.

Additional folders may be added in the future, and resources may be moved around as needed.