# Préparation CKS

**Langues:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/fr/courses/cks-prep">
    <img src="https://course-cover.labex.io/cks-prep.png?lang=fr" alt="Préparation CKS">
  </a>
</p>

Un cours de préparation au CKS adapté aux débutants, comprenant 45 laboratoires Kubernetes guidés, structurés des bases de la sécurité à la configuration des clusters, au durcissement, à la sécurité des charges de travail, à la chaîne d'approvisionnement, à l'audit et à l'analyse du runtime.

[Commencer le cours sur LabEx](https://labex.io/fr/courses/cks-prep)

## Exercices

|   Index | Nom                                                   | Difficulté   | Pratique                                                                                                                                         |
|---------|-------------------------------------------------------|--------------|--------------------------------------------------------------------------------------------------------------------------------------------------|
|      01 | Cartographier les frontières de sécurité Kubernete... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/map-kubernetes-security-boundaries-663929?course=cks-prep'>Commencer le lab</a>                |
|      02 | Collecter des preuves de sécurité avec kubectl        | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/collect-security-evidence-with-kubectl-663911?course=cks-prep'>Commencer le lab</a>            |
|      03 | Examen des Namespaces et de l'isolation des locata... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/review-namespaces-and-tenant-isolation-663942?course=cks-prep'>Commencer le lab</a>            |
|      04 | Inspecter les sujets et les permissions RBAC          | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/inspect-rbac-subjects-and-permissions-663924?course=cks-prep'>Commencer le lab</a>             |
|      05 | Inspecter le comportement des jetons ServiceAccoun... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/inspect-serviceaccount-token-behavior-663925?course=cks-prep'>Commencer le lab</a>             |
|      06 | Appliquer les standards de sécurité des Pods          | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/apply-pod-security-standards-663906?course=cks-prep'>Commencer le lab</a>                      |
|      07 | Restreindre le trafic d'un namespace avec NetworkP... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/restrict-namespace-traffic-with-networkpolicy-663938?course=cks-prep'>Commencer le lab</a>     |
|      08 | Autoriser le DNS via une politique de refus par dé... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/allow-dns-through-default-deny-egress-663905?course=cks-prep'>Commencer le lab</a>             |
|      09 | Publier une ressource Ingress avec TLS                | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/publish-ingress-with-tls-663932?course=cks-prep'>Commencer le lab</a>                          |
|      10 | Refuser l'accès des charges de travail aux métadon... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/deny-workload-access-to-node-metadata-663913?course=cks-prep'>Commencer le lab</a>             |
|      11 | Vérification des binaires Kubernetes                  | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/verify-kubernetes-binaries-663948?course=cks-prep'>Commencer le lab</a>                        |
|      12 | Examen des résultats CIS avec kube-bench              | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/review-cis-findings-with-kube-bench-663940?course=cks-prep'>Commencer le lab</a>               |
|      13 | Vérification de l'admission et de la préparation à... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/check-admission-and-pod-security-readiness-663910?course=cks-prep'>Commencer le lab</a>        |
|      14 | Minimiser les permissions d'un rôle                   | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/minimize-a-role-s-permissions-663930?course=cks-prep'>Commencer le lab</a>                     |
|      15 | Réduire une liaison ClusterRoleBinding surprivilég... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/reduce-an-overprivileged-clusterrolebinding-663934?course=cks-prep'>Commencer le lab</a>       |
|      16 | Désactiver le montage automatique des jetons de Se... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/disable-default-serviceaccount-token-mounts-663917?course=cks-prep'>Commencer le lab</a>       |
|      17 | Définir le périmètre d'un rôle d'opérateur dans un... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/scope-a-namespace-operator-role-663947?course=cks-prep'>Commencer le lab</a>                   |
|      18 | Blocage de l'escalade via le proxy de l'API Server    | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/block-api-server-proxy-escalation-663908?course=cks-prep'>Commencer le lab</a>                 |
|      19 | Contenir un jeton de ServiceAccount ayant fuité       | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/contain-a-leaked-serviceaccount-token-663912?course=cks-prep'>Commencer le lab</a>             |
|      20 | Auditer l'accès aux ressources sensibles              | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/audit-access-to-sensitive-resources-663907?course=cks-prep'>Commencer le lab</a>               |
|      21 | Inspecter la surface d'attaque de l'hôte en toute ... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/inspect-host-attack-surface-safely-663923?course=cks-prep'>Commencer le lab</a>                |
|      22 | Désactiver un service de débogage hôte                | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/disable-a-host-debug-service-663916?course=cks-prep'>Commencer le lab</a>                      |
|      23 | Examen de l'exposition du kubelet                     | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/review-kubelet-exposure-663941?course=cks-prep'>Commencer le lab</a>                           |
|      24 | Vérification de l'application d'un profil AppArmor... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/review-apparmor-profile-enforcement-on-a-workload-663919?course=cks-prep'>Commencer le lab</a> |
|      25 | Installer un profil seccomp local                     | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/install-a-local-seccomp-profile-663926?course=cks-prep'>Commencer le lab</a>                   |
|      26 | Supprimer l'accès HostPath d'une charge de travail    | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/remove-hostpath-access-from-a-workload-663936?course=cks-prep'>Commencer le lab</a>            |
|      27 | Renforcer le contexte de sécurité d'un Pod            | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/harden-a-pod-security-context-663922?course=cks-prep'>Commencer le lab</a>                     |
|      28 | Suppression des capacités Linux                       | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/drop-linux-capabilities-663918?course=cks-prep'>Commencer le lab</a>                           |
|      29 | Exécuter des conteneurs en tant qu'utilisateur non... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/run-containers-as-non-root-663944?course=cks-prep'>Commencer le lab</a>                        |
|      30 | Protéger les secrets avec des fichiers projetés       | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/protect-secrets-with-projected-files-663931?course=cks-prep'>Commencer le lab</a>              |
|      31 | Rotation et restriction des secrets d'application     | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/rotate-and-constrain-application-secrets-663943?course=cks-prep'>Commencer le lab</a>          |
|      32 | Isoler une limite de sidecar à risque                 | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/isolate-a-risky-sidecar-boundary-663928?course=cks-prep'>Commencer le lab</a>                  |
|      33 | Appliquer des conteneurs d'exécution immuables        | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/enforce-immutable-runtime-containers-663920?course=cks-prep'>Commencer le lab</a>              |
|      34 | Mise en quarantaine d'une charge de travail suspec... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/quarantine-a-suspicious-workload-663933?course=cks-prep'>Commencer le lab</a>                  |
|      35 | Construire une image minimale approuvée               | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/build-a-minimal-approved-image-663909?course=cks-prep'>Commencer le lab</a>                    |
|      36 | Analyser les manifestes de charge de travail avec ... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/scan-workload-manifests-with-kube-linter-663946?course=cks-prep'>Commencer le lab</a>          |
|      37 | Analyser la sortie Helm avec kube-linter              | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/scan-helm-output-with-kube-linter-663945?course=cks-prep'>Commencer le lab</a>                 |
|      38 | Vérifier la nomenclature logicielle (SBOM) et les ... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/verify-sbom-and-checksum-evidence-663949?course=cks-prep'>Commencer le lab</a>                 |
|      39 | Appliquer des registres d'images de confiance         | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/enforce-trusted-image-registries-663921?course=cks-prep'>Commencer le lab</a>                  |
|      40 | Supprimer les secrets de build d'une image            | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/remove-build-secrets-from-an-image-663935?course=cks-prep'>Commencer le lab</a>                |
|      41 | Examen des événements d'audit pour l'accès aux Sec... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/review-audit-events-for-secret-access-663939?course=cks-prep'>Commencer le lab</a>             |
|      42 | Enquêter sur une activité API non autorisée           | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/investigate-unauthorized-api-activity-663927?course=cks-prep'>Commencer le lab</a>             |
|      43 | Détecter les processus d'exécution suspects           | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/detect-suspicious-runtime-processes-663915?course=cks-prep'>Commencer le lab</a>               |
|      44 | Détecter la dérive de fichiers au runtime             | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/detect-runtime-file-drift-663914?course=cks-prep'>Commencer le lab</a>                         |
|      45 | Restaurer une politique à partir des preuves d'aud... | Débutant     | <a target='_blank' href='https://labex.io/fr/labs/restore-policy-from-audit-evidence-663937?course=cks-prep'>Commencer le lab</a>                |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>

