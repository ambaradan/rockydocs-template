---
title: RockyDocs Example
author: your_name
contributors: other_names
tags:
    - neovim
    - editor
    - markdown
---
<!-- vale off -->
## Rocky Linux Documentation Project

### Overview

The Rocky Linux documentation project is an open-source initiative aimed at creating a comprehensive and user-friendly documentation for the Rocky Linux operating system. The project is driven by a community of contributors who are passionate about providing high-quality documentation to help users get the most out of Rocky Linux.
History

Rocky Linux is a relatively new operating system, but its roots date back to the early days of CentOS. When CentOS announced its shift in focus towards CentOS Stream, a group of developers decided to fork the project and create a new, community-driven distribution. Rocky Linux was born, and with it, the need for a robust documentation project.
Goals and Objectives

The primary goal of the Rocky Linux documentation project is to provide accurate, up-to-date, and easy-to-understand documentation for users of all skill levels. The project aims to cover a wide range of topics, including:

* Installation and configuration
* System administration
* Security and hardening
* Networking and clustering
* Package management and software installation
* Troubleshooting and debugging

### Target Audience

The Rocky Linux documentation project is designed to cater to a diverse range of users, including:

* System administrators
* Developers
* Power users
* New users

### Contributing to the Project

The Rocky Linux documentation project is an open-source initiative, and contributions are welcome from anyone interested in helping. Whether you're a seasoned writer or a beginner, you can contribute to the project by:

* Writing new content
* Reviewing and editing existing content
* Translating documentation into other languages
* Providing feedback and suggestions

## MkDocs Material in Rocky Linux Documentation

The Rocky Linux Documentation Project utilizes MkDocs, a popular static site generator, with the MkDocs Material theme, which provides an enhanced Markdown experience. MkDocs Material is a theme designed for MkDocs, offering a range of extra features and functionalities that extend the capabilities of standard Markdown.

=== "Key Features of MkDocs Material"

    - **Extended Markdown syntax**: MkDocs Material includes additional Markdown features, such as syntax highlighting, code blocks, and tables, making it easier to create complex documentation.
    - **Customizable appearance**: The theme provides a high degree of customization, allowing the Rocky Linux Documentation Project to tailor the site's layout, colors, and typography to meet specific branding and design requirements.
    - **Responsive design**: MkDocs Material ensures that the documentation site is fully responsive, providing an optimal user experience across various devices and screen sizes.
    - **Integrated search**: The theme includes a built-in search engine, making it easy for users to find relevant information within the documentation.
    - **Navigation and menus**: MkDocs Material offers flexible navigation and menu options, enabling the documentation team to organize content in a logical and user-friendly manner.

=== "Benefits of using MkDocs Material"

    - **Improved readability**: MkDocs Material's clean and minimalistic design enhances the overall readability of the documentation, making it easier for users to navigate and understand complex topics.

    - **Enhanced collaboration**: The theme's flexibility and customization options facilitate collaboration among contributors, ensuring that the documentation remains accurate, up-to-date, and consistent.
    - **Simplified content creation**: MkDocs Material's extended Markdown features and intuitive interface make it easier for documentation authors to create high-quality content without requiring extensive technical expertise.
    - **Consistent branding**: By leveraging MkDocs Material's customization options, the Rocky Linux Documentation Project can maintain a consistent visual identity and branding throughout the documentation.

By utilizing MkDocs with the MkDocs Material theme, the Rocky Linux Documentation Project can create a professional-looking, user-friendly, and highly functional documentation site that meets the needs of its community.

## MkDocs Material Main Features

=== "Admonitions"

    MkDocs Material provides a feature called admonitions, which allows you to draw attention to important information, warnings, or notes in your documentation. Admonitions are special blocks of text that are displayed with a unique style and icon to convey their importance.

    MkDocs Material supports the following types of admonitions:

    - Note: Used to provide additional information or context.
    - Tip: Used to offer helpful advice or suggestions.
    - Warning: Used to warn users of potential dangers or pitfalls.
    - Caution: Used to advise users to exercise caution when performing a particular action.
    - Important: Used to highlight crucial information that users should be aware of.
    - Danger: Used to indicate a potential hazard or risk.

    Admonitions can be used to make your documentation more engaging, informative, and effective in conveying important information to your users.

    **Examples**:

    !!! Note "Note Title"

        Your note here

    !!! Danger "Danger Title"

        Your danger admonition

    **Code**

    ```markdown
    !!! Note "Note Title"

        Your note here

    !!! Danger "Danger Title"

        Your danger admonition

    ```

