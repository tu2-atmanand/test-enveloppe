---
publish: true
aliases:
  - What is New?/Changelog
---

# Changelog

See also [Breaking Changes](Breaking%20Changes.md): Tasks releases with version numbers ending `.0.0` indicate that an update to user vaults may be required.

_In recent [Tasks releases](https://github.com/obsidian-tasks-group/obsidian-tasks/releases)..._

## 7.x releases

- 7.11.0:
  - Add [random sorting](Sorting.md#Random%20sorting), with `sort by random`
- 7.10.0:
  - Right-click on any task date field in Reading and Query Results views to:
    - postpone Start, Scheduled and Due dates
    - advance Created, Cancelled and Done dates
- 7.9.0:
  - Add [hide and show](Layout.md) instructions `hide on completion` and `show on completion`.
  - Add one-click support for the [Border](Border%20Theme.md) theme.
- 7.8.0.
  - Add [On Completion](On%20Completion.md) facility, to tidy up your completed tasks.
- 7.7.0:
  - Queries can now use values in [Obsidian Properties](Obsidian%20Properties.md) (also known as YAML or frontmatter) for filtering, sorting and grouping.
- 7.6.0:
  - New setting to [recognise extra date format](Use%20Filename%20as%20Default%20Date.md#Additional%20date%20format) in file name as default date.
  - Add page [Request a Feature](Request%20a%20Feature.md).
- 7.5.0:
  - Add page [Missing tasks in callouts with some Obsidian 1.6.x versions](Missing%20tasks%20in%20callouts%20with%20some%20Obsidian%201.6.x%20versions.md).
  - [Auto-suggest](Auto-Suggest.md#How%20do%20I%20see%20fewer%20or%20more%20suggestions?) now defaults to at most 20 suggestions in new vaults. This is useful when adding dependencies.
- 7.4.0:
  - [Auto-suggest](Auto-Suggest.md#Details) now supports [task dependencies](Task%20Dependencies.md#Option%202%20Use%20the%20Auto-Suggest%20feature).
- 7.3.0:
  - Add 'Remove date' option to the [postpone](Postponing.md) right-click menu in search results.
- 7.2.0:
  - Much improved layout of the [Create or edit Task](Create%20or%20edit%20Task.md) modal, on mobile devices.
  - Add [[Tasks Api#`executeToggleTaskDoneCommand (line string, path string) => string;`|executeToggleTaskDoneCommand()]] to the Tasks API.
  - Add [Auto-Suggest Integration](Tasks%20Api.md#Auto-Suggest%20Integration), to enable other plugins to use Tasks' [Auto-Suggest](Auto-Suggest.md) facility.
- 7.1.0:
  - Much improved layout of the [Create or edit Task](Create%20or%20edit%20Task.md) modal, on desktop machines.
  - Add access keys for Created, Done and Cancelled dates in [Create or edit Task](Create%20or%20edit%20Task.md).
- 7.0.0:
  - Major improvements to [Combining Filters](Combining%20Filters.md) with Boolean combinations. See [the appendix](Combining%20Filters.md#Appendix%20Changes%20to%20Boolean%20filters%20in%20Tasks%207.0.0) for details.
  - Add documentation page (now in [Useful Links](Useful%20Links.md)), with links to write-ups,  talks and sample vaults from users.

## 6.x releases

- 6.1.0:
  - Add support for [task dependencies](task%20dependencies.md):
    - First, [use 'Create or edit Task'](Create%20or%20edit%20Task.md#Dependencies) to define the order in which you want to work on a set of tasks, using two new task emojis: 🆔  and ⛔.
    - Then adjust your searches, perhaps to see tasks that are [blocking others](Filters.md#Blocking%20Tasks), or hide ones that are [blocked](Filters.md#Blocked%20Tasks) and cannot yet be done.
  - `query.allTasks` is now available in custom searches: see [query search properties](Query%20Properties.md#Values%20for%20Query%20Search%20Properties).
  - The [Create or edit Task](Create%20or%20edit%20Task.md) modal now fully supports editing of statuses, updating done and cancelled dates, and creating new recurrences. See the [section on editing statuses](Create%20or%20edit%20Task.md#Status) for details and tips.
  - Add HTML samples in [full](Styling.md#Sample%20HTML%20Full%20mode) and [short](Styling.md#Sample%20HTML%20Short%20mode) modes to demonstrate custom styling.
- 6.0.0:
  - Add [custom sorting](Custom%20Sorting.md).
  - Document the [default sort order](Sorting.md#Default%20sort%20order).
  - **Warning**: This release contains some **bug-fixes** to **sorting** and to treatment of **invalid dates**.
    - The changes are detailed in [breaking changes](Breaking%20Changes.md#Tasks%206.0.0%20(19%20January%202024)), even though they are all improvements to the previous behaviour.
    - You may need to update any CSS snippets for the Edit or Postpone buttons: see [How to style buttons](How%20to%20style%20buttons.md).

## 5.x releases

- 5.6.0:
  - The [postpone](Postponing.md) menu now offers `today` and `tomorrow`.
- 5.5.0:
  - The [Create or edit Task](Create%20or%20edit%20Task.md) modal can now edit Created, Done and Cancelled dates
  - Add support for [cancelled dates](Dates.md#Cancelled%20date).
- 5.4.0:
  - Add ['full mode'](Layout.md#Full%20Mode) to turn off `short mode`.
  - Add any ['group by'](Grouping.md) and ['sort by'](Sorting.md) instructions to [explain](Explaining%20Queries.md) output.
  - Recurrence now works well [when DONE is not followed by TODO or IN_PROGRESS](Recurring%20Tasks%20and%20Custom%20Statuses.md#When%20DONE%20is%20not%20followed%20by%20TODO%20or%20IN_PROGRESS).
- 5.3.0:
  - Add [postpone button](Postponing.md) to Tasks query results.
  - Add ['change task status' menu](Toggling%20and%20Editing%20Statuses.md#'Change%20task%20status'%20context%20menu) to Reading mode and Tasks query results.
  - Add documentation section about [editing tasks](About%20Editing.md).
  - Add documentation page about [toggling and editing statuses](toggling%20and%20editing%20statuses.md).
- 5.2.0:
  - Most query instructions can now include [capital letters](About%20Queries.md#Capitals%20in%20Query%20Instructions%20-%20Case%20Insensitivity).
- 5.1.0:
  - Add 'Review and check your Statuses' facility: see [check your statuses](Check%20your%20Statuses.md).
  - Enable [custom filters](Custom%20Filters.md) and [custom grouping](Custom%20Grouping.md) to use [query properties](Query%20Properties.md) directly - no placeholders required.
- 5.0.0:
  - Add [line continuations](Line%20Continuations.md).
    - **Warning**: This is a [potentially breaking change](Line%20Continuations.md#Appendix%20Updating%20pre-5.0.0%20searches%20with%20trailing%20backslashes) if you search for backslash (`\`) characters.
  - Document [inline comments](Comments.md#Inline%20comments)
  - Document [recurring tasks and custom statuses](Recurring%20Tasks%20and%20Custom%20Statuses.md)
  - Add new Help pages [Known Limitations](Known%20Limitations.md) and [Breaking Changes](Breaking%20Changes.md).

## 4.x releases

- 4.9.0:
  - Add [task properties](Task%20Properties.md) `task.priorityNameGroupText` and `task.status.typeGroupText`, for example:
    - `group by function task.priorityNameGroupText + ': ' + task.status.typeGroupText`
  - Add [task date properties](Task%20Properties.md#Values%20in%20TasksDate%20Properties) for categorising dates, for example:
    - `group by function task.due.category.groupText`
  - Add [task date properties](Task%20Properties.md#Values%20in%20TasksDate%20Properties) for grouping dates by [time from now](https://momentjs.com/docs/#/displaying/fromnow/), for example:
    - `group by function task.due.fromNow.groupText`
- 4.8.0:
  - Add [query file properties](Query%20Properties.md#Values%20for%20Query%20File%20Properties) `query.file.pathWithoutExtension` and `query.file.filenameWithoutExtension`
  - Add [task file properties](Task%20Properties.md#Values%20for%20File%20Properties) `task.file.pathWithoutExtension` and `task.file.filenameWithoutExtension`
- 4.7.0:
  - Use [Query Properties](Query%20Properties.md) and [Placeholders](Placeholders.md) to filter and group with the query's file path, root, folder and name.
- 4.6.0:
  - Add `on or before` and `on or after` to [date search options](Filters.md#Date%20search%20options)
  - Add `in or before` and `in or after` to [date range search options](Filters.md#Date%20range%20options)
- 4.5.0:
  - Support task in list items starting with [[Getting Started#Finding tasks in your vault|`+` signs]]
- 4.4.0:
  - Support [variables, if statements, and functions](Expressions.md#More%20complex%20expressions) in custom filters and groups
- 4.3.0:
  - Bug fixes, usability improvements and `explain` support for [regular expression](Regular%20Expressions.md) searches
- 4.2.0:
  - Add [custom filtering](Custom%20Filters.md)
- 4.1.0:
  - Add [hide and show tags](Layout.md)
- 4.0.0:
  - Add [custom grouping](Custom%20Grouping.md), using [task properties](Task%20Properties.md) to create [expressions](expressions.md) - the start of a whole new [scripting](About%20Scripting.md) world in Tasks!

## 3.x releases

- 3.9.0:
  - Add [lowest and highest](Priority.md#Priorities%20and%20Order) priorities
- 3.8.0:
  - Add [limiting tasks per group](Limiting.md#Limit%20number%20of%20tasks%20in%20each%20group)
  - Add option to control the [order of new recurring tasks](Recurring%20Tasks.md#Order%20of%20the%20new%20task)
- 3.7.0:
  - Add [reverse sorting of groups](Grouping.md#Reversing%20groups)
- 3.6.0:
  - Add [group by urgency](Grouping.md#Urgency)
  - Add [sort by recurring](Sorting.md#Recurrence)
- 3.5.0:
  - New [Global Query](Global%20Query.md) facility.
- 3.4.0:
  - Clicking on a [Backlink](Backlinks.md) jumps to the exact task line.
  - Tasks now requires at least Obsidian 1.1.1.
- 3.3.0:
  - Multiple [Task Format](About%20Task%20Formats.md) support - starting with [Dataview Format](Dataview%20Format.md).
