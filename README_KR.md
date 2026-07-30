# 쿨스 박막 III-V on SiC 광반도체 플랫폼

[English](README.md) | [中文](README_ZH.md) | [특허 포트폴리오](PATENT_PORTFOLIO.md) | [공개 고지](PUBLIC_NOTICE.md)

## 광기능은 III-V가, 그 아래의 열·응력·기계·패키지는 SiC가 담당한다

**고가의 인듐포스파이드(InP)계 III-V 재료는 광기능이 필요한 수 마이크로미터 박막으로만 사용하고, 실리콘카바이드(SiC)계 플랫폼이 방열·기계 지지·열팽창 정합·광정렬·패키지 기능을 담당하는 구조입니다.**

기존에는 InP 벌크 웨이퍼가 에피 성장 템플릿, 광기능층, 기계적 지지체, 열전달 경로를 모두 담당했습니다. 쿨스 플랫폼은 이 역할을 분리합니다.

```text
광소자 / 전극 / 광도파로
────────────────────────
InP계 III-V 광기능 박막
(InP / InGaAs / InGaAsP / InAlGaAs / MQW / APD / SPAD)
────────────────────────
직접접합 또는 초박막 본딩 계면
────────────────────────
SiC계 방열·기계·패키지 플랫폼
(단결정 SiC / 박막 SiC / 다결정 SiC / RBSC)
```

---

## 1. 핵심 구조

| 구성 | 역할 |
|---|---|
| InP계 III-V 박막 | 발광, 변조, 검출, 도파, 다중양자우물 기능 |
| 본딩 계면 | 저온 결합, 낮은 계면 열저항, 선택적 전기·계면 조절 |
| SiC계 지지층 | 열확산, 기계 지지, 열팽창 정합, 패키지 베이스, 광정렬 기준면, 수직 비아 플랫폼 |

InP계 광기능 박막은 InP 단층에 한정되지 않고 InGaAs, InGaAsP, InAlGaAs, 다중양자우물(Multiple Quantum Well, MQW), 레이저 적층체, 애벌란치 광검출기(Avalanche Photodiode, APD), 단광자 애벌란치 검출기(Single-Photon Avalanche Diode, SPAD)를 포함할 수 있습니다.

---

## 2. 왜 InP 아래에 SiC인가

### 방열

InP의 열전도도는 약 68 W/m·K인 반면 고품질 단결정 SiC는 약 490 W/m·K에 도달할 수 있습니다. 광원·변조기·검출기에서 발생한 열이 짧은 경로로 SiC 지지층에 전달됩니다.

### 열팽창 정합

SiC와 InP의 열팽창계수는 각각 약 4.0 ppm/K와 4.6 ppm/K로 가깝습니다. InP-on-Si보다 본딩·냉각·열사이클 중 잔류응력과 박막 균열을 줄일 수 있습니다.

### 기계·패키지 통합

SiC 지지층은 단순 서브마운트가 아니라 다음 역할을 통합할 수 있습니다.

- 고강성 패키지 베이스
- 히트스프레더
- 광정렬 기준면
- 수직 광 인터커넥트(Vertical Optical Interconnect, VOI) 플랫폼
- 광 비아 또는 관통전극 형성 기반

---

## 3. 벌크 InP 소비에서 반복 도너 전사로

대표 공정은 다음과 같습니다.

```text
1. InP계 III-V 도너 또는 에피 적층체 준비
2. H/He 이온 주입으로 매몰 박리면 형성
3. SiC계 지지층과 저온 본딩
4. 박리면을 따라 III-V 박막 분리·전사
5. 박막 표면 마감 및 광소자 형성 또는 완성
6. 잔류 도너 재생·재사용
```

매 사이클에서 수 마이크로미터 이하의 기능층만 소비합니다. 전사 두께, 도너 표면 재생 손실 및 반복 횟수에 따라 벌크 기판 방식 대비 InP 원소재 사용량을 약 **1/100~1/300** 수준으로 줄이는 것을 목표로 합니다.

---

## 4. 본딩 계면

플랫폼은 특정 결합법에 한정되지 않습니다.

- 친수성 직접접합
- 플라즈마 표면활성접합
- 산화막 또는 질화막 매개 접합
- 금속 접합
- 벤조사이클로부텐(Benzocyclobutene, BCB) 접합
- 폴리에틸렌이민(Polyethyleneimine, PEI) 또는 에톡실화 폴리에틸렌이민(Ethoxylated Polyethyleneimine, PEIE)계 아민 분자층 매개 접합

핵심은 두꺼운 접착층이나 솔더층이 SiC의 방열 이점을 훼손하지 않도록 계면을 얇게 구성하는 것입니다.

---

## 5. SiC 지지층 변형

### 단결정 SiC

높은 열전도도, 균질성 및 후면 광입사가 필요한 응용에 적합합니다.

### 다른 캐리어 위 박막 SiC

실리콘 시모스 판독 집적회로(CMOS ROIC), 수직 광 인터커넥트 및 복합 광학 적층에 적합합니다.

### 다결정 SiC

전체 단결정 웨이퍼 없이도 고강성·고방열 핸들을 제공합니다.

