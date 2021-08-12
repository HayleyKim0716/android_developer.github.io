---
title: "Kotlin Bytecode 보기"
data: 2021-08-12 09:28:00
categories: short notes
---
Kotlin 은 Java Virtual Machie(JVM) 에서 동작하기 때문에 한 프로젝트에서 Kotlin 과 Java 혼용이 가능하다.
Kotlin 코드는 JVM bytecode 로 compile 하고 Java 코드로 decompile 하기 때문에 Kotlin 의 문법을 명확히 이해하기 위해 종종 변환된 Java 코드를 보곤 한다.
Android Studio 에서 Kotlin 파일을 Java 로 변환된 파일로 볼 수 있는 방법은 아주 간단하다.

1. Tools > Kotlin > Show Kotlin Bytecode 로 이동
2. 'Decompile' 버튼 클릭
