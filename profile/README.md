<p align="center">
  <img width="360" src="https://github.com/terraform101/.github/blob/main/profile/terraform_cover.jpg">
</p>

<img height="32" width="32" src="https://cdn.jsdelivr.net/npm/simple-icons@v8/icons/terraform.svg" /> <img height="32" width="32" src="https://freesvg.org/img/Infinity-Symbol.png" /> <img height="32" width="32" src="https://img.icons8.com/external-smashingstocks-mixed-smashing-stocks/256/external-Code-database-and-data-technology-smashingstocks-mixed-smashing-stocks.png" />

# 테라폼으로 시작하는 IaC

> [HashiCorp Homepage](https://www.hashicorp.com/)  
> [Terraform Homepage](https://www.terraform.io/)  
> [Terraform Registry](https://registry.terraform.io/)  
> [Terraform Developer](https://developer.hashicorp.com/terraform)  

## 부록

> [함수 추가 설명(부록) 영상](https://www.youtube.com/watch?v=ejAwCK-gr0U&list=PLQUXE_kb6KOjUdhva880Ve2z51IzU1MYX&pp=gAQBiAQB)


## 책 소개

> 매년 게시되는 깃허브GitHub의 OCTOVERSE 보고서에서 2021~2023년 가장 빠르게 성장하는 언어로 측정된 HCL(HashiCorp Configuration Language, 56.1% 성장)은 테라폼의 인기와 더불어 `인프라 자동화를 위한 IaC`를 향한 관심을 반영한다. 대표적인 프로비저닝 도구인 테라폼은 인프라 환경을 생성하고 관리하는 데 목적이 있다. 이 책에서는 테라폼의 본질을 이해하고 문법을 익히는 것부터 시작한다. 뒤이어 사용자 간 협업, 팀간 협업, 조직 규모에서의 사용을 다룬다. 각 장의 구성은 상향식 접근 방법을 통해 테라폼을 사용하는 역량을 기르는 것을 목표로 한다.

## 책 구성과 깃허브 레포 안내

### 1부.

사용자가 테라폼을 다방면에 실용성 있게 사용할 수 있도록 테라폼 자체의 동작과 원리를 파악해 원하는 구성을 효율적으로 설계하고 의도한 동작이 발생하도록 안내한다. 

#### 1장. IaC와 테라폼

인프라 자동화의 흐름과 IaC가 출현한 배경을 확인하고, IaC의 가장 대표적인 도구인 테라폼의 특성과 목표에 대해 확인한다..

#### 2장. 테라폼 설치와 환경 구성

사용자가 테라폼을 처음 시작하기 위한 실행 환경을 구성하는  방법을 안내한다.

#### 3장. 기본 사용법 익히기

테라폼의 명령어와 코드적인 속성을 이해하는 내용이다. 각 명령어와 옵션이 적용될 상황에 대해 미리 습득하여, 향후 다수의 사용자가 서로의 코드를 리뷰하고 더 나은 작성법을 탐구하기 위해서 알아야 할 기본기를 익힌다.

- [terraform-basic](https://github.com/terraform101/terraform-basic)

#### 4장. 프로바이더

테라폼이 다수의 인프라 대상을 프로비저닝할 수 있게 하는 프로바이더에 대해 확인하고 대표적인 클라우드 프로바이더의 설정 방법을 확인한다.

#### 5장. State

State는 테라폼에서 가장 중요한 개념이다. 테라폼의 Stateful(상태가 있는) 속성을 부여하고 프로비저닝한 대상을 추적하도록 하는 State에 대해 설명한다.

#### 6장. 모듈

코드의 재사용성을 높여주는 모듈의 의미를 이해하고, 모듈의 구조적 특성을 파악하여 향후 설계단계에서의 기준을 확인한다.

- [terraform-module-repo](https://github.com/terraform101/terraform-module-repo)

<br>

### 2부

테라폼으로 프로비저닝을 하면서 사용 규모가 확장되는 각 단계별 모범 사례를 확인한다.

#### 7장. 협업

둘 이상의 작업자가 테라폼으로 협업하는 과정을 실습을 통해 확인한다. VCS를 사용하여 공유되는 코드와 State백엔드를 사용하는데 주의할 점과 주요 구성 요소를 살펴본다.

- [terraform-aws-collaboration](https://github.com/terraform101/terraform-aws-collaboration)

#### 8장. 워크플로

테라폼의 기본 워크플로를 단계별로 이해하고, 규모에 따른 테라폼으로 일하는 방식의 예시를 통해 워크플로를 설계하는 과정을 확인한다.

- [terraform-aws-github-action](https://github.com/terraform101/terraform-aws-github-action)
- [terraform-aws-tfc-workflow](https://github.com/terraform101/terraform-aws-tfc-workflow)
- [terraform-aws-ec2-test-module](https://github.com/terraform101/terraform-aws-ec2-test-module)

#### 9장. 인프라 운영 및 관리

테라폼으로 지속적으로 인프라를 관리하고 운영에서 테라폼이 사용되는 방안에 대해 설명하고 조직 규모에서 고려해야 하는 테라폼 개발과 운영의 프로세스에 대한 체계를 이해한다. 또한 LG유플러스의 사례를 통해 테라폼을 조직 차원에서 활용하기 위해 제공되는 셀프 서비스가 추구하는 목표와 방안을 살펴보고, 조직간 협업 프로세스 방식을 확인한다.

- [terraform-refactoring-and-modularity](https://github.com/terraform101/terraform-refactoring-and-modularity)

#### 10장. 생성형 AI와 테라폼

IaC의 이점에도 불구하고 학습 곡선과 조직 및 산업별 규정, 보안 표준을 준수해야 하는 복잡성으로 인해 클라우드나 IaC 도입 여정이 늦어질 수 있다. 인공지능의 발전으로 가능해진 생성형 AI를 사용하여 인프라 자동화와 관리 생산성을 향상시키는 방안을 확인한다.

- [terraform-and-generative-ai](https://github.com/terraform101/terraform-and-generative-ai)
