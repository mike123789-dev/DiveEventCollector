# DiveEventCollector

DiveEventCollector는 이벤트 수집을 돕기위해 만든 패키지 입니다


# 사용범

## life cycle
**SwiftUI App**

```swift
    let manager = AnalyticsManager(serverEngine: MongoDBEventEngine(),
                                   backupEngine: BackupEventEngine(),
                                   alertEngine: AlertEventEngine())

```

**UIKit AppDelegate**


### 참여자
[강병민](https://github.com/mike123789-dev)
[류연수](https://github.com/yeonduing)
