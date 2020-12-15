# DiveEventCollector

DiveEventCollector는 이벤트 수집을 돕기위해 만든 패키지 입니다

# 설치
Xcode 메뉴에서 File > Swift Packages > Add Package Dependency를 선택후
`https://github.com/mike123789-dev/DiveEventCollector` 를 입력합니다


# 사용법

### life cycle
**SwiftUI App**

```swift
    let manager = AnalyticsManager(serverEngine: MongoDBEventEngine(),
                                   backupEngine: BackupEventEngine(),
                                   alertEngine: AlertEventEngine())

```

**UIKit AppDelegate**

> 자세한 사용법은 추가 예정입니다.


### 참여자
[강병민](https://github.com/mike123789-dev)
[류연수](https://github.com/yeonduing)
