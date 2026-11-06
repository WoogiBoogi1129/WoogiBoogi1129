# Hi, I'm H. Taeuk 👋

### Cloud Architecture · Kubernetes · Platform Engineering

Kubernetes 기반 인프라와 GPU 워크로드 실행 환경을 연구·개발합니다.
클러스터 구축부터 자원 관리, 배포 자동화, 사용자 개발 환경까지
연결되는 클라우드 아키텍처에 관심을 두고 있습니다.

숭실대학교 DCN 연구실에서 연구원으로 활동하며,
구현 과정과 실험 결과를 코드와 문서로 정리하고 있습니다.

## 🔭 What I Work On

- **Cloud Infrastructure**
  Linux 기반 Kubernetes 클러스터 구성과 설치 자동화

- **GPU & Virtualized Workloads**
  Kubernetes·KubeVirt 환경의 GPU 실행·공유와 자원 수명 주기 관리

- **Developer Platforms**
  Kubernetes GPU Pod와 VS Code·JupyterHub를 연결하는 개발 환경

- **Automation & Access Control**
  Operator 기반 리소스 관리, Argo CD 배포 실습,
  Namespace·RBAC를 활용한 사용자별 실습 환경 구성

## 🛠️ Selected Projects

### [VMWeave-GPU](https://github.com/WoogiBoogi1129/VMWeave-GPU)

Kubernetes가 관리하는 가상머신을 위한 GPU 실행·공유 시스템을
연구·개발합니다. 공유 메모리 기반 실행 경로와 Operator를 통해
GPU 할당 및 수명 주기를 관리하는 구조를 다룹니다.

- 주요 기술: Kubernetes, KubeVirt, Go, Python, Helm, HAMi
- 공개 자료: 아키텍처, 배포 절차, 실험 결과 및 검증 범위
- 상태: 연구·개발 단계

### [GPU Pod Runner](https://github.com/WoogiBoogi1129/GPU-Pod-Runner)

VS Code에서 Python 파일을 Kubernetes GPU execution Pod로
실행하도록 돕는 확장 프로그램입니다.
개발 환경과 GPU 실행 자원을 연결하는 흐름을 구현합니다.

- 주요 기술: TypeScript, Kubernetes, VS Code, JupyterHub
- 주요 기능: 실행 Pod 생성·상태 조회·정리,
  ServiceAccount 및 kubeconfig 인증, 공유 작업 공간 연동

### [Kubernetes Installer](https://github.com/WoogiBoogi1129/Kubernetes_Installer)

Kubernetes 클러스터 구축 과정을 자동화하는 Shell 스크립트입니다.
CRI-O·kubeadm 기반 구성과 Kubernetes·런타임·Cilium 버전 선택을 지원합니다.

- 주요 기술: Linux, Shell, Kubernetes, CRI-O, Cilium
- 목적: 반복적인 설치 작업을 줄이고 클러스터 구성 절차를 코드로 관리

### [Kubernetes Multi-Tenant Practice](https://github.com/WoogiBoogi1129/Kubernetes-Multi-Tenant-Practice)

하나의 Kubernetes 클러스터에서 여러 사용자가 실습할 수 있도록
Namespace와 RBAC 기반 환경 구성을 자동화한 프로젝트입니다.

- 주요 기술: Kubernetes, Shell, RBAC, kubeconfig
- 구성 범위: 사용자·Namespace 생성, 인증서 및 권한 설정,
  사용자별 kubeconfig 분리
- 활용 범위: 교육·실습용 환경

## 📚 What I Share

구축 과정과 실습 내용을 다른 사람이 따라 해볼 수 있도록 정리합니다.

- [Argo CD Demo](https://github.com/WoogiBoogi1129/ArgoCD_Demo)
  — Kubernetes 기초부터 Argo CD 기반 운용까지 다루는 워크숍 데모

- [Operator SDK Seminar](https://github.com/WoogiBoogi1129/Operator-SDK-Seminar)
  — Kubernetes Operator 개발 실습을 위한 세미나 자료

- [SQLite Index Performance Lab](https://github.com/WoogiBoogi1129/sqlite-index-performance-lab)
  — 실행 계획, 조회 지연, 삽입 비용, 저장 공간을 비교하는 성능 실험

## ⚙️ Tech Stack

| 영역 | 기술 |
|---|---|
| Infrastructure | Linux, Kubernetes, KubeVirt |
| Cluster & Deployment | kubeadm, CRI-O, Cilium, Helm, Argo CD |
| GPU & Development Platforms | HAMi, JupyterHub, VS Code Extension |
| Languages | Python, Go, Shell, TypeScript, C/C++ |

## 🎓 Background

- **숭실대학교 DCN 연구실 · 연구원**
  2024.06 – 현재

- **숭실대학교 전자정보공학부 IT융합전공 · 졸업**
  2024.02

## 📫 Connect

- Email: [taeuk.h@dcn.ac.kr](mailto:taeuk.h@dcn.ac.kr)
- GitHub: [@WoogiBoogi1129](https://github.com/WoogiBoogi1129)