=== "Code Blocs"

    MkDocs Material provides a range of features for working with code blocks, making it easier to create and display code snippets in your documentation. These features include:

    - Syntax Highlighting: Supports syntax highlighting for a wide range of programming languages.
    - Line Numbers: Allows you to enable line numbers for code blocks.
    - Custom Titles: Enables you to add custom titles to code blocks.
    - Inline Code: Supports inline code snippets by wrapping the code in single backticks.
    - Code Block Options: Provides several options for customizing code blocks, including enabling line numbers, highlighting specific lines, adding custom titles, and specifying the programming language.
    - Multiple Language Support: Supports code blocks in multiple languages, allowing you to specify the language for each code block and apply syntax highlighting accordingly.

    By utilizing these code block features, you can create professional-looking documentation with clear and readable code snippets.

=== "Annotations"

    MkDocs Material provides a feature called annotations, which allows you to add notes, comments, and other metadata to your documentation. Annotations are a way to provide additional context and information to your users, making it easier for them to understand and use your documentation.

=== "Content Tabs"

    MkDocs Material provides a feature called content tabs, which allows you to organize and display related content in a tabbed interface. Content tabs are a great way to break up long pages into smaller, more manageable sections, making it easier for users to find the information they need.

    **Benefits of Content Tabs**

    Content tabs offer several benefits, including:

    - Improved organization: Content tabs help to organize related content into a single, easy-to-use interface.
    - Reduced clutter: By breaking up long pages into smaller sections, content tabs reduce clutter and make it easier for users to focus on the information they need.
    - Increased usability: Content tabs make it easy for users to navigate and find the information they need, improving the overall usability of your documentation.
    - Enhanced user experience: Content tabs provide a clean and intuitive interface, enhancing the overall user experience and making it more engaging.

=== "Data Tables"

    MkDocs Material provides a feature called data tables, which allows you to display data in a tabular format. Data tables are a great way to present complex data in a clear and concise manner, making it easier for users to understand and analyze the information.

    **Benefits of Data Tables**

    Data tables offer several benefits, including:

    - Improved readability: Data tables make it easy to read and understand complex data by presenting it in a clear and organized format.
    - Enhanced comparison: Data tables enable users to compare data across different categories, making it easier to identify trends and patterns.
    - Increased usability: Data tables provide a simple and intuitive way to display data, making it easier for users to navigate and understand the information.
    - Better decision-making: By presenting data in a clear and concise manner, data tables enable users to make more informed decisions.

    Types of Data Tables

    MkDocs Material supports several types of data tables, including:

    - Simple tables: These are basic tables that display data in a simple format.
    - Sortable tables: These tables allow users to sort the data by clicking on the column headers.
    - Filterable tables: These tables allow users to filter the data by entering keywords or phrases.
    - Responsive tables: These tables adapt to different screen sizes and devices, ensuring that the data is always displayed in a clear and readable format.

