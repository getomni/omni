# Contributing

First off, we would like to thank you for taking the time to contribute and make this a better project!

Here we have a set of instructions and guidelines to reduce misunderstandings and make the process of contributing to Omni as smooth as possible. We hope this guide makes the contribution process clear and answers any questions you may have.

## Language

While contributing or interacting in this project, please refrain from using any language other than English.

### For native English speakers

Try to use simple words and sentences. Don't make fun of non-native English speakers if you find something wrong with how they express themselves.

Try to encourage newcomers to express their opinions and make them comfortable enough to do so.

## Creating new themes

To submit a new theme, you need to follow these steps:

1. Create a new repository based on the [template](https://github.com/getomni/template).
   a) The branch name must be `main` (we will keep this name pattern from now on).
   b) The repository name must be lowercase and contain just the application name. E.g. `visual-studio-code`.
2. Build the new theme using the [Omni Color Palette](https://github.com/getomni/omni#color-palette).
3. Submit an issue with the link to your repository. Once the theme is accepted, we will move the repository under the Omni organization.
4. Open a PR to add the theme to the main repository (this one). Add it under its respective category (if it doesn't exist, you can create one). Also, make sure it is in alphabetical order.
   a) Update the total number of applications supported in the README.
5. Finally, after your theme is under the organization, update all links to match the new repository URL.
6. Spread the word by tweeting about your new theme and encouraging others to try it out.

## Maintaining a theme

After your theme is under the Omni organization, you're responsible for maintaining it. It's your responsibility to answer issues, review PR's and always keep it up-to-date.

Below you can find some guidelines that we follow:

- Always open pull requests when updating the theme (the `main` branch is protected by default);
- Review issues and PRs periodically;
- When you're going to add a new theme maintainer, add it in the README (team section) and the CODEOWNERS file;
- Share the theme on forums, Twitter and communities, to spread the word about your theme;
- In case you have any questions, reach out to [João Pedro Schmitz](https://github.com/jpedroschmitz).

## For organization owners

This section is for owners of the Omni organization in GitHub. It covers guides on how to add a new theme and some responsibilities.

### Adding new theme

To add a new theme to the organization, you need to review the proposed theme and make sure it follows the template and the color pallete.

When the theme is ready to be added to the organization, you need to:

1. Create a new team on the organization for the application;
   
   a) The team name is the application name;
   
   b) The team description is the application name + "theme maintainers";
   
   c) Remove yourself as a member (if you created it, don't do so).
   
2. Invite the theme creator to that team and ask to transfer the repository;
3. When the transfer is completed, add the repository to the created team;

   a) Set the repository permission to `write`.
   
4. Go to the theme repository and then:

   a) Disable wikis and projects (we don't use them);
   
   b) Disable packages (in the same place where we change description);
   
   c) Add tags (theme, omni, omni-theme, <tool>);
  
   d) Add description (🎨 Omni for <tool>);
  
   e) Add Open Graph Image (this is the [Figma link](https://www.figma.com/file/LJRny1i7eOagTXO4Her5u7/Omni-Project/duplicate), use it to generate an image);
   
   f) Add protection rule for the `main` branch (check the `Require pull request reviews before merging` and `Require review from Code Owners`);
   
   g) Close the issue and add a `transfer-completed` label;
   
   h) Ask the owner to add the new theme on the main repo;
   
   i) That's it, the theme is ready!
