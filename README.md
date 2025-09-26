# How to connect OAC(Oracle Analytics Cloud) on OCI
How to set up the configuration for OAC

## 1. 설치 환경
오라클 클라우드(OCI) VM 환경  
<img width="2742" height="1456" alt="image" src="https://github.com/user-attachments/assets/78e1d9b7-5072-4ab0-9bb3-2e0cdf8721b6" />  

  
<img width="2060" height="1180" alt="image" src="https://github.com/user-attachments/assets/5096d4a6-0217-4cfb-87a0-d5187c41212e" />  


<img width="2524" height="1154" alt="image" src="https://github.com/user-attachments/assets/2f6b158a-dc42-4ffe-9d2e-021cb4ce7102" />  


<img width="2444" height="1436" alt="image" src="https://github.com/user-attachments/assets/b73044bf-cabc-4f30-be1b-e1b56fa26c1a" />  







OS : OL 8 - 현재는 리눅스 8 버전이 지원 버전입니다.  
OCI VM은 이미 생성했다고 가정합니다.  
(compartment를 mysql ai를 위한 것으로 새로 만들어주세요. 그리고 시큐리티 rule 에 8000, 8080, 8443 을 추가해주면 됩니다.

  
## Object Store에서 rpm tar 및 cert tar 파일을 다운로드
```
mkdir mysqlairpms  