=== "Diagrams"

    MkDocs Material provides a feature called diagrams, which allows you to create and display diagrams in your documentation. Diagrams are a great way to visualize complex information, making it easier for users to understand and analyze the data.

    **Benefits of Diagrams**

    Diagrams offer several benefits, including:

    Improved understanding: Diagrams help to simplify complex information, making it easier for users to understand the relationships between different components.
    Enhanced visualization: Diagrams provide a visual representation of the data, making it easier for users to identify trends and patterns.
    Increased engagement: Diagrams make the documentation more engaging and interactive, helping to keep users interested and motivated.
    Better communication: Diagrams facilitate communication between teams and stakeholders, ensuring that everyone is on the same page.

    Types of Diagrams

    MkDocs Material supports several types of diagrams, including:

    Flowcharts: These diagrams show the steps involved in a process or workflow.
    Sequence diagrams: These diagrams show the sequence of events or interactions between different components.
    Class diagrams: These diagrams show the relationships between different classes or objects.
    State diagrams: These diagrams show the different states or statuses of a system or component.

    ```mermaid
    graph LR
     A[Develop] --> B{Error};
     B -->|Yes| C[Fix];
     C --> D[Debug];
     D --> B;
     B ---->|No| E[Update];
    ```

    ```mermaid
    sequenceDiagram
       participant User as :User with Lua Script
       participant Interpreter as "Lua Interpreter"
       participant Lexer as "Lexer (Tokenization)"
       participant Parser as "Parser (Syntax Analysis)"
       participant Executor as "Executor (Code Execution)"
        participant Memory as "Memory Management"

       Note over User,Interpreter: User Provides Lua Script
       User->>Interpreter: Load Script
       Interpreter->>Lexer: Tokenize Script
       Lexer->>Interpreter: Return Tokens
       Interpreter->>Parser: Parse Tokens
       Parser->>Interpreter: Abstract Syntax Tree (AST)
       Interpreter->>Executor: Execute AST
       Executor->>Memory: Allocate/Deallocate Memory as Needed
       Memory->>Executor: Provide Memory Access
       Executor->>Interpreter: Execution Results
       Interpreter->>User: Return Results
       Note over Interpreter,User: Script Execution Completed

       alt Error Handling
           Interpreter->>User: Report Syntax Errors
       end
    ```

=== "Footnotes"

    MkDocs Material provides a feature called footnotes, which allows you to add notes or references to the bottom of a page. Footnotes are a great way to provide additional information or context to your readers without disrupting the flow of your main content.

    Benefits of Footnotes

    Footnotes offer several benefits, including:

    Improved readability: Footnotes allow you to keep your main content concise and focused, while still providing additional information or context to readers who need it.
    Enhanced credibility: Footnotes demonstrate that you have done your research and are willing to provide evidence to support your claims.
    Increased transparency: Footnotes provide a clear and transparent way to acknowledge sources and provide additional information.

    Types of Footnotes

    MkDocs Material supports several types of footnotes, including:

    Inline footnotes: These are footnotes that are included directly in the text, using a superscript number or symbol.
    Reference footnotes: These are footnotes that are included at the bottom of the page, using a numbered or symbol-based reference system.

    Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit.

    [^1]: Lorem ipsum dolor sit amet, consectetur adipiscing elit.

### Formatting Feature

MkDocs Material provides a robust formatting feature that allows you to customize the appearance of your documentation. This feature is essential for creating professional-looking documents that are easy to read and understand.

Benefits of Formatting

The formatting feature in MkDocs Material offers several benefits, including:

: Improved Readability

: MkDocs Material's formatting feature allows you to create clear headings, subheadings, and paragraphs, making it easier for readers to follow your content. You can use bold, italics, and other formatting options to draw attention to important information and create visual hierarchy.

: Enhanced Visual Appeal

: With MkDocs Material's formatting feature, you can add images, diagrams, and other visual elements to break up text and make your content more engaging. The feature also allows you to customize the layout and design of your pages, making it easier to create a consistent look and feel throughout your documentation.

: Increased Accessibility

: MkDocs Material's formatting feature includes options for adding alt text to images, making your content more accessible to readers with visual impairments. The feature also allows you to create tables, lists, and other structured content that is easy to read and understand.

To get the most out of MkDocs Material's formatting feature, follow these best practices:

* Use clear and concise headings to organize your content.
* Use bold and italics to draw attention to important information.
* Use images and diagrams to break up text and create visual interest.
* Use code blocks to display technical information and examples.
* Use tables and lists to create structured content that is easy to read and understand.

Keyboard Keys Feature

MkDocs Material provides a feature for adding keyboard keys to your documentation, making it easier to explain complex keyboard shortcuts and commands. This feature is essential for creating technical documentation, such as user manuals, tutorials, and guides.

Benefits of Adding Keyboard Keys

The feature for adding keyboard keys in MkDocs Material offers several benefits, including:

