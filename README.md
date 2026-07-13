
### Kubernetes Network Lab

Kubernetes와 ArgoCD를 기반으로 네트워크 테스트 환경을
선언적으로 배포하고 관리하는 개인 클러스터입니다.

GitHub에 저장된 Kubernetes Manifest를 수정하면, Argo CD가 변경 사항을 감지하여 자동 또는 수동 승인 방식으로 Kubernetes 클러스터에 동기화합니다

<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/8adc9b63-8532-4108-a33c-1fd1cb0a6afc" />


- DNS Server : 내부(개인 사설 네트워크) DNS 용 서버 (https://github.com/zpzg333/my-k8s-dns)
- MetalLB: K8S Service IP 노출(External IP) (https://github.com/zpzg333/K8S-MetalLB)
- ContainerLAB: 컨테이너 형 가상화 랩 (https://github.com/zpzg333/C9S-containerLAB)
- network automation service: Job 형태의 ansible & Python 컨테이너 (ansible & python) (https://github.com/zpzg333/Ansible)
- argocd : GitOps 기반 kubernetes 관리 (https://github.com/zpzg333/my-argocd)
- monitor : grafana / prometheus / exporter (https://github.com/zpzg333/my-monitor-grafana-prometheus-)

---

### Public LLM Wiki

Hermes (GPT Agent) + Claude Code 
LLM Wiki를 구현하여 개인 비서 역할을 수행하고 업무에 활용

(https://github.com/zpzg333/work-llm-automation)

