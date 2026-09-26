# vmpu73

**VMware(Broadcom) TAM.** 랩에서 실측한 것만 기록하고, 현장에서 바로 찾아 쓰도록 **대주제 › 소주제**로 체계 분류한다.
통합 열람은 **5999.lim.lab**(로그인 후 그룹 › 제품/도메인 › 패싯 계층으로 탐색, 본문은 지연 로드).

> 🔒 = 비공개(소유자 전용). 방문자용 공개 툴킷은 맨 아래 **Toolkits**.

## 📚 현장 지식베이스 — 찾아 쓰는 레퍼런스

### 🔒 vmware-field-kb — VMware 전 제품
12제품 × **6패싯**(제품마다 찾는 자리가 같다):

| 대주제 | 소주제 |
|---|---|
| **제품(12)** | vSphere/ESXi · vCenter · vSAN · NSX · Avi · Aria Operations(vROps) · Operations for Logs(vRLI) · Operations for Networks(vRNI) · VKS/Supervisor · Private AI · vDefend · Aria Automation |
| **패싯(6)** | CLI 명령 · API · 로그(종류·경로·키워드) · 트러블슈팅·Breakfix · GUI 절차 · 이슈·KB |

\+ **INDEX** — 증상·에러문구·API로 바로 찾는 교차색인 · 주간 자동 갱신(check_refs 검증 포함)

### 🔒 tech-field-kb — 기술 전 영역
16도메인 × **6패싯**(명령 · API/SDK · 개념 · 트러블슈팅 · 예제 · 학습경로):

| 대주제 | 소주제(도메인) |
|---|---|
| **클라우드·데브옵스** | AWS · Azure · Kubernetes · Docker · Terraform · Ansible · Linux |
| **개발·언어** | Python · JavaScript · Java/Spring Boot · Shell · 웹 서비스 |
| **네트워크·벤더** | Cisco · F5 BIG-IP · Fortinet · Wireshark |

### 🔒 enterprise-services-kb — 기업 서비스 총백서
포트·프로토콜을 인프라 관점으로 정리한 27편(인증·디렉터리 · 네트워크 서비스 · 앱/API/데이터 · 업종 로직 · LB/방화벽)

## 🎓 학습 커리큘럼
- 🔒 **study-hub** — 투자 · 영어 · **AI 활용** (주차별 강의, 매주 갱신)
- 🔒 **vsan-mastery** · **mastery-48w** — vSAN 16주 · 48주 전문가 로드맵(심화)

## 🧪 랩 기록 🔒
limlab-vcf911(VCF 9.1.1 nested) · limlab-k8s-web(kubeadm 웹클러스터) · lab-config(인벤토리) · vrni-adoption-kit

---

## 📦 Toolkits (public)

| | |
|---|---|
| **[nsx-collect-toolkit](https://github.com/vmpu73/nsx-collect-toolkit)** | On-box packet capture and state collection for NSX Edge and ESXi. Nothing is installed on the target. |
| **[avi-migration-kit](https://github.com/vmpu73/avi-migration-kit)** | NSX-T native LB → Avi (NSX ALB): what the ACT conversion tool does and does not do, and how to run both load balancers in parallel behind GSLB while traffic shifts gradually. |
| **[esxi-numa-diag](https://github.com/vmpu73/esxi-numa-diag)** | Read-only NUMA scheduler diagnostics. Locality migration rate against memory locality, so you can tell whether `Numa.LocalityWeightActionAffinity` is worth touching. |

Browse by topic: [`knowledge-base`](https://github.com/vmpu73?tab=repositories&q=topic%3Aknowledge-base) ·
[`toolkit`](https://github.com/vmpu73?tab=repositories&q=topic%3Atoolkit) ·
[`lab-record`](https://github.com/vmpu73?tab=repositories&q=topic%3Alab-record) ·
[`nsx`](https://github.com/vmpu73?tab=repositories&q=topic%3Ansx) ·
[`esxi`](https://github.com/vmpu73?tab=repositories&q=topic%3Aesxi)

---
_Everything verified against real equipment before it was written. Lab records and internal knowledge bases are kept private._
