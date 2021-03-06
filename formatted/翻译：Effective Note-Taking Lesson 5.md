- **[Metadata](<Metadata.md>):**
    - **[Tags](<Tags.md>):** #[翻译](<翻译.md>) #[未发布](<未发布.md>)
    - **[Source](<Source.md>):** #[Andy Henson Series](<Andy Henson Series.md>)
    - 初翻: [wangxh1000](<wangxh1000.md>)
    - 校对: 
- 原文：[Effective Note-Taking Lesson 5](<Effective Note-Taking Lesson 5.md>)
- 
- 嗨，
- 初看起来，Roam 似乎并不能成为一个好的任务管理器，今天我们会介绍几个 Roam 基础模块，看看能否将它们组合成符合要求的管理器。
- 最基础的是 TODO block。你可以在任何时间任何位置，用 `/TODO` 命令新建或将当前 block 转为 TODO block。TODO block 在最开始的地方显示一个复选框，这样你就能在任务完成后进行勾选，示意任务完成。同样的，你也可以用 `Command-Enter` 快捷键创建 TODO block。如果连续按键，TODO block 会在 TODO、DONE 和退出 TODO block 三种状态间进行切换。
- 你可能会说，嗯，很好。但是，如果我能到处创建任务，我怎么能保证再次找到它们呢？
- 如果仔细观察 TODO 的语法，你会发现 TODO 关键字是被包括在代表页面引用的双方括号里的。对应任务结束的 DONE 关键字也是如此。这意味着，我们能用 TODO 关键字搜索任务，我们甚至可以添加 TODO 页面到 Shortcuts 列表中，这样，打开该页面就能在下方的 `Linked References` 列表中看到所有任务。
- 如果你在 TODO block 上同时添加了标签信息，你就能在 `Linked References` 列表过滤器中利用标签进行过滤，进一步缩小列表内容。
- ## Getting Things Done (GTD)
- Daily Note 是个添加任务列表的好地方。新建一个用于归置待办事项的 block，把任务都集中放置在该 block 下，出现新任务就直接加到列表最后。
- ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxwang-learning-space%2FlOcUoNrKaE.png?alt=media&token=abe7b0ac-665a-4339-b765-fb283f75cc59)
- ### 看板
- 更棒的是 Roam 还支持创建看板，这样你就能直观地查看任务进度。看板是表现各阶段工作的轻量级视觉方式。它的列代表了不同阶段 —— 例如，一个简单的待办事项系统可能包含 To-Do、Doing、Done 三个阶段。每列中的事项代表它们处于这个阶段。
- 在 Roam 中准备待办事项列表，像是这样：
- ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxwang-learning-space%2FarK3fZvnL_.png?alt=media&token=e7952946-2bc9-44e8-bf49-725f0f51685c)
- 在这个名为 Daily TODOs 的分层 block 下，第一层是列标题，你可以用页面引用做标题，这样如果你想跳到别的地方，就会很方便。然后在第一层列标题下列出所有待办事项的内容。
- 然后，在 Daily TODOs block 上，输入 `/Kanban Board` 命令，Roam 会在下方插入一个与列表内容对应的看板图形表示。它是可交互的，可以把待办事项从一列拖到另外一列。
- ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fxwang-learning-space%2FPjZsNiqKkR.png?alt=media&token=fb5c5ff0-d9f5-40c9-b51a-1945c2b0ce25)
- 要注意的是，拖动任务到 DONE 列，Roam 不会自动标识任务为结束，你必须人工勾选复选框标识任务完成。
- 显然，看板并不是只能用于待办事项管理。你可以用它跟踪与流程阶段相关的任何事项。因为 Roam 的典型用途是写作，所以未来我可能会做文章构思内容流程方面的介绍。
- ### 番茄定时器(Pomodoro Timers)
- 在我们讨论 getting things done(GTD) 的时候，Roam 又新加了一个番茄定时器的功能。番茄工作法是个工作25分钟休息5分钟的简单的工作方法。可以用 `/Pomodoro Timer` 命令在 Roam 的任何 block 上添加定时器。定时器显示为按钮的样子，点击按钮启动计时。25分钟计时结束后，你会听到"叮"的一声，然后转入5分钟休息时间计时。全部结束后，番茄图标右侧会显示一个绿色复选框代表已经完成一个番茄时间。
- ### 输入将来的某个日期
- 大多时候，我们总有些想在未来某天完成的事情。在 Roam 中，很简单，你只要在 TODO block 中用 `/Date Picker` 命令插入日期选择器，然后选择日期即可。等到这天，你就会在 Daily Note 下方的 `Linked References` 列表中看到这条待办事项。
- ## 更多高级的工作流程
- 希望读到这里，已经给你建立了一些关于如何组合之前所学的简单模块来做任务管理的基本概念。对于刚开始使用 Roam 的人来说，始终存在一种想一下把所有都搞"完美"的诱惑与冲动。不要这样，我建议边学边实践，实践越多你就越理解 Roam 的工作方式以及如何将 Roam 与最佳个人实践有效结合，让属于你的 Roam 系统自然成长出现吧。在这个过程中，你会看到什么有效，然后在此基础上往前继续发展。Roam 一直都能让你轻松找到并做出改变。
- 在明天的课程中，我们将介绍 Roam 的 **Query** 语法，它是创建更复杂的任务管理流程的关键之一。可以用它查找过期的待办事项，而且如果你想，结合 **Query** 和标签就能建立一个完整的类 GTD 系统。
- 和往常一样，如果你有任何反馈或者迫切想得到回答的问题，欢迎回复这封邮件。我会尽最大努力回复，并将其纳入修订版和今后的课程中。
- 明天见
- Andy

# Backlinks
## [August 2nd, 2020](<August 2nd, 2020.md>)
- 完成初翻 [翻译：Effective Note-Taking Lesson 5](<翻译：Effective Note-Taking Lesson 5.md>)

