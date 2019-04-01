# android-interview

## Software Enginnering
- lean 개발 방식이란?
- TDD란?
- DDD란?
- AB Test 란?
- Dynamic 프로그래밍은 무엇인가요?
- Concurrency 에 대해서 설명해 보세요
- Rest API 에 대해서 설명해 보세요.
- DI (dependency injection)
- git 에서 conflict 가 일어나는 원인과 해결책을 설명해 보세요
- git rebase 를 설명해 보세요.
- mvc, mvvm, mvp 패턴의 차이점을 설명해보세요.


### 보안
- md5, sha1, sha256
- 무차별 공격
- side channel attack
- base64 인코딩을 왜하나요?
- 비대칭암호와에 대해서 설명해주세요
- 공인인증서는 어떤방식으로 인증을 하게되나요?

## Java 일반
- 자바 메모리 구조
- LRU 알고리즘
- Weak Reference vs Soft Reference vs Strong Reference
- 가비지 컬렉터 란?
- set, list, map 의 차이와 용도
- hash 함수는 무엇인가요?
- hash 충돌에 대해서 설명하시고 해결책은?
- hashMap, treeMap, linkedHashMap 각각을 설명하시고 용도 차이를 비교해 보세요
- singleton 패턴을 설명해보세요
	- synchronized
	- double check
	- volatile
- CheckedException과 UncheckedException 차이와 용도는?
- java에서 static void main 에서 static을 붙이는 이유는?
- linkedList, arraylist 비교해 보세요
- deep copy, shallow copy 
- android sparseArray vs hashMap
- Arrays.sort는 어떤 알고리즘을 쓰는가?
- Serializable과 Parcelable의 차이는 무엇인가요?

## Android
- UUID 는 무엇이고, 어떤 용도로 쓰이는가?
- 이미지 라이브러리인 Glide와 Picasso의 차이점은 무엇인가요?
- 안드로이드 메모리 누수관리는 어떻게 할것인가?
- Room과 Realm 비교해 보세요
- 4대 컴포넌트 (Activity, Service, BroadcastReceiver, ContentProvider)를 설명해 보세요


### Activity & Component & Context
- activity 사이에서 data 전달 방법은 무엇이 있나요
- 잠깐 Background 전환된 사이에 Activity가 메모리 문제로 OS에 의해 죽었습니다. 해결방법은?
- ContentProvider은 언제 사용하나요?

### Thread & Communication

### UI
- onMeasure와 onDraw의 역할는 무엇인가요?
- TouchEvent가 전달되는 순서를 설명해 보세요

## Kotlin
- Scope Functions의 종류와 사용 사례를 들어주세요
- 코틀린이 자바보다 장점은 무엇인가요?

## RX
- concatMap, switchMap, flatMap의 차이는 무엇인가요?
- subject와 observable의 차이는 무엇인가요?
- flowable와 observable의 차이는 무엇인가요?
- 핫옵저버블과 콜드옵저버블은 어떤건가요?
- 구독 해지를 하려면 어떻게 해야하나요?
- 스케쥴러의 종류와 용도를 설명해보세요. 쓰레드의 개수는? (new Thread, Computation, IO, 트램펄린, 싱글 스레드 스케쥴러)

## Build
- Gradle에서 implementation 과 api 의 차이를 설명해주세요.
- android build 속도를 높이기 위해 필요한 작업은 무엇이 있나요?

## 테스트
- 테스트의 종류에 대해서 아는 대로 설명해주세요.
- Unit 테스트는 왜 하는가?
- 안드로이드 폴더 구조에서 AndroidTest 와 Test 폴더에 대해서 설명해주세요.
