# vim9notes.vim
A Vim9script plugin for easy note management using Typst markups. This plugin allows you to create, edit, and manage your notes efficiently within Vim, leveraging the powerful Typst markup language for formatting.

## Features

- **Easy Note Creation**: Quickly create new notes with a simple command.
- **Typst Markup Support**: Use Typst syntax for formatting your notes, including headings, lists, and more.
- **Search and Filter**: Easily search through your notes to find specific content.
- **Customizable Templates**: Create and use templates for different types of notes.
- **Integration with Vim**: Seamlessly integrates with your existing Vim workflow.

## Installation

To install the plugin, you can use your favorite plugin manager. For example, with `vim-plug`, add the following line to your `.vimrc` :

```vim
Plug 'sevehub/vim9notes.vim'
```

Then run :PlugInstall in Vim.

## Usage
Creating a New Note
To create a new note, use the command:

:Note
This will open a new buffer where you can start writing your note using Typst markup.

## Formatting Notes
You can use the following Typst syntax for formatting:

Headings: Use = for H1, == for H2, etc.
Bold and Italics: Use **text** for bold and *text* for italics.

## Searching Notes
To search through your notes, use:

:SearchNotes <search_term>
This will display a list of notes containing the search term.

## Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
Thanks to the Typst community for their amazing markup language.
