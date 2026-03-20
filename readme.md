
синтакиси маркдаун - https://docs.github.com/ru/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

# title 1
**жирный** __жирный__ 
* список
_курсив_
~~ЗАЧЕРКНУТО~~
*** 
***жирный и курсив***
<sub>нижний регистр</sub>
<sup>верхний регистр</sup>
<ins>подчеркнуть</ins>
>цитата

Use `git status` to list

Some basic Git commands are:
```
пgit status
пgit add
пgit commit
```
The background color is #ffffff for light mode and #000000 for dark mode.

ШЕСТНАДЦАТЬ	`#RRGGBB`
RGB	`rgb(R,G,B)`
HSL	`hsl(H,S,L)`
This site was built using [GitHub Pages](https://pages.github.com/).

# Section Heading

Some body text of this section.

ссылка на якарь
<a name="my-custom-anchor-point"></a>
Some text I want to provide a direct link to, but which doesn't have its own heading.

(… more content…)

[A link to that custom anchor](#my-custom-anchor-point)

перенос строки:

Этот пример   
займет две строки.

This example\
Will span two lines

This example<br/>
Will span two lines

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)
HTML <picture>-элемент поддерживается.

список:

- George Washington
* John Adams
+ Thomas Jefferson

1. First list item
   - First nested list item
     - Second nested list item

список задач:

- [x] #739
- [ ] https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-tasklists про списк задач
- [ ] Add delight to the experience when all tasks are complete :tada:
- [ ] \(Optional) Open a followup issue

@github/support What do you think about these updates? - упомянание человека в гите
https://docs.github.com/en/organizations/organizing-members-into-teams/about-teams - о камандах организации
# - список предлагаеммых задач и запросов на слияние в репозитории - https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/autolinked-references-and-urls

Настройка автоматических ссылок для указания на внешние ресурсы. - https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/configuring-autolinks-to-reference-external-resources

@octocat :+1: This PR looks great - it's ready to merge! :shipit: - эмодзи (спаргалка эммодзи - https://github.com/ikatyang/emoji-cheat-sheet/blob/github-actions-auto-update/README.md)

сноски:

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, add 2 spaces to the end of a line.  
This is a second line.

предупреждения:
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.


<!-- комментарий -->
игнорирование комманд с помощью \ :
Let's rename \*our-new-project\* to \*our-old-project\*.
