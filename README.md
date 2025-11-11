# Code Vocabulary for Developers

一个个人学习资源，收集自真实开发场景的英语例句（包括文档、注释和技术规范），用于提升技术英语的理解与写作能力。| A personal learning resource of English example sentences collected from real-world developer contexts — documentation, comments, and specifications — curated to improve technical English comprehension and writing skills.

## Vocabulary

<details xmlns="http://www.w3.org/1999/html"><summary>autonomously</summary>

* adv. 自治的，独立自主地
</details>

<details><summary>auxiliary</summary>

* adj. 辅助的
  * You can also have sidecar containers that provide auxiliary services to the main application Pod (for example: a service mesh). | [查看原文](https://kubernetes.io/docs/concepts/workloads/pods/#:~:text=containers%20that%20provide-,auxiliary,-services%20to%20the) | 你也可以使用边车容器，边车容器为主应用 Pod 提供辅助服务（比如: service mesh）。
* adj. 备用的
</details>

<details><summary>beneath</summary>

* prep. 在...之下
    * If the ConfigMap exists, but the referenced key is non-existent, the path will be absent beneath the mount point. | [查看原文](https://v1-32.docs.kubernetes.io/docs/tasks/configure-pod-container/configure-pod-configmap/#:~:text=If%20the%20ConfigMap%20exists%2C%20but%20the%20referenced%20key%20is%20non%2Dexistent%2C%20the%20path%20will%20be%20absent%20beneath%20the%20mount%20point.) | 如果 ConfigMap 存在，但引用的 key 不存在，那么在挂载点下对应的路径将不会出现。
* prep. 配不上某人
* adv. 在下面，往下
</details>

<details><summary>broadly</summary>

* adv. 大体上，整体上
  * Broadly, a version string might look like v2 or v2beta1. ｜ [查看原文](https://v1-32.docs.kubernetes.io/docs/tasks/extend-kubernetes/custom-resources/custom-resource-definition-versioning/#:~:text=Broadly%2C%20a%20version%20string%20might%20look%20like%20v2%20or%20v2beta1.) ｜ 大体上，一个版本字符串可能看起来像 v2 或者 v2beta1 这样。
* adv. 咧嘴（笑）地
</details>

<details>

<summary>corporate</summary>

* adj. 公司的
  * [Kubernetes pods installed on linux server can’t access any API’s or ips from local **corporate** network but can communicate with each other and internet.](https://discuss.kubernetes.io/t/kubernetes-pods-installed-on-linux-server-cant-access-any-apis-or-ips-from-local-corporate-network-but-can-communicate-with-each-other-and-internet/30226/1)
    * 运行在 Linux 服务器上的 k8s pods，无法访问本地**公司**网络的任何 API 或 IP，但可以互相通信并访问互联网。
* adj. 全体的，团体的

</details>

<details><summary>delicate</summary>

* adj. 微妙的；易受损的；精美的
  * Delicate dance: the semaphore implementation calls acquireSudog, acquireSudog calls new(sudog), new calls malloc, malloc can call the garbage collector, and the garbage collector calls the semaphore implementation in stopTheWorld. Break the cycle by doing acquirem/releasem around new(sudog). The acquirem/releasem increments m.locks during new(sudog), which keeps the garbage collector from being invoked. | [查看原文](https://github.com/golang/go/blob/a5f55a441ef497d8e2a12610f4ec2bd32fdc04b2/src/runtime/proc.go#L491) | 精妙的配合：信号量的实现会调用 acquireSudog，acquireSudog 会调用 new(sudog)，new 会调用 malloc，malloc 可能会调用垃圾回收器，而垃圾回收器在 stopTheWorld 中又会调用信号量的实现。通过在 new(sudog) 周围执行 acquirem/releasem 来打破这个循环。acquirem/releasem 会在执行 new(sudog) 期间增加 m.locks，这样可以防止垃圾回收器被调用。
* adj.（仪器等）精密的
* adj. (人)柔弱的
</details>

<details>

<summary>generic</summary>

* adj. 一般的，通用的
* adj. 无商标的

</details>

<details><summary>override</summary>

* vt.（以权利）否决，推翻
* vt. 凌驾
* vt. 覆盖
  * The kubelet is the primary "node agent" that runs on each node. It can register the node with the apiserver using one of: the hostname; a flag to override the hostname; or specific logic for a cloud provider. | [查看原文](https://kubernetes.io/docs/reference/command-line-tools-reference/kubelet/#synopsis:~:text=Synopsis-,The,-kubelet%20is%20the) | kubelet 是主要的“节点代理”，运行在每个节点上。它可以使用以下之一向 apiserver 注册节点：主机名；一个覆盖主机名的 flag；或者云服务提供商的特定逻辑。
</details>

<details><summary>overuse</summary>

* n. 使用过度，滥用
  * Overuse of `//go:linkname` to reach into Go standard library internals (especially runtime internals) means that when we do change the standard library internals in ways that should not matter, we can end up breaking packages that are depended on by a large swath of the Go ecosystem. | [查看原文](https://github.com/golang/go/issues/67401#:~:text=Contributor-,Overuse,-of%20//go%3Alinkname) | 过度使用 `//go:linkname` 访问 Go 标准库的内部（尤其是 runtime 的内部），意味着当我们以本不该影响外部的方式修改标准库内部时，可能会导致依赖这些包的 Go 生态系统中大量软件发生破坏。
* vt. 使用国服，滥用
</details>

<details><summary>pea</summary>

* n. 豌豆
  * [A Pod (as in a pod of whales or **pea** pod) is a group of one or more containers.](https://kubernetes.io/docs/concepts/workloads/pods/#:~:text=as%20in%20a%20pod%20of%20whales%20or%20pea%20pod)
    * 一个 Pod（就像鲸群或者豌豆荚）是一组容器。

</details>

<details><summary>personalize</summary>

* vt. 为个人定制
  * **Personalization**. To tailor the content and information that we may send or display to you on our Sites and in our Services, to offer location customization and **personalized** help and instructions and to otherwise **personalize** your experiences. | [查看原文](https://www.linuxfoundation.org/legal/privacy-policy#:~:text=our%20legal%20rights.-,Personalization,-.%20To%20tailor%20the) | 个性化。（我们收集个人信息的目的之一），是定制我们可能在网站和服务中向您发送或展示的内容和信息，是为了提供基于位置的定制服务以及个性化的帮助和指导，从而使您的使用体验更加个性化。
</details>

<details>

<summary>portal</summary>

* n. 门户网站
  * [Backstage is an open framework for building developer **portals**.](https://github.com/backstage/backstage#:~:text=Backstage%20is%20an%20open%20framework%20for%20building%20developer%20portals)
    * Backstage 是一个用于构建开发者**门户**的开放框架。
* n. 出入口
* n. 正门

</details>

<details><summary>pod</summary>

* n. 豆荚
  * A Pod (as in a pod of whales or pea **pod**) is a group of one or more containers. | [查看原文](https://kubernetes.io/docs/concepts/workloads/pods/#:~:text=as%20in%20a%20pod%20of%20whales%20or%20pea%20pod) | 一个 Pod（就像鲸群或者豌**豆荚**）是一组容器。
* n. 飞机吊舱
* n. 分离舱
* n. 一群
  * A Pod (as in a **pod** of whales or pea pod) is a group of one or more containers. | [查看原文](https://kubernetes.io/docs/concepts/workloads/pods/#:~:text=as%20in%20a%20pod%20of%20whales%20or%20pea%20pod) | 一个 Pod（就像鲸**群**或者豌豆荚）是一组容器。
</details>

<details><summary>primary</summary>

* adj. 首要的
  * The kubelet is the **primary** "node agent" that runs on each node. | [查看原文](https://kubernetes.io/docs/reference/command-line-tools-reference/kubelet/#synopsis:~:text=The%20kubelet%20is%20the%20primary%20%22node%20agent%22%20that%20runs%20on%20each%20node.) | kubelet 是**首要的**“节点代理”，运行在每个节点上。
* adj. 最早的
* adj. 小学的
</details>

<details><summary>prime</summary>

* adj. 首要的
  * CI/CD servers are **prime** targets for attacks, giving hackers access to source code and sensitive data. | [查看原文](https://www.jetbrains.com/lp/teamcity-cicd-security-whitepaper/#:~:text=CI/CD%20servers%20are%20prime%20targets%20for%20attacks%2C%20giving%20hackers%20access%20to%20source%20code%20and%20sensitive%20data.) | CI/CD服务器是攻击的**首要**目标，使黑客能够访问源代码和敏感数据。
* adj. 最好的
* adj. 典型的
* n. 盛年，鼎盛时期
* vt. 准备
  * Priming the Cache. | [查看原文](https://support.ptc.com/help/windchillrvs/r13.0.0.0/en/index.html#page/IntegrityHelp/serv_proxy_FSA_priming_proxy.mif-3.html) | “Priming the cache”（预热缓存 / 预先填充缓存）指的是在系统正式运行前，主动将常用或关键的数据加载到缓存中，以避免用户首次访问时触发缓存未命中（cache miss）而导致的性能下降。
* vt. 事先指点
</details>

<details><summary>progress</summary>

* n. 进步，进展；前进
  * Go 1.26 is not yet released. These are **work-in-progress** release notes. Go 1.26 is expected to be released in February 2026. | [查看原文](https://tip.golang.org/doc/go1.26#introduction) | Go 1.26 还没有发布，目前的文档是开发中的版本说明。Go 1.26 预计会在 2026 年 2 月发布。
* vi. 取得进步；前进；（时间）流逝

</details>

<details><summary>replica</summary>

* n. 复制品，仿制品
  * [On the source and each **replica**, you must set the server_id system variable to establish a unique replication ID in the range from 1 to 2<sup>32</sup> − 1.](https://dev.mysql.com/doc/refman/8.0/en/replication-options-replica.html#:~:text=On%20the%20source%20and%20each%20replica%2C%20you%20must%20set%20the%20server_id%20system%20variable%20to%20establish%20a%20unique%20replication%20ID%20in%20the%20range%20from%201%20to%20232%20%E2%88%92%201.)
    * 在主服务器与每个**副本**上，都必须设置 server_id 系统变量，以建立一个在 1 到 2³² − 1 范围内唯一的复制 ID。

</details>

<details>

<summary>shelve</summary>

* vt. 搁置（计划）
* vt. 把...放在架子上
* vi. （陆地）倾斜

</details>

<details>

<summary>shift</summary>

* vi. vt. 转移，挪动
  * **Shift** Testing Left. [原文](https://telepresence.io/#:~:text=see%20results%20immediately.-,Shift%20Testing%20Left,-You%20want%20to) 把测试提前到开发早期进行，让问题更早被发现、更便宜地解决。
  * **Shift** the positional parameters to the left by n: the positional parameters from `n+1` … `$#` are renamed to `$1` … `$#-n`. [原文](https://www.gnu.org/software/bash/manual/bash.html#:~:text=Shift%20the%20positional%20parameters%20to%20the%20left%20by%20n%3A%20the%20positional%20parameters%20from%20n%2B1%20%E2%80%A6%20%24%23%20are%20renamed%20to%20%241%20%E2%80%A6%20%24%23%2Dn.) 把位置参数向左**移动** n 个位置：从 `n+1` 到 `$#` 的位置参数被重命名为 `$1` 到 `$#-n`.
* vi. vt. 换（挡）
* vi. （情况等）改变
* vt. 改变观点（态度等）
* vt. 推卸（责任）
* n. 改变，转变

</details>

<details><summary>synopsis</summary>

* n.（书、电影等）提要，梗概
  * [Synopsis](https://kubernetes.io/docs/reference/command-line-tools-reference/kubelet/#synopsis)
</details>

<details>

<summary>tele-</summary>

* comb. "远距离"
  * [Telepresence](https://telepresence.io/) 远程呈现
  * [Telemetry](https://opentelemetry.io/) 遥感勘测；远距离测量术

</details>

## License

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/) — see the [LICENSE](https://github.com/dushaoshuai/code-vocab/blob/main/LICENSE) file for details.
