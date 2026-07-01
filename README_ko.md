# CKS 준비 과정

**언어:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/ko/courses/cks-prep">
    <img src="https://course-cover.labex.io/cks-prep.png?lang=ko" alt="CKS 준비 과정">
  </a>
</p>

보안 기초부터 클러스터 설정, 강화, 워크로드 보안, 공급망, 감사, 런타임 조사까지 총 45 개의 가이드형 Kubernetes 보안 실습으로 구성된 초보자 맞춤형 CKS 준비 과정입니다.

[LabEx에서 코스 시작](https://labex.io/ko/courses/cks-prep)

## 연습

|   인덱스 | 이름                                      | 난이도   | 연습                                                                                                                                    |
|-------|-----------------------------------------|-------|---------------------------------------------------------------------------------------------------------------------------------------|
|    01 | Kubernetes 보안 경계 매핑                     | 초급    | <a target='_blank' href='https://labex.io/ko/labs/map-kubernetes-security-boundaries-663929?course=cks-prep'>실습 시작</a>                |
|    02 | kubectl 을 이용한 보안 증거 수집                  | 초급    | <a target='_blank' href='https://labex.io/ko/labs/collect-security-evidence-with-kubectl-663911?course=cks-prep'>실습 시작</a>            |
|    03 | 네임스페이스 및 테넌트 격리 검토                      | 초급    | <a target='_blank' href='https://labex.io/ko/labs/review-namespaces-and-tenant-isolation-663942?course=cks-prep'>실습 시작</a>            |
|    04 | RBAC 주체 및 권한 검사                         | 초급    | <a target='_blank' href='https://labex.io/ko/labs/inspect-rbac-subjects-and-permissions-663924?course=cks-prep'>실습 시작</a>             |
|    05 | ServiceAccount 토큰 동작 검사                 | 초급    | <a target='_blank' href='https://labex.io/ko/labs/inspect-serviceaccount-token-behavior-663925?course=cks-prep'>실습 시작</a>             |
|    06 | Pod 보안 표준 적용하기                          | 초급    | <a target='_blank' href='https://labex.io/ko/labs/apply-pod-security-standards-663906?course=cks-prep'>실습 시작</a>                      |
|    07 | NetworkPolicy 를 사용한 네임스페이스 트래픽 제한       | 초급    | <a target='_blank' href='https://labex.io/ko/labs/restrict-namespace-traffic-with-networkpolicy-663938?course=cks-prep'>실습 시작</a>     |
|    08 | 기본 거부 (Default-Deny) 이그레스 환경에서 DNS 허용하기 | 초급    | <a target='_blank' href='https://labex.io/ko/labs/allow-dns-through-default-deny-egress-663905?course=cks-prep'>실습 시작</a>             |
|    09 | TLS 를 사용한 Ingress 게시                    | 초급    | <a target='_blank' href='https://labex.io/ko/labs/publish-ingress-with-tls-663932?course=cks-prep'>실습 시작</a>                          |
|    10 | 워크로드의 노드 메타데이터 접근 차단                    | 초급    | <a target='_blank' href='https://labex.io/ko/labs/deny-workload-access-to-node-metadata-663913?course=cks-prep'>실습 시작</a>             |
|    11 | Kubernetes 바이너리 검증                      | 초급    | <a target='_blank' href='https://labex.io/ko/labs/verify-kubernetes-binaries-663948?course=cks-prep'>실습 시작</a>                        |
|    12 | kube-bench 를 이용한 CIS 결과 검토              | 초급    | <a target='_blank' href='https://labex.io/ko/labs/review-cis-findings-with-kube-bench-663940?course=cks-prep'>실습 시작</a>               |
|    13 | Admission 및 Pod 보안 준비 상태 확인             | 초급    | <a target='_blank' href='https://labex.io/ko/labs/check-admission-and-pod-security-readiness-663910?course=cks-prep'>실습 시작</a>        |
|    14 | 역할(Role) 권한 최소화                         | 초급    | <a target='_blank' href='https://labex.io/ko/labs/minimize-a-role-s-permissions-663930?course=cks-prep'>실습 시작</a>                     |
|    15 | 과도한 권한이 부여된 ClusterRoleBinding 축소하기     | 초급    | <a target='_blank' href='https://labex.io/ko/labs/reduce-an-overprivileged-clusterrolebinding-663934?course=cks-prep'>실습 시작</a>       |
|    16 | 기본 ServiceAccount 토큰 마운트 비활성화           | 초급    | <a target='_blank' href='https://labex.io/ko/labs/disable-default-serviceaccount-token-mounts-663917?course=cks-prep'>실습 시작</a>       |
|    17 | 네임스페이스 오퍼레이터 역할 범위 지정                   | 초급    | <a target='_blank' href='https://labex.io/ko/labs/scope-a-namespace-operator-role-663947?course=cks-prep'>실습 시작</a>                   |
|    18 | API 서버 프록시 권한 상승 차단                     | 초급    | <a target='_blank' href='https://labex.io/ko/labs/block-api-server-proxy-escalation-663908?course=cks-prep'>실습 시작</a>                 |
|    19 | 유출된 ServiceAccount 토큰 격리                | 초급    | <a target='_blank' href='https://labex.io/ko/labs/contain-a-leaked-serviceaccount-token-663912?course=cks-prep'>실습 시작</a>             |
|    20 | 민감한 리소스에 대한 액세스 감사                      | 초급    | <a target='_blank' href='https://labex.io/ko/labs/audit-access-to-sensitive-resources-663907?course=cks-prep'>실습 시작</a>               |
|    21 | 호스트 공격 표면 안전하게 검사하기                     | 초급    | <a target='_blank' href='https://labex.io/ko/labs/inspect-host-attack-surface-safely-663923?course=cks-prep'>실습 시작</a>                |
|    22 | 호스트 디버그 서비스 비활성화                        | 초급    | <a target='_blank' href='https://labex.io/ko/labs/disable-a-host-debug-service-663916?course=cks-prep'>실습 시작</a>                      |
|    23 | kubelet 노출 검토                           | 초급    | <a target='_blank' href='https://labex.io/ko/labs/review-kubelet-exposure-663941?course=cks-prep'>실습 시작</a>                           |
|    24 | 워크로드에 대한 AppArmor 프로필 적용 검토             | 초급    | <a target='_blank' href='https://labex.io/ko/labs/review-apparmor-profile-enforcement-on-a-workload-663919?course=cks-prep'>실습 시작</a> |
|    25 | 로컬 seccomp 프로필 설치                       | 초급    | <a target='_blank' href='https://labex.io/ko/labs/install-a-local-seccomp-profile-663926?course=cks-prep'>실습 시작</a>                   |
|    26 | 워크로드에서 HostPath 액세스 제거                  | 초급    | <a target='_blank' href='https://labex.io/ko/labs/remove-hostpath-access-from-a-workload-663936?course=cks-prep'>실습 시작</a>            |
|    27 | Pod 보안 컨텍스트 강화                          | 초급    | <a target='_blank' href='https://labex.io/ko/labs/harden-a-pod-security-context-663922?course=cks-prep'>실습 시작</a>                     |
|    28 | Linux Capabilities 제한하기                 | 초급    | <a target='_blank' href='https://labex.io/ko/labs/drop-linux-capabilities-663918?course=cks-prep'>실습 시작</a>                           |
|    29 | 컨테이너를 Non-Root 로 실행하기                   | 초급    | <a target='_blank' href='https://labex.io/ko/labs/run-containers-as-non-root-663944?course=cks-prep'>실습 시작</a>                        |
|    30 | 프로젝티드 파일 (Projected Files) 을 사용한 시크릿 보호 | 초급    | <a target='_blank' href='https://labex.io/ko/labs/protect-secrets-with-projected-files-663931?course=cks-prep'>실습 시작</a>              |
|    31 | 애플리케이션 시크릿 (Secret) 교체 및 권한 제한          | 초급    | <a target='_blank' href='https://labex.io/ko/labs/rotate-and-constrain-application-secrets-663943?course=cks-prep'>실습 시작</a>          |
|    32 | 위험한 사이드카 경계 격리하기                        | 초급    | <a target='_blank' href='https://labex.io/ko/labs/isolate-a-risky-sidecar-boundary-663928?course=cks-prep'>실습 시작</a>                  |
|    33 | 불변 런타임 컨테이너 강제 적용                       | 초급    | <a target='_blank' href='https://labex.io/ko/labs/enforce-immutable-runtime-containers-663920?course=cks-prep'>실습 시작</a>              |
|    34 | 의심스러운 워크로드 격리                           | 초급    | <a target='_blank' href='https://labex.io/ko/labs/quarantine-a-suspicious-workload-663933?course=cks-prep'>실습 시작</a>                  |
|    35 | 최소한의 승인된 이미지 빌드                         | 초급    | <a target='_blank' href='https://labex.io/ko/labs/build-a-minimal-approved-image-663909?course=cks-prep'>실습 시작</a>                    |
|    36 | kube-linter 를 사용한 워크로드 매니페스트 스캔         | 초급    | <a target='_blank' href='https://labex.io/ko/labs/scan-workload-manifests-with-kube-linter-663946?course=cks-prep'>실습 시작</a>          |
|    37 | kube-linter 를 사용하여 Helm 출력 스캔하기         | 초급    | <a target='_blank' href='https://labex.io/ko/labs/scan-helm-output-with-kube-linter-663945?course=cks-prep'>실습 시작</a>                 |
|    38 | SBOM 및 체크섬 증거 검증                        | 초급    | <a target='_blank' href='https://labex.io/ko/labs/verify-sbom-and-checksum-evidence-663949?course=cks-prep'>실습 시작</a>                 |
|    39 | 신뢰할 수 있는 이미지 레지스트리 강제 적용                | 초급    | <a target='_blank' href='https://labex.io/ko/labs/enforce-trusted-image-registries-663921?course=cks-prep'>실습 시작</a>                  |
|    40 | 이미지에서 빌드 시크릿 제거하기                       | 초급    | <a target='_blank' href='https://labex.io/ko/labs/remove-build-secrets-from-an-image-663935?course=cks-prep'>실습 시작</a>                |
|    41 | Secret 접근에 대한 감사 이벤트 검토                 | 초급    | <a target='_blank' href='https://labex.io/ko/labs/review-audit-events-for-secret-access-663939?course=cks-prep'>실습 시작</a>             |
|    42 | 비인가 API 활동 조사                           | 초급    | <a target='_blank' href='https://labex.io/ko/labs/investigate-unauthorized-api-activity-663927?course=cks-prep'>실습 시작</a>             |
|    43 | 의심스러운 런타임 프로세스 탐지                       | 초급    | <a target='_blank' href='https://labex.io/ko/labs/detect-suspicious-runtime-processes-663915?course=cks-prep'>실습 시작</a>               |
|    44 | 런타임 파일 드리프트 탐지                          | 초급    | <a target='_blank' href='https://labex.io/ko/labs/detect-runtime-file-drift-663914?course=cks-prep'>실습 시작</a>                         |
|    45 | 감사 증적을 통한 정책 복구                         | 초급    | <a target='_blank' href='https://labex.io/ko/labs/restore-policy-from-audit-evidence-663937?course=cks-prep'>실습 시작</a>                |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

