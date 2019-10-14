# android-interview

## Software Enginnering
- lean 스타트 개발 방식이란?
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
- 무차별(DOS,DDOS) 공격
- side channel attack
- base64 인코딩을 왜하나요?
- 비대칭암호와에 대해서 설명해주세요
- 공인인증서는 어떤방식으로 인증을 하게되나요?
- 대칭방식과 비대칭방식의 장단점은 무엇인가요?

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
- 블럭, 넌블럭, 동기, 비동기에 대해서 설명

## Android
- UUID 는 무엇이고, 어떤 용도로 쓰이는가?
- 이미지 라이브러리인 Glide와 Picasso의 차이점은 무엇인가요?
- 안드로이드 메모리 누수관리는 어떻게 할것인가?
- Room과 Realm 비교해 보세요
- 4대 컴포넌트 (Activity, Service, BroadcastReceiver, ContentProvider)를 설명해 보세요
- 안드로이드 실행환경에 대해서 간단하게 설명하시오.
- 안드로이드는 다른 플랫폼에 비해 어떤 장점이 있는가?
- 인플레이션(inflation)이란 무엇인가요?
- 액티비티가 무엇이고 액티비티 생명주기는 어떻게되나요?
- application과 context에 대해서 설명해보세요
- task란 무엇인가요?
- 액티비티 하위 호환성에 대한 패키지 또는 라이브러리를 설명해보세요.
- Jetpack이란 무엇인가요? 
- AsyncTask를 써야한다면 반드시 구현해야되는 부분은 무엇인가요? 그리고 다른 비동기 스레드 처리방식과 비교하여 장단점은 무엇인가요?
- 액티비티 스택이 무엇인지 설명해주세요.
- png와 jpg, bmp의 차이에 대해서 설명해주세요.

### Activity & Component & Context
- activity 사이에서 data 전달 방법은 무엇이 있나요
- 잠깐 Background 전환된 사이에 Activity가 메모리 문제로 OS에 의해 죽었습니다. 해결방법은?
- ContentProvider은 언제 사용하나요?
- onPause와 onStop이 호출되는 시점의 차이는 무엇인가요?
- 안드로이드의 context는 무엇인가요?

### Thread & Communication
- 사이드 이펙트에 대해서 설명해주세요
- 데드락에 대해서 설명해주세요

### UI
- onMeasure와 onDraw의 역할는 무엇인가요?
- TouchEvent가 전달되는 순서를 설명해 보세요

## Kotlin
- Scope Functions의 종류와 사용 사례를 들어주세요
- 코틀린이 자바보다 장점은 무엇인가요?
- @JvmOverloads 어노테이션은 무엇인가요?
- @JvmField 어노테이션은 무엇인가요?
- let, run, with, apply, also 키워드에 대해서 설명해 보세요.
- 지연 초기화 기법 (lazy, lateinit)을 설명해 보세요.
- 확장함수란? 사용 예는 어떤 것이 있을까?
- inline 키워드는 어떤 역할을 하고 어떻때 사용하나요?
- infix 키워드는 어떤 역할을 하고 어떻때 사용하나요?
- operator 키워드는 어떤 역할을 하고 어떻때 사용하나요?
- sealed class의 특징과 사용법을 설명해 보세요
- kotlin과 java 의 inner class 차이를 설명해 보세요.
- internal 키워드는?

## RX
- concatMap, switchMap, flatMap의 차이는 무엇인가요?
- subject와 observable의 차이는 무엇인가요?
- flowable와 observable의 차이는 무엇인가요?
- 핫옵저버블과 콜드옵저버블은 어떤건가요?
- 구독 해지를 하려면 어떻게 해야하나요?
- 스케쥴러의 종류와 용도를 설명해보세요. 쓰레드의 개수는? (new Thread, Computation, IO, 트램펄린, 싱글 스레드 스케쥴러)
- disposable 관리는 어떻게 해야 하나?
- launch 와 runBlocking 의 차이는?
- 이미 비동기로 설계된 api 를 coroutine 으로 감싸는 방법은?
- RX에서 Observable사용후에 메모리 누수방지를 위해서 어떻게 해야할까요?
- CompositeDisposable에서 dispose()와 clear()의 차이는 무엇인가요?

## Build
- Gradle에서 implementation 과 api 의 차이를 설명해주세요.
- android build 속도를 높이기 위해 필요한 작업은 무엇이 있나요?
- D8, R8 은 무엇인가?
- 프로덕션, 테스트 앱을 분리/설치 하는 방법은?

## 테스트
- 테스트의 종류에 대해서 아는 대로 설명해주세요.
- Unit 테스트는 왜 하는가?
- 안드로이드 폴더 구조에서 AndroidTest 와 Test 폴더에 대해서 설명해주세요.
