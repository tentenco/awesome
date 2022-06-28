# Awesome Nomad

令人驚嘆的 Nomad 工具和閃亮的東西的精選列表。

非常歡迎使用其他工具和項目的拉取請求！

## 用戶界面

- [jippi/hashi-ui](https://github.com/jippi/hashi-ui) - HashiCorp 的 Consul & Nomad 接口，實時數據流，快速搜索和每個集群或客戶端的資源可視化。
- [hashicorp/damon](https://github.com/hashicorp/damon) - Nomad 的早期終端儀表板。

## 自動縮放

- [hashicorp/nomad-autoscaler](https://github.com/hashicorp/nomad-autoscaler/) - HashiCorp 的官方 Nomad Autoscaler。支持在 Nomad 內擴展分配，並通過插件擴展 AWS、Azure、GCP 或任意基礎設施上的節點。
- [jrasell/chemtrail](https://github.com/jrasell/chemtrail) - Chemtrail 是 HashiCorp Nomad 的客戶端縮放器，允許根據需求動態和安全地縮放客戶端工作池。
- [jrasell/sherpa](https://github.com/jrasell/sherpa) - Sherpa 是 HashiCorp Nomad 的工作縮放器，旨在高度靈活，以便支持廣泛的架構和預算。
- [underarmour/libra](https://github.com/underarmour/libra) - 根據外部指標 Graphite 或 AWS CloudWatch 擴展 Nomad 任務組計數。
- [Spotinst](https://help.spotinst.com/hc/en-us/articles/115005038289-Nomad-Container-Management-) - SaaS Nomad 集群自動擴縮器，可選擇在 Spot 實例上運行客戶端（僅限 AWS）
- [trivago/scalad](https://github.com/trivago/scalad) - Scalad 是一個游牧水平縮放器，可以根據外部指標從每個作業任務組元節中進行設置。
- [dkt26111/nomad-senlin-autoscale](https://github.com/dkt26111/nomad-senlin-autoscaler) - OpenStack Senlin 的 Nomad Autoscaler 插件。
- [jsiebens/nomad-droplets-autoscaler](https://github.com/jsiebens/nomad-droplets-autoscaler) - 數字海洋水滴的 Nomad Autoscaler 插件。
- [lucretius/nomad-elastigroup-autoscaler](https://github.com/lucretius/nomad-elastigroup-autoscaler) - [Spot.io Elastigroup] (https://spot.io/products/elastigroup) 的 Nomad Autoscaler 插件/)。

## CI / CD

- [getnelson/nelson](https://getnelson.io/) - Nomad（和其他可插入調度程序）的無人值守部署和生命週期管理器。與 Vault 和 Consul 完全集成。可以選擇充當您的流量路由 teir 的控制平面。
- [jenkinsci/nomad-plugin](https://github.com/jenkinsci/nomad-plugin) - Jenkins 插件允許使用 Nomad Jobs 擴展 Jenkins 構建從站。
- [jrasell/levant](https://github.com/jrasell/levant) - HashiCorp Nomad 作業的模板和部署工具，可在部署問題時提供實時反饋和詳細的失敗消息。
- [ValFadeev/rundeck-nomad-plugin](https://github.com/ValFadeev/rundeck-nomad-plugin) - 一個 Rundeck 插件，用於由操作員或在自動部署管道中創作和運行 Nomad 作業。
- [screwdrivercd/nomad](http://screwdriver.cd/) - 使用 nomad 調度和執行由 scm (github/bitbucket) 觸發的工作流。
- [fortress-shell](https://github.com/fortress-shell/fortress-shell) - 基於 Hashicorp Nomad 自寫 CI/CD SaaS

## 插件

- [trivago/nomad-pot-driver](https://github.com/trivago/nomad-pot-driver) - 使用 Hashicorp 的 Nomad 管理 FreeBSD 監獄的插件
- [cneira/jail-task-driver](https://github.com/cneira/jail-task-driver) - 使用 FreeBSD 監獄的任務驅動程序
- [pascomnet/nomad-driver-podman](https://github.com/pascomnet/nomad-driver-podman) - [podman 容器] (https://podman.io) 的游牧任務驅動程序
- [Roblox/nomad-driver-containerd](https://github.com/Roblox/nomad-driver-containerd) - [containerd](https://containerd.io) 的游牧任務驅動程序。關於 [`nomadproject.io`](https://www.nomadproject.io/docs/drivers/external/containerd) 的文檔。
- [JanMa/nomad-driver-nspawn](https://github.com/JanMa/nomad-driver-nspawn) - 使用 [systemd-nspawn](https://www.freedesktop. org/software/systemd/man/systemd-nspawn.html）。
- [hpcng/nomad-driver-singularity](https://github.com/hpcng/nomad-driver-singularity) - 運行 [singularity 容器](https://github.com/sylabs/singularity) 的游牧任務驅動程序）。
- [Roblox/nomad-driver-iis](https://github.com/Roblox/nomad-driver-iis) - 運行 [windows IIS](https://www.iis.net/) 的 nomad 任務驅動程序任務。
- [cneira/firecracker-task-driver](https://github.com/cneira/firecracker-task-driver) - [Firecracker]的游牧任務驅動程序(https://firecracker-microvm.github.io/)微型虛擬機。
- [cneira/nomad-zones-driver](https://github.com/cneira/nomad-zones-driver) - [Illumos](https://illumos.org/) 區域的任務驅動程序。

＃＃ 自助服務

- [data-science-platform/cluster-broccoli](https://github.com/data-science-platform/cluster-broccoli) - Cluster Broccoli 是一個 RESTful Web 服務 + UI，用於通過自助服務應用程序管理 Nomad 作業. 作業是基於模板定義的，允許可選擇的定制量。

## 作業文件和包

- [hashicorp/nomad-pack-community-registry](https://github.com/hashicorp/nomad-pack-community-registry) - Nomad Pack 模板的官方社區註冊表。
- [jrasell/nomadfiles](https://github.com/jrasell/nomadfiles) Nomad 作業文件的集合，用於將應用程序部署到集群。
- [perrymanuk/hashi-homelab](https://github.com/perrymanuk/hashi-homelab) 基於 nomad 和來自 hashcorp 的 consul 的小型輕量級家庭實驗室的工作文件。

## 實用程序

- [seatgeek/nomad-helper](https://github.com/seatgeek/nomad-helper) - 簡單的幫助程序二進製文件，允許您重新評估所有作業、耗盡節點（並等待所有分配停止）、強制YAML 格式的垃圾收集、導出/導入作業任務組計數。
- [seatgeek/nomad-firehose](https://github.com/seatgeek/nomad-firehose) - 使用二進制“尾部”API 端點並將每個更改的資源的消息發送到 RabbitMQ、AWS kinesis 或 stdout。
- [seatgeek/nomad-crashloop-detector](https://github.com/seatgeek/nomad-crashloop-detector) - 使用來自 seatgeek/nomad-firehose 的 RabbitMQ 輸出，將檢測分配何時重新啟動過快或過於頻繁，將違規分配輸出到 RabbitMQ、AWS Kinesis 或 stdout。
- [jrasell/nomad-toast](https://github.com/jrasell/nomad-toast) - 基於 HashiCorp Nomad 事件接收通知的工具。
- [axsuul/nomad-event-streamer](http://github.com/axsuul/nomad-event-streamer) - 用於將事件發送到您最喜歡的目的地（例如 Discord）的工具。
- [sepulworld/deadman-check](https://github.com/sepulworld/deadman-check) - Nomad 定期作業的監視伴侶，如果定期未按預期間隔運行，則會發出警報。
- [blalor/nomad-watcher](https://github.com/blalor/nomad-watcher) - 一個簡單的服務，它監視 Nomad 的節點、作業、分配、部署和評估，並將事件寫入文件。還包括一個用於將事件拖尾到控制台窗口的實用程序。
- [smintz/nomadgen](https://github.com/smintz/nomadgen) - 使用 Python 定義您的 Nomad 工作規範。
- [jet/nomad-service-alerter](https://github.com/jet/nomad-service-alerter) - 一種為在 Nomad 上運行的作業提供選擇加入警報的工具。它主要涵蓋 Consul Health-check 警報和 Restart-Loop（當分配經常由於內部錯誤在“掛起”和“運行”狀態之間切換時）警報提供與 PagerDuty 的集成。
- [42wim/nomadctld](https://github.com/42wim/nomadctld) - 能夠執行/附加/logs/tail/stop hashcorp nomad 容器的 Ssh 服務器。
- [ataccam/nomad-deploy](https://github.com/ataccam/nomad-deploy) - 呈現 Jinja2 模板、計劃和註冊作業的 Python3 腳本。可從 [pypi.org](https://pypi.org/project/nomad-deploy/) 作為可執行文件安裝。
- [ngine-io/chaotic](https://github.com/ngine-io/chaotic) - 具有集成游牧支持的 Choas 猴子。作為批處理作業或服務運行，並定期隨機終止分配。
- [jsiebens/hashi-up](https://github.com/jsiebens/hashi-up) - 在任何遠程 Linux 主機上安裝 Nomad（和其他 HashiCorp 工具）的輕量級實用程序。
- [let-sh/nomad-deploy-result-action](https://github.com/let-sh/nomad-deploy-result-action) - 使用 GitOps 自動部署 Nomad 的 GitHub 操作。
- [koyeb/kreconciler](https://github.com/koyeb/kreconciler) - 在 Nomad（或其他調度程序）之上構建操作員和協調器的庫。
- [Roblox/nomad-node-problem-detector](https://github.com/Roblox/nomad-node-problem-detector) - 一種用於根據用戶定義的健康檢查檢測 Nomad 節點問題的工具。
- [hashicorp/nomad-pack](https://github.com/hashicorp/nomad-pack) - Nomad 的官方模板工具和包管理器，目前是技術預覽版。

## 教程

- [anubhavmishra/envoy-consul-sds](https://github.com/anubhavmishra/envoy-consul-sds) - 關於如何讓 Envoy 在 Nomad 上運行並使用 Envoy 的 SDS（服務發現服務）訪問 Consul 的教程API。
- [kelseyhightower/hashiconf-eu-2016](https://github.com/kelseyhightower/hashiconf-eu-2016) - 來自關於使用 GCE/Consul/Nomad/Fabio 負載平衡器構建部署的演講的回購。查看 youtube 上的演講：https://www.youtube.com/watch?v=Nosa5-xcATw

## 示例/演示

- [pete0emerson/hashipoc](https://github.com/pete0emerson/hashipoc) - 一個 Vagrant 驅動的示例，通過部署的示例應用程序讓 Consul / Vault / Nomad 啟動並運行
- [fhemberger/nomad-demo](https://github.com/fhemberger/nomad-demo) - 基於 Vagrant 的演示設置，用於運行 Hashicorp Consul、Nomad 和 Vault，包括 Docker、JRE 的示例應用程序和基本監控設置。使用 Traefik 作為負載均衡器，直接從 Consul 目錄中獲取服務。

＃＃ 其他

- [numkem/nomad-spk](https://github.com/numkem/nomad-spk) - 將 Hashicorp 的 nomad 調度程序安裝到 Synology NAS 的 spk（Synology 軟件包）