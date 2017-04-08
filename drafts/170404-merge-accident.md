# 一个由暴力 Merge 引发的被异地与被变性 惨案


## 涉案人物

- 暴力嫌疑人: xpgeng, 男, 一个有 local 女朋友的直男
- 盲人狙击手: zoomquiet, 一个被叫做作大妈的男人
- 懵逼被害人: Zhangshyingrunwithcc(怼圈最长 ID 持有人), 女, 一个有异地男朋友的女子
- 笑哭的围观群众: zoe 等一甘人


### WANTED!!!


## 案发起因

### xpgeng 做了什么?

作为怼圈第一次提交当日小结, 在爱心妈咪 zoe 的带领下, 怼友稀稀拉拉的...开始提交自己的总结. 第一天总结, 怎能上来就缺席?

写, 写好了, push! 在 push 之前他还想: 大家第一天交总结不怎么积极嘛, 估计也不用 pull 就可以推上去了, 省时省力, 好机智.

滴滴滴! 提示 repo 滞后了... 看来这是有人已经动过 master repo 了呐, 哎, 太年轻. Pull 之! 

哐哐哐! Conflict?! 就写个总结也特么能有 conlict? 能有啥 conflict 啊? 遥想以前在隔壁仓库协作更新 wiki 的时候, 也遇到过这种情况, 基本上这种 conflict, 正常 commit 下, 直接 push 就好. 大家的文字肯定是不会丢的. 遂, commit, push, Done! 检查一下, 不错. 

### zhangshiyingrunwithcc 做了什么?

一直认真积极的诗颖同学就在 xpgeng 还在写总结的时候, 咔咔咔完成了 push. 正在开心自己提交的时候, 浏览 repo 内其他怼友的小结是, 她发现文件名搞错了. 在 README 中, 要求的文件格式为

> du_s01e01_[github id].md

例如,大妈的作业文件名就应该是: du_s01e01_zoomquiet.md

然后**特(shi)别(er)实(bu)在(jian)**的诗颖同学的文件名是: du_s01e01_[zhangshiyingrunwithcc].md

