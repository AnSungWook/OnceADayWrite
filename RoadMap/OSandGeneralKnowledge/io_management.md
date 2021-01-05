# I/O Management

- I/O 장치의 관리는 운영 체제에서 매우 중요한 부분이며, 매우 중요하고 다양하여 전체 I/O 하위 시스템이 운영체제에 할당 됨
- I/O 하위 시스템은 두가지 경향과 경쟁 해야함
  - 광범위한 장치에 대한 표준 인터페이스에 대한 인력, 새로 개발된 장치를 기존 시스템에 더 쉽게 추가 할 수 있게 하는것
  - 기존의 표준 인터페이스가 항상 적용되기 쉬운 것은 아닌 완전히 새로운 유형의 장치의 개발
  - 장치 드라이버는 OS에 연결하여 특정 장치의 범주를 처리할 수 있는 모듈임

##  I/O 하드웨어

- I/O 장치는 대략적으로 스토리지, 통신, 사용자 인터페이스 및 기타로 분류 가능
- 장치는 와이어 또는 공기를 통해 전송되는 신호를 통해 컴퓨터와 통신함
- 장치는 직렬 또는 병렬 포트와 같은 포트를 통해 컴퓨터와 연결
- 여러 장치를 연결하는 일반적인 와이어 세트를 버스라고 함
  - 버스에는 버스를 통해 전송할 수 있는 메시지 유형과 경합 문제를 해결하기 위한 절차에 대한 엄격한 프로토콜이 포함
  - PCI 버스, 확장 버스, SCSI 버스, 데이지 체인 버스
- 장치와 통신하는 또 다른 기술은 메모리 맵 I/O 임

- 폴링
- 인터럽트
- 직접 메모리 액세스

## 응용 프로그램 I/O 인터페이스

- 블록 및 문자 장치
- 네트워크 장치
- 시계 및 타이머
- 차단 및 비차단 I/O
- 벡터링 I/O

## 커널 I/O 하위 시스템

- 스케줄링
- 버퍼링
- 캐싱
- 스풀링 및 기기 예약
- 오류 처리
- I/O 보호

---

>출처

-[I/O OperatingSystems](https://www.cs.uic.edu/~jbell/CourseNotes/OperatingSystems/13_IOSystems.html)