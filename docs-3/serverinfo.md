# 서버 정보

서버가 사용하는 소프트웨어 및 하드웨어 정보에 대해 알아봅니다.

### 하드웨어 사양

아래 하드웨어를 사용하는 전용 서버를 사용합니다.

| CPU  | 13세대 Intel® Core™ i5-13600K         |
| ---- | ----------------------------------- |
| RAM  | 64 GB (Samsung PC4-25600 32 GB \*2) |
| SSD  | 1 TB (P31)                          |
| 네트워크 | 1 Gbps                              |

### 소프트웨어 사양

아래 소프트웨어를 사용합니다.

<table data-header-hidden><thead><tr><th width="375"></th><th></th></tr></thead><tbody><tr><td>운영체제</td><td><a href="https://www.clearlinux.org/"><mark style="color:blue;">클리어 리눅스</mark></a></td></tr><tr><td>자바</td><td><a href="https://adoptium.net/"><mark style="color:blue;">Eclipse Temurin™</mark></a></td></tr><tr><td>서버 구동기</td><td><a href="https://purpurmc.org/"><mark style="color:blue;">PurPur</mark></a></td></tr></tbody></table>

### 자주 묻는 질문

#### 왜 전용 서버를 사용하나요?

호스팅을 사용하게 될 경우 VPS(가상 개인 서버 - 공유 코어, 공유 메모리 할당) 또는 VDS(가상 전용 서버 - 전용 코어, 전용 메모리 할당)를 사용할 수 있습니다. VPS는 가격이 저렴하나 느리고, VDS는 가격이 비쌉니다. 따라서 대부분의 서버는 비용상의 문제로 VPS를 사용해 서버를 구동합니다. 하지만 이는 아주 넓은 세계를 상시로 로드하고 있는 야생 서버에는 적합하지 않습니다. 만약 이 서버가 VPS를 사용하게 될 경우 서버가 심각하게 느려질 겁니다. 대안으로 VDS를 사용한다면 속도 문제는 해결될 수 있으나, 전용 서버를 직접 구동하는 것에 비해 비쌉니다. 이러한 이유로 전용 서버를 직접 구동하는 것이 더 경제적일 것이라는 결론 하에 전용 서버를 사용하고 있습니다.

#### 왜 소비자용 인텔 프로세서를 사용하나요?

싱글 코어 성능이 다른 프로세서에 비해 우월하기 때문입니다. 예시로, 오버클럭하지 않은 인텔 11세대 i9는 AMD의 라이젠 5000 시리즈에 비해 약 5\~10% 높은 싱글 코어 성능을 보이며, 비슷한 가격대의 워크스테인선용/서버용 프로세서 보다도 더 높은 싱글 코어 성능을 보입니다. 또한 소음 문제에서 자유로운 서버의 특성상 오버클럭이 가능한 소비자용 프로세서의 성능을 최대한으로 이끌어내 사용함으로써 더 높은 기대 성능을 고려할 수 있으므로 소비자용 인텔 프로세서를 사용하는 것입니다.

1. &#x20;[<mark style="color:blue;">UserBenchmark의 CPU 성능 비교 (i9 11900K vs. Ryzen 7 5900X)</mark>](https://cpu.userbenchmark.com/Compare/Intel-Core-i9-11900K-vs-AMD-Ryzen-9-5900X/4110vs4087)
2. &#x20;[<mark style="color:blue;">UserBenchmark의 CPU 성능 비교 (i9 11900K vs. i9 10900X)</mark>](https://cpu.userbenchmark.com/Compare/Intel-Core-i9-11900K-vs-Intel-Core-i9-10900X/4110vsm969950)
