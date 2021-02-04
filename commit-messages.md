# Ten Birds - Commit Messages



## List


|                        | Type            | Emoji                  | Code                     | When to use it                                               | Semantic versioning |
| ---------------------- | :-------------- | :--------------------- | :----------------------- | :----------------------------------------------------------- | ------------------- |
| **:white_check_mark:** |                 | :construction:         | `:construction:`         | Work in progress.                                            |                     |
| **:white_check_mark:** | BREAKING CHANGE | :boom:                 | `:boom:`                 | Introducing a Breaking Change                                | major               |
| **:white_check_mark:** | feat            | :sparkles:             | `:sparkles:`             | Introducing new features                                     | minor               |
| **:white_check_mark:** | fix             | :bug:                  | `:bug:`                  | Fixing a bug                                                 | patch               |
| **:white_check_mark:** | fix             | :shirt:                | `:shirt:`                | Fixing linter warnings                                       | patch               |
| **:white_check_mark:** | fix             | :lock:                 | `:lock:`                 | Fixing security issues                                       | patch               |
| **:white_check_mark:** | fix             | :pencil2:              | `:pencil2:`              | Fixing typos                                                 | patch               |
| **:white_check_mark:** | fix             | :ambulance:            | `:ambulance:`            | Critical hotfix                                              | patch               |
| **:white_check_mark:** | docs            | :pencil:               | `:pencil:`               | Writing docs                                                 |                     |
| **:white_check_mark:** | docs            | :bulb:                 | `:bulb:`                 | Just adding, removing or updating a comment.<br />Documenting source code |                     |
| **:white_check_mark:** | style           | :lipstick:             | `:lipstick:`             | Updating the UI and style files                              | patch               |
| **:white_check_mark:** | i18n            | :globe_with_meridians: | `:globe_with_meridians:` | Internationalization and localization                        | patch               |
| **:white_check_mark:** | refactor        | :recycle:              | `:recycle:`              | Refactoring code                                             |                     |
| **:white_check_mark:** | perf            | :zap:                  | `:zap:`                  | Improving performance                                        |                     |
| **:white_check_mark:** | build           | :heavy_plus_sign:      | `:heavy_plus_sign:`      | Adding a dependency                                          |                     |
| **:white_check_mark:** | build           | **:heavy_minus_sign:** | `:heavy_minus_sign:`     | Removing a dependency                                        |                     |
| **:white_check_mark:** | build           | :arrow_up:             | `:arrow_up:`             | Upgrading dependencies                                       |                     |
| **:white_check_mark:** | build           | :arrow_down:           | `:arrow_down:`           | Downgrading dependencies                                     |                     |
| **:white_check_mark:** | resp            | :iphone:               | `:iphone:`               | Working on responsive design                                 | patch               |
| **:white_check_mark:** | gitignore       | :see_no_evil:          | `:see_no_evil:`          | Adding or updating a .gitignore file                         |                     |
| **:white_check_mark:** | release         | :rocket:               | `:rocket:`               | Release                                                      |                     |



## Structure

The commit message should be structured as follows:

> ```
> <optional emoji> <type> (<scope>): <description>
> 
> <optional body>
> 
> <optional footer>
> ```
>

<u>**e.g.:**</u>

> :bug: fix: Fix the "Crop image to fill entire column"
>
> * Use correct class name for media container element
>
> * Rename media container class name for consistency
