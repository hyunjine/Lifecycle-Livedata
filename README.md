# Lifecycle-Livedata
lifecycle owner의 구분과 SingleLiveEvent의 한계점에 대한 문제점을 담은 예제 코드
```java
private fun initialize() {
        /**
         * 1. lifecycleOwner, 일반 livedata 사용 시                                    -> testA
         * 2. viewLifecycleOwner, 일반 livedata 사용 시                                -> testB
         * 3. viewLifecycleOwner, SingleLivedata 사용 시                              -> testC
         * 4. viewLifecycleOwner, SingleLivedata 사용 시 initialize에 list.add 추가    -> testD
         */

}
```
