# Word-Press-heading-list-generator-Plugin

Automatically generates a hierarchical list for headings in WordPress pages/posts and displays it under the [heading_list] shortcode.

## Description

The "Heading List Generator" is a WordPress plugin that automatically generates a hierarchical list of headings in your pages/posts. It creates a hierarchical list with links to each heading, making it easy for users to navigate through the content. You can use the [heading_list] shortcode to display the generated list in your pages/posts.

## Features

- Automatically generates a hierarchical list for headings in your WordPress pages/posts.
- Uses a hierarchical structure with sub-items for lower-level headings.
- Excludes the page/post title from the generated list for a cleaner presentation.
- Easy-to-use shortcode to display the list in your content.
- Compatible with different themes and installations.

## How to Use

1. Install and activate the "Heading List Generator" plugin in your WordPress website.
2. Edit the page/post where you want to display the hierarchical list.
3. Add headings (H1 to H6) in the content editor. The plugin will automatically generate a list based on these headings.
4. To display the generated list, add the `[heading_list]` shortcode in your content where you want the list to appear.

## Example Usage

Suppose you have the following headings in your page/post:
<h1>This is Heading 1</h1>
<p>Content for Heading 1...</p>
<h2>This is Heading 1-1</h2>
<p>Content for Heading 1-1...</p>
<h2>This is Heading 1-2</h2>
<p>Content for Heading 1-2...</p>
<h3>This is Heading 1-2-1</h3>
<p>Content for Heading 1-2-1...</p>
```
When you add the [heading_list] shortcode in your content, the plugin will generate the following hierarchical list:

This is Heading 1
This is Heading 1-1
This is Heading 1-2
This is Heading 1-2-1
Plugin Customization
You can further customize the appearance of the generated list using custom CSS. The generated list will be wrapped in a <div> element with the ID "gheadinglistid". You can apply your custom styles to this container to change the list's appearance.

Support and Issues
If you encounter any issues or have questions regarding the "Heading List Generator" plugin, feel free to create a new issue on our GitHub repository. We'll be happy to assist you.

Contribution
We welcome contributions to the plugin! If you'd like to make any improvements or fix issues, please fork the repository and submit a pull request.

License
This plugin is licensed under the MIT License.

Developed by igy-apps.com
Visit: igy-apps.com