Improved Readability

    Adding keyboard keys can make your documentation more readable and easier to understand, especially for technical topics that require complex keyboard shortcuts.
    Keyboard keys can be used to illustrate keyboard shortcuts, making it easier for readers to follow along and understand the instructions.

Enhanced Clarity

    Adding keyboard keys can help clarify complex keyboard shortcuts and commands, making it easier for readers to understand the instructions.
    Keyboard keys can be used to break down complex commands into smaller, more manageable parts, making it easier for readers to follow along.

Increased Accessibility

    Adding keyboard keys can make your documentation more accessible to readers with visual impairments, as it provides a clear and concise way to explain complex keyboard shortcuts.
    MkDocs Material's feature for adding keyboard keys includes options for adding accessibility features, such as alt text for images and semantic HTML tags.

Images Feature

MkDocs Material provides a robust images feature that allows you to add visual elements to your documentation. This feature is essential for creating engaging and informative content that captures the attention of your readers.
Benefits of Images

The images feature in MkDocs Material offers several benefits, including:
Enhanced Visual Appeal

    Images can help break up large blocks of text, making your content more scannable and easier to read.
    High-quality images can add a professional touch to your documentation, making it more visually appealing.

Improved Understanding

    Images can help illustrate complex concepts, making them easier for readers to understand.
    Diagrams, flowcharts, and other visual aids can provide a clear and concise way to communicate information.

Increased Engagement

    Images can help capture the attention of your readers, drawing them into your content and encouraging them to read more.
    Relevant and interesting images can help create an emotional connection with your readers, making your content more memorable.

Lists Feature

MkDocs Material provides a robust lists feature that allows you to create ordered and unordered lists in your documentation. This feature is essential for presenting information in a clear and concise manner, making it easier for readers to understand and follow your content.
Benefits of Lists

The lists feature in MkDocs Material offers several benefits, including:
Improved Readability

    Lists can help break up large blocks of text, making your content more scannable and easier to read.
    Ordered and unordered lists can provide a clear and concise way to present information, making it easier for readers to follow your content.

Enhanced Organization

    Lists can help you organize your content in a logical and structured way, making it easier for readers to understand the relationships between different pieces of information.
    Nested lists can be used to create a hierarchy of information, making it easier for readers to see the bigger picture.

Increased Accessibility

    Lists can be used to provide a clear and concise way to present information, making it easier for readers with visual impairments to understand your content.
    MkDocs Material's lists feature includes options for adding accessibility features, such as alt text for images and semantic HTML tags.

Types of Lists

MkDocs Material supports several types of lists, including:
Ordered Lists

    You can use the 1., 2., 3., etc. syntax to create ordered lists.
    Ordered lists can be used to present information in a specific order, such as a step-by-step guide or a list of ranked items.

Unordered Lists

    You can use the *, -, or + syntax to create unordered lists.
    Unordered lists can be used to present information in a non-specific order, such as a list of features or a list of ideas.

Nested Lists

    You can use indentation to create nested lists.
    Nested lists can be used to create a hierarchy of information, making it easier for readers to see the bigger picture.

Definition Lists

    You can use the ; syntax to create definition lists.
    Definition lists can be used to present information in a key-value format, such as a list of terms and definitions.

Tooltips Feature

MkDocs Material provides a robust tooltips feature that allows you to add interactive and informative tooltips to your documentation. This feature is essential for providing additional context and information to your readers, making it easier for them to understand your content.
Benefits of Tooltips

The tooltips feature in MkDocs Material offers several benefits, including:
Improved User Experience

    Tooltips can provide additional context and information to your readers, making it easier for them to understand your content.
    Tooltips can be used to explain technical terms, provide definitions, or offer additional resources.

Enhanced Engagement

    Tooltips can be used to add interactive elements to your documentation, making it more engaging and interesting for your readers.
    Tooltips can be used to provide additional information, such as images, videos, or audio files, to supplement your text.

Increased Accessibility

    Tooltips can be used to provide additional information to readers with visual impairments, making it easier for them to understand your content.
    MkDocs Material's tooltips feature includes options for adding accessibility features, such as alt text for images and semantic HTML tags.
