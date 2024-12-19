## Final Project Dataset

VPC Flow Log에서 생성된 네트워크 트래픽을 수집한 데이터 셋입니다.


### Dataset Structure

아래는 데이터 셋에 대한 구조 설명입니다.

`16` : 날짜를 의미함, 12월 16일에 수집 된 데이터셋
`533267253556_vpcflowlogs_ap-northeast-2_fl-0282c7ec20b408a58_20241216T0815Z_532515b6.log.gz` : log가 들어있는 gz 파일
`533267253556_vpcflowlogs_ap-northeast-2_fl-0282c7ec20b408a58_20241216T0815Z_532515b6.log` : 실제 log 파일
```
├── 16
│   ├── 533267253556_vpcflowlogs_ap-northeast-2_fl-0282c7ec20b408a58_20241216T0815Z_532515b6.log.gz
│   │   └── 533267253556_vpcflowlogs_ap-northeast-2_fl-0282c7ec20b408a58_20241216T0815Z_532515b6.log
│   ├── 533267253556_vpcflowlogs_ap-northeast-2_fl-0282c7ec20b408a58_20241216T0820Z_533515b6.log.gz
│   │   └── 533267253556_vpcflowlogs_ap-northeast-2_fl-0282c7ec20b408a58_20241216T0820Z_533515b6.log
│
├── 17
...
```