### 반응결합 탄화규소(RBSC)

대면적·저원가·고강성 방열 핸들에 적합합니다. 잔류 실리콘, 기공, 다상구조가 존재하므로 균질한 후면 투과체로 일반화하지 않고, 필요시 개구부·단결정 SiC 윈도우·광 비아·측면 또는 전면 조사 경로를 별도로 둡니다.

---

## 6. 선택적 광열 후처리

광열 처리는 모플랫폼의 필수 구성이 아니라 선택적 확장입니다.

전면·후면·측면·광 비아·투명창을 통해 광을 입사하고, III-V 박막 내 선택흡수영역에서 국소 발열 피크를 형성할 수 있습니다.

대상 영역은 다음을 포함할 수 있습니다.

- 다중양자우물
- 도핑영역 및 자유캐리어 흡수영역
- 이온주입 손상영역과 결함준위
- 매몰 금속 흡수층
- 계면 반응층
- 광흡수 보조층

이를 통해 결함 회복, 도펀트 활성화, 파장 트리밍, 국부 양자우물 혼합을 수행하면서 열영향부를 좁게 제한할 수 있습니다.

---

## 7. 응용 플랫폼

### 자동차 라이다

1,500~1,600 nm 광원과 검출기를 동일 SiC 플랫폼에 집적하며, 비행시간(Time of Flight, ToF), 주파수변조연속파(Frequency-Modulated Continuous Wave, FMCW), 코히어런트 검출 및 광위상배열(Optical Phased Array, OPA) 구조로 확장할 수 있습니다.

### 코패키지드 옵틱스

SiC가 광엔진의 방열 핸들, 광정렬 기준면, 저열팽창 패키지 베이스가 되어 스위치 주문형 반도체(Application-Specific Integrated Circuit, ASIC) 인접 집적을 지원합니다.

### 단파장 적외선 카메라

InGaAs/InP 검출 적층체를 박막 SiC를 매개로 실리콘 CMOS ROIC 위에 전사하여 미세 화소·고균일 단파장 적외선(Short-Wavelength Infrared, SWIR) 어레이를 구현합니다.

### 양자광학·양자키분배

III-V 단광자 광원, SPAD 및 선택적 그래핀 기능을 열적으로 안정된 SiC 위에 통합합니다.

### 우주용 다중접합 태양전지

III-V 다중접합 박막 적층을 SiC가 지지하여 두꺼운 게르마늄 기판 사용을 줄이고, 그래핀·초박막 금속망·다른 투명도전층을 이용해 인듐주석산화물 의존도도 낮출 수 있습니다.

---

## 8. 본질적 차이

```text
기존: 벌크 III-V 기판이 구조체와 기능층을 모두 담당

쿨스: 반복 사용하는 III-V 도너가 기능 박막을 공급
      + SiC가 영구 방열·기계·패키지 플랫폼을 담당
```

이는 단순히 InP 칩을 SiC 서브마운트 위에 실장하는 기술이 아닙니다. **영구 기판 자체를 III-V에서 SiC로 전환하고, III-V는 기능 박막으로만 남기는 구조 전환**입니다.

---

## 9. 관련 쿨스 플랫폼

- [Thermally Active Photonic Substrate](https://github.com/jhcho9494/Cools_Thermally_Active_Photonic_Substrate) — 알루미나계 BOX와 열전도 핸들러
- [CPO Zero Thermal Budget Bonding](https://github.com/jhcho9494/Cools_CPO_Zero_Thermal_Budget_Bonding) — 저열예산 이종접합
- [Transmissive Self-Aligned Annealing](https://github.com/jhcho9494/Cools_Transmissive_Self_Aligned_Annealing) — 저흡수 경로를 이용한 국부 광처리
- [Package-Substrate-Less SystemBoard](https://github.com/jhcho9494/Cools_Package_Substrate_Less_SystemBoard) — 전사 미세배선과 패키지기판 제거

통합 시 다음 전체 스택을 구성할 수 있습니다.

```text
InP계 능동 광기능층
+ 알루미나계 광학·열 BOX
+ SiC/RBSC 열활성 핸들러
+ 전사형 전기·광 재배선 오버레이
```

---

## 10. 공동개발 범위

- InP 도너 준비·재생·반복 사용
- 이온컷 및 대체 박막 분리 공정
- 저온 III-V/SiC 본딩
- 계면 열저항·CTE·열사이클 신뢰성
- LiDAR 및 CPO 광엔진
- SWIR 검출기-CMOS 통합
- 양자광 집적
- 우주용 다중접합 적층

본 저장소는 공개 가능한 시스템 아키텍처를 설명합니다. 세부 계면 처리 조건, 도너 회수 조건, 소자 레이아웃, 공정 창 및 신뢰성 데이터는 별도의 공동개발·라이선스 협의 대상입니다.

---

## 발명자 및 연락

**조진현 / Jinhyun Cho**  
Cools, Republic of Korea

공동개발, 기술검증 및 라이선스 협의는 저장소 소유자 프로필을 통해 연락해 주십시오.

---

© 2026 Cools. 특허권 및 관련 권리 유보. [PUBLIC_NOTICE.md](PUBLIC_NOTICE.md) 참조.