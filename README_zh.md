# CKS 备考指南

**支持语言:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/zh/courses/cks-prep">
    <img src="https://course-cover.labex.io/cks-prep.png?lang=zh" alt="CKS 备考指南">
  </a>
</p>

这是一门面向初学者的 CKS 备考课程，包含 45 个引导式 Kubernetes 安全实验。课程内容由浅入深，涵盖安全基础、集群搭建、加固、工作负载安全、供应链安全、审计及运行时调查等核心领域。

[在 LabEx 开始课程](https://labex.io/zh/courses/cks-prep)

## 练习

|   序号 | 名称                          | 难度   | 练习                                                                                                                                   |
|------|-----------------------------|------|--------------------------------------------------------------------------------------------------------------------------------------|
|   01 | 映射 Kubernetes 安全边界          | 初级   | <a target='_blank' href='https://labex.io/zh/labs/map-kubernetes-security-boundaries-663929?course=cks-prep'>开始实验</a>                |
|   02 | 使用 kubectl 收集安全证据           | 初级   | <a target='_blank' href='https://labex.io/zh/labs/collect-security-evidence-with-kubectl-663911?course=cks-prep'>开始实验</a>            |
|   03 | 回顾命名空间与租户隔离                 | 初级   | <a target='_blank' href='https://labex.io/zh/labs/review-namespaces-and-tenant-isolation-663942?course=cks-prep'>开始实验</a>            |
|   04 | 检查 RBAC 主体与权限               | 初级   | <a target='_blank' href='https://labex.io/zh/labs/inspect-rbac-subjects-and-permissions-663924?course=cks-prep'>开始实验</a>             |
|   05 | 检查 ServiceAccount Token 行为  | 初级   | <a target='_blank' href='https://labex.io/zh/labs/inspect-serviceaccount-token-behavior-663925?course=cks-prep'>开始实验</a>             |
|   06 | 应用 Pod 安全标准                 | 初级   | <a target='_blank' href='https://labex.io/zh/labs/apply-pod-security-standards-663906?course=cks-prep'>开始实验</a>                      |
|   07 | 使用 NetworkPolicy 限制命名空间流量   | 初级   | <a target='_blank' href='https://labex.io/zh/labs/restrict-namespace-traffic-with-networkpolicy-663938?course=cks-prep'>开始实验</a>     |
|   08 | 允许 DNS 通过默认拒绝的出站流量策略        | 初级   | <a target='_blank' href='https://labex.io/zh/labs/allow-dns-through-default-deny-egress-663905?course=cks-prep'>开始实验</a>             |
|   09 | 使用 TLS 发布 Ingress           | 初级   | <a target='_blank' href='https://labex.io/zh/labs/publish-ingress-with-tls-663932?course=cks-prep'>开始实验</a>                          |
|   10 | 拒绝工作负载访问节点元数据               | 初级   | <a target='_blank' href='https://labex.io/zh/labs/deny-workload-access-to-node-metadata-663913?course=cks-prep'>开始实验</a>             |
|   11 | 验证 Kubernetes 二进制文件         | 初级   | <a target='_blank' href='https://labex.io/zh/labs/verify-kubernetes-binaries-663948?course=cks-prep'>开始实验</a>                        |
|   12 | 使用 kube-bench 审查 CIS 安全基准发现 | 初级   | <a target='_blank' href='https://labex.io/zh/labs/review-cis-findings-with-kube-bench-663940?course=cks-prep'>开始实验</a>               |
|   13 | 检查准入与 Pod 安全就绪状态            | 初级   | <a target='_blank' href='https://labex.io/zh/labs/check-admission-and-pod-security-readiness-663910?course=cks-prep'>开始实验</a>        |
|   14 | 最小化角色权限                     | 初级   | <a target='_blank' href='https://labex.io/zh/labs/minimize-a-role-s-permissions-663930?course=cks-prep'>开始实验</a>                     |
|   15 | 缩减权限过大的 ClusterRoleBinding  | 初级   | <a target='_blank' href='https://labex.io/zh/labs/reduce-an-overprivileged-clusterrolebinding-663934?course=cks-prep'>开始实验</a>       |
|   16 | 禁用默认 ServiceAccount 令牌挂载    | 初级   | <a target='_blank' href='https://labex.io/zh/labs/disable-default-serviceaccount-token-mounts-663917?course=cks-prep'>开始实验</a>       |
|   17 | 限定命名空间操作员的角色权限              | 初级   | <a target='_blank' href='https://labex.io/zh/labs/scope-a-namespace-operator-role-663947?course=cks-prep'>开始实验</a>                   |
|   18 | 阻止 API Server 代理提权          | 初级   | <a target='_blank' href='https://labex.io/zh/labs/block-api-server-proxy-escalation-663908?course=cks-prep'>开始实验</a>                 |
|   19 | 包含泄露的 ServiceAccount 令牌     | 初级   | <a target='_blank' href='https://labex.io/zh/labs/contain-a-leaked-serviceaccount-token-663912?course=cks-prep'>开始实验</a>             |
|   20 | 审计敏感资源访问权限                  | 初级   | <a target='_blank' href='https://labex.io/zh/labs/audit-access-to-sensitive-resources-663907?course=cks-prep'>开始实验</a>               |
|   21 | 安全检查主机攻击面                   | 初级   | <a target='_blank' href='https://labex.io/zh/labs/inspect-host-attack-surface-safely-663923?course=cks-prep'>开始实验</a>                |
|   22 | 禁用主机调试服务                    | 初级   | <a target='_blank' href='https://labex.io/zh/labs/disable-a-host-debug-service-663916?course=cks-prep'>开始实验</a>                      |
|   23 | 审查 Kubelet 暴露情况             | 初级   | <a target='_blank' href='https://labex.io/zh/labs/review-kubelet-exposure-663941?course=cks-prep'>开始实验</a>                           |
|   24 | 审查工作负载的 AppArmor 配置文件强制执行情况 | 初级   | <a target='_blank' href='https://labex.io/zh/labs/review-apparmor-profile-enforcement-on-a-workload-663919?course=cks-prep'>开始实验</a> |
|   25 | 安装本地 seccomp 配置文件           | 初级   | <a target='_blank' href='https://labex.io/zh/labs/install-a-local-seccomp-profile-663926?course=cks-prep'>开始实验</a>                   |
|   26 | 移除工作负载的 HostPath 访问权限       | 初级   | <a target='_blank' href='https://labex.io/zh/labs/remove-hostpath-access-from-a-workload-663936?course=cks-prep'>开始实验</a>            |
|   27 | 加固 Pod 安全上下文                | 初级   | <a target='_blank' href='https://labex.io/zh/labs/harden-a-pod-security-context-663922?course=cks-prep'>开始实验</a>                     |
|   28 | 移除 Linux Capabilities       | 初级   | <a target='_blank' href='https://labex.io/zh/labs/drop-linux-capabilities-663918?course=cks-prep'>开始实验</a>                           |
|   29 | 以非 Root 用户身份运行容器            | 初级   | <a target='_blank' href='https://labex.io/zh/labs/run-containers-as-non-root-663944?course=cks-prep'>开始实验</a>                        |
|   30 | 使用投射文件保护密钥                  | 初级   | <a target='_blank' href='https://labex.io/zh/labs/protect-secrets-with-projected-files-663931?course=cks-prep'>开始实验</a>              |
|   31 | 旋转并限制应用密钥                   | 初级   | <a target='_blank' href='https://labex.io/zh/labs/rotate-and-constrain-application-secrets-663943?course=cks-prep'>开始实验</a>          |
|   32 | 隔离高风险的 Sidecar 边界           | 初级   | <a target='_blank' href='https://labex.io/zh/labs/isolate-a-risky-sidecar-boundary-663928?course=cks-prep'>开始实验</a>                  |
|   33 | 强制执行不可变运行时容器                | 初级   | <a target='_blank' href='https://labex.io/zh/labs/enforce-immutable-runtime-containers-663920?course=cks-prep'>开始实验</a>              |
|   34 | 隔离可疑工作负载                    | 初级   | <a target='_blank' href='https://labex.io/zh/labs/quarantine-a-suspicious-workload-663933?course=cks-prep'>开始实验</a>                  |
|   35 | 构建最小化合规镜像                   | 初级   | <a target='_blank' href='https://labex.io/zh/labs/build-a-minimal-approved-image-663909?course=cks-prep'>开始实验</a>                    |
|   36 | 使用 kube-linter 扫描工作负载清单     | 初级   | <a target='_blank' href='https://labex.io/zh/labs/scan-workload-manifests-with-kube-linter-663946?course=cks-prep'>开始实验</a>          |
|   37 | 使用 kube-linter 扫描 Helm 输出   | 初级   | <a target='_blank' href='https://labex.io/zh/labs/scan-helm-output-with-kube-linter-663945?course=cks-prep'>开始实验</a>                 |
|   38 | 验证 SBOM 和校验和证据              | 初级   | <a target='_blank' href='https://labex.io/zh/labs/verify-sbom-and-checksum-evidence-663949?course=cks-prep'>开始实验</a>                 |
|   39 | 强制执行受信任的镜像仓库                | 初级   | <a target='_blank' href='https://labex.io/zh/labs/enforce-trusted-image-registries-663921?course=cks-prep'>开始实验</a>                  |
|   40 | 从镜像中移除构建密钥                  | 初级   | <a target='_blank' href='https://labex.io/zh/labs/remove-build-secrets-from-an-image-663935?course=cks-prep'>开始实验</a>                |
|   41 | 审查 Secret 访问的审计事件           | 初级   | <a target='_blank' href='https://labex.io/zh/labs/review-audit-events-for-secret-access-663939?course=cks-prep'>开始实验</a>             |
|   42 | 调查未经授权的 API 活动              | 初级   | <a target='_blank' href='https://labex.io/zh/labs/investigate-unauthorized-api-activity-663927?course=cks-prep'>开始实验</a>             |
|   43 | 检测可疑运行时进程                   | 初级   | <a target='_blank' href='https://labex.io/zh/labs/detect-suspicious-runtime-processes-663915?course=cks-prep'>开始实验</a>               |
|   44 | 检测运行时文件漂移                   | 初级   | <a target='_blank' href='https://labex.io/zh/labs/detect-runtime-file-drift-663914?course=cks-prep'>开始实验</a>                         |
|   45 | 从审计证据中恢复策略                  | 初级   | <a target='_blank' href='https://labex.io/zh/labs/restore-policy-from-audit-evidence-663937?course=cks-prep'>开始实验</a>                |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

