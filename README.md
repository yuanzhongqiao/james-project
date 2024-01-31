Apache James Project  邮件系统开源
====================

<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><h1 tabindex="-1" dir="auto"><a id="user-content-apache-james-project" class="anchor" aria-hidden="true" tabindex="-1" href="#apache-james-project"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阿帕奇詹姆斯项目</font></font></h1>
<div id="user-content-preamble" dir="auto">
<div dir="auto">
<div dir="auto">
<p dir="auto"><span><a href="https://james.apache.org/mail.html" rel="nofollow"><img src="https://camo.githubusercontent.com/410bc42652447e669247f4b6d6cb4e327ae45dc5f9a6916a2fd3bd36c757303f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4a6f696e25323075732d4d61696c696e672532306c697374732d707572706c652e737667" alt="加入%20us 邮件%20lists 紫色" data-canonical-src="https://img.shields.io/badge/Join%20us-Mailing%20lists-purple.svg" style="max-width: 100%;"></a></span>
<a href="https://gitter.im/apache/james-project" rel="nofollow"><span><img src="https://camo.githubusercontent.com/a1e916418b53361d4eb3e1591e35c5e76a3413af7ad79044b23d5a754efc8e7d/68747470733a2f2f6261646765732e6769747465722e696d2f6170616368652f6a616d65732d70726f6a6563742e737667" alt="通过链接加入聊天：https://gitter.im/apache/james-project" data-canonical-src="https://badges.gitter.im/apache/james-project.svg" style="max-width: 100%;"></span></a>
<span><a href="https://ci-builds.apache.org/job/james/job/ApacheJames/" rel="nofollow"><img src="https://camo.githubusercontent.com/9158f357eec290d58e945991c2cc5f89703167b82f57a748fc4f2b55951bba4b/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f43492d4a656e6b696e732d626c75652e737667" alt="CI詹金斯蓝" data-canonical-src="https://img.shields.io/badge/CI-Jenkins-blue.svg" style="max-width: 100%;"></a></span>
<span><a href="https://james.apache.org/documentation.html" rel="nofollow"><img src="https://camo.githubusercontent.com/4d69457890e3fa43e6112f766aa3670bfbc75e447cffe91a392d47ec363e5a98/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f63756d656e746174696f6e2d677265656e2e737667" alt="文档绿色" data-canonical-src="https://img.shields.io/badge/Documentation-green.svg" style="max-width: 100%;"></a></span>
<span><a href="https://james.apache.org/download.cgi" rel="nofollow"><img src="https://camo.githubusercontent.com/c1421acae97835d41f59fa680e10e75f1fab2a21c733629c7ab834eabbff3268/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f776e6c6f6164732d332e382e302d79656c6c6f772e737667" alt="下载 3.8.0 黄色" data-canonical-src="https://img.shields.io/badge/Downloads-3.8.0-yellow.svg" style="max-width: 100%;"></a></span>
<span><a href="https://hub.docker.com/r/apache/james" rel="nofollow"><img src="https://camo.githubusercontent.com/a8b6e93f14bac546e1933800563a0bc96f47bdb916ae1cac16b57a94baf7426a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f496d616765732d646f636b65722d626c75652e737667" alt="图像 docker 蓝色" data-canonical-src="https://img.shields.io/badge/Images-docker-blue.svg" style="max-width: 100%;"></a></span>
<span><a href="https://www.apache.org/licenses/" rel="nofollow"><img src="https://camo.githubusercontent.com/45102e0e6db8530f9583267c79e3f94f6e7f80f14da33299854945a02a421f89/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d41706163686556322d6f72616e67652e737667" alt="许可证 ApacheV2 橙色" data-canonical-src="https://img.shields.io/badge/License-ApacheV2-orange.svg" style="max-width: 100%;"></a></span>
<span><a href="https://james.apache.org/index.html#posts" rel="nofollow"><img src="https://camo.githubusercontent.com/d7d359d86acb504e2ae41755ed0b9579234a1c034dfcd1de1d84a62973302a83/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6174657374732d6e6577732d7265642e737667" alt="最新消息红色" data-canonical-src="https://img.shields.io/badge/Latests-news-red.svg" style="max-width: 100%;"></a></span></p>
</div>
<div dir="auto">
<div dir="auto">
<a href="https://james.apache.org" rel="nofollow"><img src="/apache/james-project/raw/master/james-logo.png" alt="詹姆斯标志" style="max-width: 100%;"></a>
</div>
</div>
<div dir="auto">
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">James</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代表</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Java Apache Mail Enterprise Server！</font></font></strong></p>
</div>
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它具有基于一组丰富的</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现代</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">高效</font><font style="vertical-align: inherit;">组件的模块化架构，最终提供
</font><strong><font style="vertical-align: inherit;">在 JVM 上运行的完整、稳定、安全和可扩展的邮件</font></strong></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务器</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font><strong><font style="vertical-align: inherit;"></font></strong><font style="vertical-align: inherit;"></font></p>
</div>
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">借助提供的控制反转邮件平台，通过组装所需的组件来</font><font style="vertical-align: inherit;">创建您</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">自己的个人电子邮件处理解决方案，并使用</font></font></strong><font style="vertical-align: inherit;"></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">James Mailet Container</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进一步自定义过滤和路由规则。</font></font></p>
</div>
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持的协议有：IMAP、SMTP、</font></font><a href="https://jmap.io" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">JMAP</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、POP3 等等...</font></font></p>
</div>
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分布式</font></font><a href="https://james.staged.apache.org/james-distributed-app/3.8.0/index.html" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">服务器</font></font></strong></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">专注于提供基于现代技术（Cassandra、S3、OpenSearch 和 RabbitMQ）的易于操作的可扩展邮件服务器。</font></font></p>
</div>
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://james.apache.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请在我们的网站</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上阅读更多内容</font><font style="vertical-align: inherit;">。</font></font></p>
</div>
</div>
</div>
<div dir="auto">
<h2 id="user-content-how-to-contribute" tabindex="-1" dir="auto"><a id="user-content-how-to-contribute" class="anchor" aria-hidden="true" tabindex="-1" href="#how-to-contribute"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何贡献？</font></font></h2>
<div dir="auto">
<details>
<summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阅读更多...&ZeroWidthSpace;</font></font></summary>
<div dir="auto">
<div dir="auto">
<p dir="auto">James is a project that lives from the contributions of its community! Anyone can contribute!</p>
</div>
<div dir="auto">
<p dir="auto">Read <a href="https://james.apache.org/index.html#third" rel="nofollow">how to contribute</a>.</p>
</div>
<div dir="auto">
<p dir="auto">We more than welcome <strong>articles</strong> and <strong>blog posts</strong> about James. Contact us by <a href="https://james.apache.org/mail.html" rel="nofollow">email</a>
or on <a href="https://gitter.im/apache/james-project" rel="nofollow">Gitter</a> to share your experiences.</p>
</div>
<div dir="auto">
<p dir="auto"><strong>Documentation</strong> is an easy way to get started, and more than wanted! Check out the <a href="https://issues.apache.org/jira/issues/?jql=project%20%3D%20JAMES%20AND%20resolution%20%3D%20Unresolved%20AND%20labels%20%3D%20documentation%20ORDER%20BY%20priority%20DESC%2C%20updated%20DESC" rel="nofollow">~documentation</a> label on JIRA.</p>
</div>
<div dir="auto">
<p dir="auto">And to get started with <strong>code contributions</strong>, search out the
<a href="https://issues.apache.org/jira/issues/?jql=project%20%3D%20JAMES%20AND%20resolution%20%3D%20Unresolved%20AND%20labels%20%3D%20newbie%20ORDER%20BY%20priority%20DESC%2C%20updated%20DESC" rel="nofollow">~newbie</a>,
<a href="https://issues.apache.org/jira/issues/?jql=project%20%3D%20JAMES%20AND%20resolution%20%3D%20Unresolved%20AND%20labels%20%3D%20easyfix%20ORDER%20BY%20priority%20DESC%2C%20updated%20DESC" rel="nofollow">~easyfix</a>,
<a href="https://issues.apache.org/jira/issues/?jql=project%20%3D%20JAMES%20AND%20resolution%20%3D%20Unresolved%20AND%20labels%20%3D%20feature%20ORDER%20BY%20priority%20DESC%2C%20updated%20DESC" rel="nofollow">~feature</a> labels on JIRA.</p>
</div>
<div dir="auto">
<p dir="auto">There is many other ways one can help us: packaging, communication, etc …&ZeroWidthSpace;</p>
</div>
</div>
</details>
</div>
</div>
<div dir="auto">
<h2 id="user-content-how-to-try-james" tabindex="-1" dir="auto"><a id="user-content-how-to-try-james" class="anchor" aria-hidden="true" tabindex="-1" href="#how-to-try-james"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何尝试詹姆斯</font></font></h2>
<div dir="auto">
<details>
<summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阅读更多...&ZeroWidthSpace;</font></font></summary>
<div dir="auto">
<div dir="auto">
<p dir="auto">Requirements: <code>docker</code> installed.</p>
</div>
<div dir="auto">
<p dir="auto">Here you will try James server version 3.8.0 thanks to a docker image. This James image has a default configuration using JPA
(hsqldb) and Lucene. It also includes a default domain named james.local and three default users: <a href="mailto:user01@james.local">user01@james.local</a>,
<a href="mailto:user02@james.local">user02@james.local</a>, <a href="mailto:user03@james.local">user03@james.local</a>, with their default password being 1234.</p>
</div>
<div dir="auto">
<p dir="auto">Note: this James server will respond to IMAPS port 993 and SMTPS port 465.</p>
</div>
<div dir="auto">
<p dir="auto">Pull and run the James image with the following single command:</p>
</div>
<div dir="auto">
<div dir="auto">
<pre>    $ docker run -p "465:465" -p "993:993" apache/james:demo-3.8.0</pre>
</div>
</div>
<div dir="auto">
<p dir="auto">Then, connect this image with for instance, Thunderbird.
<a href="https://james.apache.org/howTo/imap-server.html" rel="nofollow">This tutorial</a> covers more in depth user and domain creation, as well as Thunderbird setup.</p>
</div>
<div dir="auto">
<p dir="auto">Instructions that do not imply <code>docker</code> are also available <a href="https://james.apache.org/server/install.html" rel="nofollow">here</a>.</p>
</div>
<div dir="auto">
<p dir="auto">Instructions for the distributed server can be found <a href="/apache/james-project/blob/master/server/apps/distributed-app/docs/modules/ROOT/pages/run/run-docker.adoc">here</a>.</p>
</div>
</div>
</details>
</div>
</div>
<div dir="auto">
<h2 id="user-content-how-to-check-the-compilation" tabindex="-1" dir="auto"><a id="user-content-how-to-check-the-compilation" class="anchor" aria-hidden="true" tabindex="-1" href="#how-to-check-the-compilation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何检查编译情况</font></font></h2>
<div dir="auto">
<details>
<summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阅读更多...&ZeroWidthSpace;</font></font></summary>
<div dir="auto">
<div dir="auto">
<p dir="auto">We require <a href="https://maven.apache.org" rel="nofollow">maven</a> version 3.6.1 minimum to build the project.</p>
</div>
<div dir="auto">
<p dir="auto">First, clone the repository locally:</p>
</div>
<div dir="auto">
<div dir="auto">
<pre>    $ git clone git@github.com:apache/james-project.git</pre>
</div>
</div>
<div dir="auto">
<p dir="auto">Then simply run <code>mvn clean install</code> within this directory to compile the project.</p>
</div>
<div dir="auto">
<p dir="auto">Useful options includes:</p>
</div>
<div dir="auto">
<ul dir="auto">
<li>
<p dir="auto"><code>-DskipTests</code> to skip the long to execute resource consuming test suite that requires a docker daemon.</p>
</li>
<li>
<p dir="auto"><code>-T 4</code> to parallelize the build on several CPUs.</p>
</li>
<li>
<p dir="auto"><code>-Dmaven.javadoc.skip=true</code> to skip the javadoc generation.</p>
</li>
</ul>
</div>
</div>
</details>
</div>
</div>
<div dir="auto">
<h2 id="user-content-how-to-run-james-in-docker" tabindex="-1" dir="auto"><a id="user-content-how-to-run-james-in-docker" class="anchor" aria-hidden="true" tabindex="-1" href="#how-to-run-james-in-docker"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何在 Docker 中运行 James</font></font></h2>
<div dir="auto">
<details>
<summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">阅读更多...&ZeroWidthSpace;</font></font></summary>
<div dir="auto">
<div dir="auto">
<p dir="auto">We maintain docker distribution for our <a href="https://github.com/google/guice">Guice</a> based applications:</p>
</div>
<div dir="auto">
<ul dir="auto">
<li>
<p dir="auto"><a href="https://github.com/apache/james-project/blob/master/server/apps/distributed-app/README.adoc">Guice + Cassandra + RabbitMQ + S3 + OpenSearch (distributed)</a></p>
</li>
<li>
<p dir="auto"><a href="https://github.com/apache/james-project/blob/master/server/apps/cassandra-app/README.adoc">Guice + Cassandra + OpenSearch</a></p>
</li>
<li>
<p dir="auto"><a href="https://github.com/apache/james-project/blob/master/server/apps/jpa-app/README.adoc">Guice + JPA + Lucene</a></p>
</li>
<li>
<p dir="auto"><a href="https://github.com/apache/james-project/blob/master/server/apps/memory-app/README.md">Guice + Memory (testing)</a></p>
</li>
</ul>
</div>
</div>
</details>
</div>
</div>
<div dir="auto">
<h2 id="user-content-using-the-cli" tabindex="-1" dir="auto"><a id="user-content-using-the-cli" class="anchor" aria-hidden="true" tabindex="-1" href="#using-the-cli"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 CLI</font></font></h2>
<div dir="auto">
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关详细信息，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="https://james.apache.org/server/manage-cli.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过命令行管理 James 。</font></font></a><font style="vertical-align: inherit;"></font></p>
</div>
</div>
</div>
<div dir="auto">
<h2 id="user-content-develop-on-james" tabindex="-1" dir="auto"><a id="user-content-develop-on-james" class="anchor" aria-hidden="true" tabindex="-1" href="#develop-on-james"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在詹姆斯身上发展</font></font></h2>
<div dir="auto">
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">James 至少需要 JDK 11 和 Maven 3.6.1 才能构建。</font><font style="vertical-align: inherit;">James 的某些部分是用 Scala 编写的，因此可能需要在 IDE 中启用 Scala 插件。</font></font></p>
</div>
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们维护</font></font><a href="/apache/james-project/blob/master/examples/README.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码示例</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来帮助您编写自己的扩展并连接您自己的服务器。</font></font></p>
</div>
<div dir="auto">
<p dir="auto"><a href="/apache/james-project/blob/master/docs/modules/development/pages/deployment-tests.adoc"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本页</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">详细介绍了如何运行部署测试。</font></font></p>
</div>
</div>
</div>
<div dir="auto">
<h2 id="user-content-know-more-about-james-design" tabindex="-1" dir="auto"><a id="user-content-know-more-about-james-design" class="anchor" aria-hidden="true" tabindex="-1" href="#know-more-about-james-design"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解更多关于詹姆斯设计的信息</font></font></h2>
<div dir="auto">
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">James 附带了</font></font><a href="https://james.apache.org/documentation.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/linagora/james-project/tree/master/src/adr"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">架构决策记录</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</div>
<div dir="auto">
<p dir="auto"><font style="vertical-align: inherit;"><a href="https://james.staged.apache.org/james-distributed-app/3.8.0/architecture/index.html" rel="nofollow"><font style="vertical-align: inherit;">可以在此处</font></a><font style="vertical-align: inherit;">找到
对</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分布式服务器</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">体系结构的更精确的描述</font><font style="vertical-align: inherit;">。</font></font><a href="https://james.staged.apache.org/james-distributed-app/3.8.0/architecture/index.html" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></p>
</div>
</div>
</div>
<div dir="auto">
<h2 id="user-content-articles-for-james-community" tabindex="-1" dir="auto"><a id="user-content-articles-for-james-community" class="anchor" aria-hidden="true" tabindex="-1" href="#articles-for-james-community"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">詹姆斯社区的文章</font></font></h2>
<div dir="auto">
<div dir="auto">
<ul dir="auto">
<li>
<p dir="auto"><a href="/apache/james-project/blob/master/docs/modules/community/pages/website.adoc"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何建立和发布网站</font></font></a></p>
</li>
<li>
<p dir="auto"><a href="/apache/james-project/blob/master/docs/modules/community/pages/release.adoc"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如何通过maven发布插件发布</font></font></a></p>
</li>
</ul>
</div>
</div>
</div></article></div>
