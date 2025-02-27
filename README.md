# Twenty Twenty-Three

Welcome to the development repository for the default theme that will launch with WordPress 6.1.

## About

Twenty Twenty-Three is a stripped-back and minimal version of [Twenty Twenty-Two](https://wordpress.org/themes/twentytwentytwo/), and will include a diverse collection of style variations designed by members of the community.

## Contributing

If you would like to contribute code, the list of [open issues](https://github.com/WordPress/twentytwentythree/issues) is a great place to start looking for tasks. [Pull requests](https://github.com/WordPress/twentytwentythree/pulls) are preferred when linked to an existing issue.

Contributing is not just for developers! There are many opportunities to help with [testing](#getting-started), triage, discussion, designing and building variations, and more. Please look through [open issues](https://github.com/WordPress/twentytwentythree/issues), and join in wherever you feel most comfortable.

If you'd like to help with triage, let @mikachan and @beafialho know here or in [WordPress.org's Slack instance](https://make.wordpress.org/chat/). The #core-themes-projects channel is a good place to start. We'll help you get set up with the ability to add labels to issues and PRs.

### Contributing Style Variations

A big part of Twenty Twenty-Three is to emphasize a diverse collection of style variations, so this is a great way to contribute to the theme! You can read more about this in the [project kick-off post](https://make.wordpress.org/design/2022/08/10/twenty-twenty-three-default-theme-project-kickoff/).

#### Design a style variation
This can be done a few different ways, including:

- Create an alternate theme.json file to the one provided by the theme and change values directly in the code.
- Make changes in the Global Styles panel in the Site Editor. You can save these changes as a new style variation using the [Create Block Theme plugin](https://wordpress.org/plugins/create-block-theme/).
- Design static mockups in Figma or a similar program.

#### Submit your style variation
When you're ready to submit, please create a new issue and share your designs:

- Theme.json files can be submitted as code or as zip files. 
- Add images that showcase the look & feel of the variation.
- Include a style guide with design specifications — this should include details on typography, colors, spacing, etc. Here’s an [example](https://www.figma.com/community/file/1136340417938880987).

### Getting Started

To get started with development:

1. Set up a WordPress instance, we recommend [wp-env](https://developer.wordpress.org/block-editor/handbook/tutorials/devenv/) or [Local](https://localwp.com/) as an alternative to docker.
2. Install the [Gutenberg plugin](https://wordpress.org/plugins/gutenberg/)
3. Clone / download this repository into your `/wp-content/themes/` directory

### Tips for Contributors
  
- Similar to Twenty Twenty-Two, a goal for the theme is to have as little CSS as possible. Much of the theme's visual treatments should be handled by the Block Editor and Global Styles. As a general rule, if multiple themes would benefit from the CSS you're considering adding, it might reasonably be provided by Gutenberg instead. Let's include clear code comments for any CSS we do include.
- Similarly, let's refrain from building any custom-built PHP or JavaScript-based workarounds for functionality that might reasonably be provided by the Block Editor. Twenty Twenty-Three will be a block theme, so let's keep its code simple.
- In accordance to those last two bullets, this theme has no required build process.
- If you've helped contribute to the theme in any way, you deserve credit! Folks will be updating [CONTRIBUTORS.md](CONTRIBUTORS.md) periodically with names of contributors, but feel free to open a PR or issue if we leave someone out.

## Requirements

- Gutenberg plugin (latest)
- WordPress 5.9+
- PHP 5.6+
- License: [GPLv2](http://www.gnu.org/licenses/gpl-2.0.html) or later

Some theme features / PRs may require Gutenberg trunk and will be described or tagged accordingly.

## Resources

- [Twenty Twenty-Three Figma Mockups](https://www.figma.com/community/file/1139275543113752375)
- [Twenty Twenty-Three Project kickoff post](https://make.wordpress.org/design/2022/08/10/twenty-twenty-three-default-theme-project-kickoff/)
- [Setting up a development environment](https://developer.wordpress.org/block-editor/handbook/tutorials/devenv/)
- [Create Block Theme plugin](https://github.com/WordPress/create-block-theme)
- [Block Theme documentation](https://developer.wordpress.org/block-editor/how-to-guides/themes/block-theme-overview)
- [Global Styles & theme.json documentation](https://developer.wordpress.org/block-editor/how-to-guides/themes/theme-json/)

## Timeline

The theme will be released with WordPress 6.1 and follow the key dates / milestones associated with [its development schedule](https://make.wordpress.org/core/6-1).