纳尼? 改! 于是紧接着有了这样一次 [commit](https://github.com/DebugUself/du4proto/commit/4fe6f2a237f49ad7ee1b108d0f849105aa9eee82#commitcomment-21604885)

> Rename du_s01e01_[zhangshiyinrunwithcc].md to du_s01e01_zhangshiyinru…

## 案发经过

### 盲人狙击手 zoomquiet 登场

在诗颖童鞋的总结里有这样一条

> 对异地恋的疑虑，让我花费1小时疏导心情

热心大妈就来了...

>  ZoomQuiet: 
>
> @xpgeng 矜持....太过私人的不用特意公开的, 要知道, 这仓库,随时可以 fork 给你女友的...
>
> 可以用自己定义的专有名词来替代, 公开自怼的技巧就是通过抽象的模型来讨论.

不对, 大妈在诗颖的总结里 @xpgeng 这是什么鬼?

> xpgeng:
> 
> @ZoomQuiet 大妈, 你@我干啥? 这是 @zhangshiyinrunwithcc 同学的.
> 
> 我知道问题出在哪了, merge 没整好... 怪我!

尽管 xpgeng 第一时间意识到了问题, 可是血案已经发生---->

-> xpgeng 被异地  
-> 诗颖被变性...  

盲人狙击手既然已经开枪, 想必是收不回来了.

> ZoomQuiet 23 hours ago

> @xpgeng @zoejane @zhangshiyinrunwithcc 请允许俺笑4分钟的....  
> 太多事儿, 不在协同中怼到, 永远不知道什么行为会引发什么后果的,  
> 所以, 大家的行为想越来越有效率/规范/专业...  
> 多尝试/折腾/犯傻/...  
> 
> 嘦及时知道, 并改正,而且恨恨记住, 再有人嗯哼, 就怼!  

此枪案现场可见 [commit b17d36](https://github.com/DebugUself/du4proto/commit/b17d36d20c31671cea1609d1b89a62d54e6be172)

如果你以为这就完事了, 那就太小看盲人狙击手了... 他除了怼翻嫌疑人, 还来了甩狙, 又....补了被害人一枪!

> ZoomQuiet commented on 4fe6f2a
>
>@xpgeng 好心的修订了文件名,结果引发了一系列误解,
>问题源头的 @zhangshiyinrunwithcc 知道自己哪儿错了?
>
>     其实就是模板语言的不理解而已
>     什么是模板语言?
>     文件命名格式:
>
>     du_s01e01_[github id].md
>
> 例如,俺的作业文件名就应该是: du_s01e01_zoomquiet.md
>
> 以上两句是前后关联的, 以及前述文本格式就是...
> 
> 还有什么模板语言,都有什么通用约定?
> 
> 请试答...

苍天可见, 明明是诗颖自己 rename 的啊, 关 xpgeng 什么事? 一个嫌疑人怎么会有那么好心! 他没把别人的总结整丢就已经很不错了呐!

> xpgeng
>
> @ZoomQuiet 大妈, 我先声明, 文件名是她自己改的, 问题真的是在我.
>
> 应该是 pull 过程中出现 conflict, 然后我暴力 merge, 所以引起后续误会.
> 
> 大妈你还是 怼我 好了...

枪案现场见 [commit 4fe6f2](https://github.com/DebugUself/du4proto/commit/4fe6f2a237f49ad7ee1b108d0f849105aa9eee82#commitcomment-21605040)

直至第二天早上, 被害人还一脸懵逼的质问 xpgeng: 你 merge 和我修改文件名有啥关系?! 

xpgeng: 具体原因呢是: ........... BLABLA ....... 就是这么情况.



## 用图说话

+--------+
| master +-------------------+------------+------->--->---+--------+---------->
+--------+                   |            |       ×       v        +
                          push            |     push    pull       push
+--------+  modifying        |            |       ^       +        |
| xpgeng +--------------------------->------------+---->conflict!+-->merge!+
+--------+                   |            |             ???!       |       |
                             |            |                        |       |
+-----------------------+    |            |                commit  |       |
| zhangshiyingrunwithcc +----+-->rename+-++           +------------+-----+ |
+-----------------------+                v            |                  | |
                                    啥 是 模 版 ?      |   xpgeng's       | |
                                         |            |                  +<+
 +------------+                          |            +------------------+
 | zoomquiet  |                          |            |   shiying's      |
 +------------+--------------comment-----+---------------------+         | -
                                                      +------------------+
                                                               |
                                   xpgeng 被 异 地  <----+shiying's = xpgeng's
                                  shiying 被 变 性 <-----+shiying = xpgeng


## 总结陈词

虽然在嫌疑犯 xpgeng 的不懈努力下, 案件已经的得到解决, 被害人也已经从懵逼中清醒过来, 可是...

盲人狙击手还并没有放过被害人, 被害人成功出发了隐藏任务: 什么模板语言,都有什么通用约定?

作为怼圈最长 ID 持有人, shiying 是不会放过这次回怼的机会的. 她经过 [6轮搜索](https://github.com/zhangshiyinrunwithcc/Zoomquiet-TASK/blob/master/templating-language-protocol.md)，对本问题进行了回答. 

可是, 想怼大妈哪那么容易...

> 是也乎,(￣▽￣) 还是少挖一层哪...   
> 模板系统的动力来源是什么? 模式匹配哪 为什么要写成模式条目?   
> 
> 因为想一句话说明白一堆条件哪 可是, 在大家不明白, 没有经过类似训练时  
> 你的研究, 应该形成一个什么 可用 的成果输出? 有益怼友们?

@zhangshiyinrunwithcc @zhangshiyinrunwithcc @zhangshiyinrunwithcc 看到请回答!看到请回答!

## 嫌疑人的反思

虽然大家在之前已经有了 GitHub 的各种操作体验, 可多数还是属于单打独斗的折腾, 所以对于 Git 的使用也基本局限在很简单的一些命令. 那么未来怼圈内会逐步开始涉及协同作业, 简单的 `push` `commit` 显然已经不够用了. 未来我们面对的可就不是本次惨案所遇到的这么简单的情况. 那么, 在协同作业中, 我们都需要掌握哪些必要的处理技能呢? 除了自己学会更深入的 Git 操作, 我们是不是该有一些协同上的约定呢?

比如:

- Commit 信息如何书写?
- Conflict 如何 fix? 正确的处理流程是什么?
- 分支该怎么使用?
- 如何合并到 Master?
- 更高级的协作还有什么?

要不我们一起讨论讨论, 分享分享, 总结总结, 整理整理, 发布发布?

## References

- [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)
    - 这个 blog 列出来该如何书写一些 commit message, 其中设计各方面的一些约定, 算是抛个砖. 
- [Git - Branches in a Nutshell](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)
    - 关于分支的使用, Pro Git 已经说的比较详细了. 
- [Commit message 和 Change log 编写指南 - 阮一峰的网络日志](http://www.ruanyifeng.com/blog/2016/01/commit_message_change_log.html)
    - 阮老师的一个篇关于 commit 的博文, 其中关于 header type 那部分有些借鉴意义. 
- [How to resolve merge conflicts in Git? - Stack Overflow](http://stackoverflow.com/questions/161813/how-to-resolve-merge-conflicts-in-git)
    - 推了一波 git mergetool. 
- [使用 git rebase 避免無謂的 merge | ihower { blogging }](https://ihower.tw/blog/archives/3843)
    - 算是更高级的用法, 目的是减少一些不必要的 merge, 同时让 master 与分支的线图看起来更醒目. 各种各样的merge 流 我也是最近才开始了解到还能这么玩?..