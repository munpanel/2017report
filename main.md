\version{1.0.0}
\overalltitle{2017 MUNPANEL 年度报告}
\title{2017 MUNPANEL Yearly Report}
\compiledate{29/10/2017}

\license{Released under CC BY-NC-ND 4.0}
\printtitlepage{2016.11.21 - 2017.7.31}

# LICENSE

This report is released under Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License (CC BY-NC-ND 4.0).

##### Under the license, you are free to

* **Share** — copy and redistribute the material in any medium or format.

##### However, you must follow the following terms:

* **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
* **NonCommercial** — You may not use the material for commercial purposes.
* **NoDerivatives** — If you remix, transform, or build upon the material, you may not distribute the modified material.

##### Notes
This is a human-readable summary of (and not a substitute for) the license. Please read the full license at \url{https://creativecommons.org/licenses/by-nc-nd/4.0/legalcode}.

\pagebreak
\printtoc{Contents}
\pagebreak

# 导言
自从 2016 年 11 月 21 日上线以来，MUNPANEL 已伴随各位开过了 BJMUNC 2017、BJMUNSS 2017 与 ROMUNC 2017。我们很荣幸服务了超过 170 个注册社团、覆盖全国 34 个省的 2000 余名用户的二十余万次访问。

自始至终，MUNPANEL 的侧重点并非会议报名，也非学术文档作业等会议功能，而是构造一个将每一个模联人联系在一起的平台。设想一个未来，使用手中的一个账号，您可以自主创建一场新的会议，邀请其他组委成员共同管理；使用手中的一个账号，您可以以代表、志愿者抑或是观察员的身份，加入任何一场会议，甚至是基于参会历史得到匹配您的水平的会议推荐；使用一个账号，您可以管理及参与社团的内部事宜，无论是招新、校内培训还是组织参会；使用一个账号，您可以查看您一路走来的足迹，与志同道合的人共同分享成功的喜悦。而这一切，并非遥不可及的梦想。

正如我们在 11 月 21 日发布通告中所提及的“将原本分散的模块进行整合，以统一面板的形式将会议升高到一个全新的维度”，在研发的过程中，我们始终未忘“整合”的理念——不仅仅整合一场会议从开始到结尾的报名、缴费、作业提交、文件下载、智能分配搭档室友、席位分配、线上商城购物等等，也不仅仅是将模联软件系统整合——用同一套账户系统整合、联动模联中用到的软件，更是将中国中学生模拟联合国活动整合。而正是构建平台并使功能通用化的的这一思路，使得开发的过程无比得艰难。我们为过去一年内平台曾出现过的种种问题感到抱歉，更感谢一路走来陪伴我们、理解我们、支持我们的各位模联人。

作为一个以人为核心的平台，我们深知会议、社团的重要性，但更不忘我们 B2C 的通用平台服务理念。我们也很欣慰地看到像 MUNPASS 在内的一些小型会议报名系统的出现，也很感激冯凯佳先生对开源社区做的努力，更感谢 Console iT、MUNCS 等团队在模拟联合国会议主持软件方面所做的努力。正是这些人的努力，使得模拟联合国数字化离我们更近一步。

在技术层面，我们深知开源社区的重要性，更重视每一位有志向走上开发道路的开发者，无论是否在模拟联合国领域。在已经开源 MUNPANEL 代表牌生成中的部分代码后，在未来我们还将开源更多在开发 MUNPANEL 过程中研发的底层基础架构、分析算法、以及面向开发者的工具。

在未来的一段时间内，我们将继续整合化平台研发，在自主创建、配置、管理会议与社团功能完善之后，以全新的面貌与更佳的用户体验与大家见面。在那之前，我们将不与任何会议或社团合作。若您关于 MUNPANEL 平台有任何期望或建议，欢迎访问 \url{https://gdgdocs.org/forms/d/e/1FAIpQLSd4H-KOIAHIvOMxAKYeOzTMZCHbtaSR4hxAJRZTNUTvyrGLig/viewform} ，您的反馈对我们无比重要。如果您的社团或会议希望在第一时间体验整合平台带来的便利，欢迎访问 \url{https://gdgdocs.org/forms/d/e/1FAIpQLSfDYeuLAdw1JvVTt0Agpx-H9aQgq12-IYJEERANdKqFZbdrPA/viewform} 加入 MUNPANEL Trusted Teser 计划，我们将在内测阶段邀请您体验，也更期待您的反馈。如您希望为全新 MUNPANEL 平台贡献一份力，也欢迎您申请加入 MUNPANEL 团队（不仅限于软件开发），详情请访问 \url{https://goo.gl/forms/eX5WF8oNRiMnHZ5m2}（需科学地访问并登陆 Google 账号）。

希望这份报告可以带您回顾 MUNPANEL 过去一年的发展，也期待在不久的将来再次和您见面！\nl

Adam Yi\nl
Founder \& CTO of MUNPANEL

\pagebreak

# Introduction
Since its release on November 21, 2016, MUNPANEL has accompanied you participating in BJMUNC 2017, BJMUNSS 2017 \& ROMUNC 2017. We are proud to have served more than 170 registered clubs, and 200,000+ visits from 2,000+ users from all 34 provinces in China.

Since the very beginning, MUNPANEL's focus is never on conference registration; nor is it on functions like documents and assignments, but on creating a platform that links every MUNer together. Imagine a future, when you can use a single account to self-create a conference and invite other co-organizers. Imagine a future, when you can use a single account to participate in any conference as either a delegate, volunteer or observer, and even get conference recommendation that matches your MUN skills based on your participation history. Imagine a future, when you can use a single account to administrate and participate in internal affairs of your club, no matter if you are recruiting, training, or organizing members to sign up for conferences. Imagine a future, when you can use a single account to view your footsteps on the path of Model UN and share your success with like-minded fellows. That future is not a dream.

As mentioned in our release announcement on Nov. 21, "to integrate the separate modules together, and push conferences to a brand new dimension in a unfied form", we never forgot the idea of "integration" in our development process. We are not only integrating everything needed from the beginning to the very end of a conference - registration, paying fee, handing in assignments, downloading documents, smart roommate and partner pairing, nation assigning, online store, etc. Nor are we only integrating all systems and software used in Model UN with a unfied account system. More importantly, we are integrating Model UN as a whole. It is the very idea of building a general and integrated platform, that makes our development much more difficult than usual. We apologize for any problems you might have run into during the past year, and are grateful for you, MUNers who are always understanding us and supporting us.

Building a platform for MUNers, we understand the importance of conferences and clubs, but we also remember our B2C model. We are grateful to see the emergence of some small-scale conference registration service like MUNPASS, and thank for the efforts of Mr. Kaijia for his contributions to the open-source community. We also appreciate the efforts of teams including Console iT and MUNCS to build awesome conference moderating software. It is their efforts that make us closer to the ultimate goal of Model UN digitalization.

In the technological facet, we understand and significance of open-source community, and value every developer, no matter in the field of Model UN or not. After open-sourcing part of the code in generating badge images for conferences, we will continue to open-source even more, especially in some network/server infrastructure-level software and developer-facing tools we developed while building MUNPANEL.

In the next period of time, we will continue integrating the platform, and will release a brand new version after finalizing the functions related to the self-creation and self-configuration of new conferences on the platform. Until then, we won't cooperate with other conferences or clubs so that we can focus on improving our user expierience. If you have any expectations or suggestions of MUNPANEL, please visit \url{https://gdgdocs.org/forms/d/e/1FAIpQLSd4H-KOIAHIvOMxAKYeOzTMZCHbtaSR4hxAJRZTNUTvyrGLig/viewform}. Your feedback is extremely important for us. If you want to enjoy the convenience brought by the new MUNPANEL at the first time, please opt in the MUNPANEL Trusted Tester program at \url{https://gdgdocs.org/forms/d/e/1FAIpQLSfDYeuLAdw1JvVTt0Agpx-H9aQgq12-IYJEERANdKqFZbdrPA/viewform}. We will invite you for future alpha tests, and your ideas could potentially determine the future path of MUNPANEL. If you wish to contribute your skills to the new MUNPANEL, you are more than welcomed to apply to join the MUNPANEL team (not limited to software engineering), please visit \url{https://goo.gl/forms/eX5WF8oNRiMnHZ5m2} for details (requires to log in with a Google account, and needs special network conditions if you are in Mainland China).

We hope that this report can serve as a retrospect of the development of MUNPANEL in the past year, and hope to see you again soon!\nl

Adam Yi\nl
Founder \& CTO of MUNPANEL

\pagebreak

# 重要时间节点

| 时间 | 事件 |
|:--------------:|:---------------------------------------------:|
| 2016年1月 | 想法诞生与初步界面设计 |
| 2016年11月14日 | 开始开发 |
| 2016年11月21日 | 推出第一个生产版本，用于BJMUNC 2017 |
| 2016年11月25日 | 线上支付功能进行小规模测试 |
| 2016年12月4日 | 后台用户、委员会、学校管理功能推出 |
| 2016年12月5日 | BJMUNC 2017 ECOSOC 组委操作失误数据丢失事件 |
| 2016年12月6日 | 权限系统初步完成 |
| 2016年12月15日 | BJMUNC 2017 缴费开始 |
| 2016年12月24日 | 初版作业功能上线 |
| 2016年12月26日 | BJMUNC 2017 UNSC 学术测试启动 |
| 2016年12月27日 | 开始支持非BJMUN成员校 |
| 2017年1月8日 | 2016年12月开发月报公开 |
| 2017年1月14日 | 初版线上商城完成 |
| 2017年1月16日 | 初版文件系统上线 |
| 2017年1月17日 | MUNLink 短链服务上线 |
| 2017年1月19日 | 代表牌自动导出功能实现 |
| 2017年1月23日 | 搭档、室友配对功能上线 |
| 2017年1月28日 | 初版席位分配功能上线 |
| 2017年2月8日 | 初版线上商城上线 |
| 2017年2月10日 | BJMUNC 2017 纪念品预定开启 |
| 2017年2月13日 | MUNPANEL 代表牌扫描、订单发货 iOS App初版发布 |
| 2017年2月26日 | 底层数据结构转变 - 初步多会议平台化 |
| 2017年2月27日 | 下线升级 |
| 2017年3月3日 | 短信通知上线 |
| 2017年3月8日 | 身份系统实现 |
| 2017年3月10日 | 支持国际手机号认证 |
| 2017年3月13日 | 新版可自定义报名与作业表格上线 |
| 2017年3月18日 | 重新上线，ROMUNC 2017 报名启动 |
| 2017年3月24日 | 主席团招募系统上线 |
| 2017年3月27日 | BJMUNSS 2017 主席团招募开启 |
| 2017年4月2日 | 初版面试功能上线 |
| 2017年4月6日 | 后台笔记功能上线 |
| 2017年5月7日 | BJMUNSS 2017 会务团队招募开启 |
| 2017年5月9日 | 新版席位分配、选择系统上线 |
| 2017年5月24日 | BJMUNSS 2017 代表报名开启 |
| 2017年6月2日 | 新版学校社团功能内部测试 |
| 2017年6月5日 | 新版社团管理功能与MUNPANEL Portal正式发布 |
| 2017年6月19日 | 新版搭档室友匹配系统内部测试 |
| 2017年7月15日 | 新版搭档室友匹配系统正式发布 |
| 2017年7月31日 | 开始筹备新版MUNPANEL平台 |

# Timeline

| Time | Event |
|:------------:|:--------------------------------------------------------------------------------------------------:|
| 2016 Jan. | Born of idea, first design of UI |
| 2016 Nov. 14 | First line of code |
| 2016 Nov. 21 | First production version for BJMUNC 2017 |
| 2016 Nov. 25 | Online purchasing alpha test |
| 2016 Dec. 4 | User, committee, school management functions rolled out |
| 2016 Dec. 5 | BJMUNC 2017 ECOSOC data loss incident due to errors by conference organizing team |
| 2016 Dec. 6 | First version of permission system rolled out |
| 2016 Dec. 15 | BJMUNC 2017 conference fees collecting started |
| 2016 Dec. 24 | First version of assignment & test function rolled out |
| 2016 Dec. 26 | BJMUNC 2017 UNSC Academic Test started |
| 2016 Dec. 27 | Started to support non-member schools of BJMUN |
| 2017 Jan. 8 | Release of December 2016 Dev Report |
| 2017 Jan. 14 | First version of online store completed |
| 2017 Jan. 16 | First version of Document function |
| 2017 Jan. 17 | MUNLink URL service rolled out |
| 2017 Jan. 19 | Automatic badge image export function implemented |
| 2017 Jan. 23 | Smart partner & roommate pairing function rolled out |
| 2017 Jan. 28 | First version of nation assigning function rolled out |
| 2017 Feb. 8 | Online store rolled out |
| 2017 Feb. 10 | BJMUNC 2017 souvenir reserving started |
| 2017 Feb. 13 | Aztec code on exported badge scanning & orders shipping - iOS App rolled out |
| 2017 Feb. 26 | Major data structure refactor - first step to turn to a platform to support multiple conferences |
| 2017 Feb. 27 | Shutdown for upgrades |
| 2017 Mar. 3 | SMS notification implemented |
| 2017 Mar. 8 | Identity system (sub-account system) implemented |
| 2017 Mar. 10 | International TEL supported |
| 2017 Mar. 13 | New version of customizable form function rolled out |
| 2017 Mar. 18 | System online, ROMUNC 2017 registration started |
| 2017 Mar. 24 | Academic team application system rolled out |
| 2017 Mar. 27 | BJMUNSS 2017 academic team application started |
| 2017 Apr. 2 | First version of interview system rolled out |
| 2017 Apr. 6 | Delegate notes system rolled out for conference organizers/chairs |
| 2017 May. 7 | BJMUNSS 2017 Conference affairs team application started |
| 2017 May. 9 | New version of role allocation system rolled out (allow delegates to choose from multiple options) |
| 2017 May. 24 | BJMUNSS 2017 delegate registration started |
| 2017 Jun. 2 | New version of school club management alpha test |
| 2017 Jun. 5 | New version of school club management and MUNPANEL Portal announced |
| 2017 Jun. 19 | New intelligent partner & roommate pairing system alpha test |
| 2017 Jul. 15 | New intelligent partner & roommate pairing system rolled out |
| 2017 Jul. 31 | Began to plan for the new MUNPANEL Platform |

# 统计 Statistics^[此统计时间为2016年11月25日至2017年7月31日 From Nov. 25, 2016 to Jul. 31, 2017]

## 概览 Overview

在过去的一年中，我们共有 172 个注册社团、2117 个注册用户，其中有 2128 个会议身份（不包括BJMUNC 2017，70 个组委／会务团队成员、155个学术团队成员、202个学校领队、1464个代表、178个志愿者、59个面试官）。47项作业共有 1637 次答案提交，31 个学术文件共有 3196 次查看或下载。

In the past year, we have served 172 registered school clubs, 2117 registered users, among which there are 2128 identities in different conferences (not including BJMUNC 2017: 70 organizing team or conference affairs team members, 155 academic team members, 202 school club leaders, 1464 delegates, 178 volunteers, 59 interviewers). There are 1637 hand-ins for 47 assignments, and 31 academic documents have been downloaded or viewed for 3196 times.

新版线上商城上线后（不包括 BJMUNC 2017 订单），共有 962 个订单，其中666个交易成功，共计流水 491274.86 人民币，其中 272963.78 元为系统内直接通过微信支付／支付宝付款，218311.08 元为其他渠道支付。

After rolling out the new version of Online Store (not including orders from BJMUNC 2017), there are 962 orders, among which 666 orders are complete. The total cash flow is 491274.86 CNY, among which 272963.78 CNY is paid directly on the system through WeChat Payment and Alipay and processed automatically by the system, and 218311.08 CNY is paid by other methods.

系统内所有会议共创建了 35 个委员会，868 个席位，30 个代表分组，30 个席位分组。

Conference organizers and academic team members have created 35 committees, 868 seats (nations), 30 delegation groups, and 30 seat groups.

## 用户分析 User Analytics

截止至 7 月 31 日，共有 235,791 次访问，日活跃用户峰值523人（2017 年 6 月 25 日）。

As of July 31, 2017, there have been 235, 791 page views. Max daily active users 523 is achieved on June 25, 2017.

\begin{figure}[H]
\includegraphics[width=\textwidth]{./audience_overview.png}
\end{figure}
\begin{figure}[H]
\includegraphics[width=\textwidth]{./active_users.png}
\end{figure}

其中，这些访问来自五大洲 43 个国家。在中国内部，这些访问以北京为主，来自全部 34 个省中 215 个城市。

Among them, these visits come from 43 nations from all 5 continents. In China, these visits mostly come from Beijing, but also 214 other cities from all 34 provinces.

\begin{figure}[H]
\includegraphics[width=\textwidth]{./geo_global.png}
\end{figure}
\begin{figure}[H]
\includegraphics[width=\textwidth]{./geo_china.png}
\end{figure}

用户浏览器以 Safari、Chrome为主。

Most of our users use Safari or Chrome.

\begin{figure}[H]
\includegraphics[width=\textwidth]{./tech_browser.png}
\end{figure}

移动端访问占比 55.77\%；桌面端访问占比 31.89\%；平板电脑访问占比 12.34\%，其中操作系统占比如下图所示。

55.77\% visits are made by mobiles; 31.89\% by desktops; 12.34\% by tablets. Among them, distribution of operating system is shown below:

\begin{figure}[H]
\includegraphics[width=\textwidth]{./tech_os.png}
\end{figure}

在移动端中，54.82\% 的访问来自 iOS；44.58\% 的访问来自 Android；0.60\% 的访问来自 Windows Phone。其中共有 375 个不同的手机机型（不完全统计）。

In mobiles, 54.82\% visits come from iOS; 44.58\% from Android; 0.60\% from Windows Phone. There are more than 375 different mobile models:

\begin{figure}[H]
\includegraphics[width=\textwidth]{./tech_phone.png}
\end{figure}
