# Dart JSON Practice 
 
 Flutter를 공부하면서 JSON 데이터를 어떻게 처리하는지 직접 실습해본 Dart 프로젝트입니다.  
 Dart에서 `Map`, `String`, `Class`를 서로 변환하며 JSON 직렬화와 역직렬화를 연습할 수 있도록 구성되어 있어요.
 
 ---
 
 
 ## Project Structure
 
 ```
 dart_json_practice/
 ├─ lib/
 │  └─ main.dart
 ├─ pubspec.yaml
 └─ README.md
 ```
 
 
 ## ✨ 프로젝트 소개
 
 이 저장소는 다음 내용을 포함한 JSON 실습을 위한 코드 예제들을 담고 있습니다:
 
 1. `Map<String, dynamic>` ↔ JSON 문자열
 2. Dart 클래스(User, Pet)를 사용한 JSON 변환
 3. 배열(List) 형태의 JSON 처리
 4. 중첩된 JSON 구조 예제 (Contact 포함)
 5. `fromJson`, `toJson` 메서드의 활용
 
 Dart의 `dart:convert` 라이브러리를 활용하여 `jsonEncode`, `jsonDecode`를 실습해보고,  
 클래스를 통해 타입 안정성을 갖춘 JSON 처리를 학습할 수 있습니다.
 
 ---
 
 ## 📌 실행 방법
 
 1. Dart SDK가 설치되어 있는지 확인하세요.
    → [Dart 설치 링크](https://dart.dev/get-dart)
 
 2. 저장소를 클론한 후 아래 명령어로 실행합니다:
 
 ```bash
 dart run lib/main.dart
 ```
 ---
 
 ## 📚 블로그에서 자세히 보기
 실습하며 배운 내용을 블로그에 자세히 정리해두었습니다.
 JSON 구조, 직렬화/역직렬화 개념, 실수했던 부분, 느낀 점까지 함께 정리했어요.
 아래 링크에서 전체 흐름을 따라가며 함께 공부해보세요!
 
 ## 🔗 블로그 포스팅:
 [👉 Flutter 트랙 TIL – 데이터 통신 기초와 JSON, Dart에서 배우는 JSON 활용법](https://grmeems.tistory.com/entry/Flutter-%ED%8A%B8%EB%9E%99-TIL-%EB%8D%B0%EC%9D%B4%ED%84%B0-%ED%86%B5%EC%8B%A0-%EA%B8%B0%EC%B4%88%EC%99%80-JSON-Dart%EC%97%90%EC%84%9C-%EB%B0%B0%EC%9A%B0%EB%8A%94-JSON-%ED%99%9C%EC%9A%A9%EB%B2%95)
 
 ---
 
 
 ## 🧠 배운 점 & 실수했던 부분
 JSON 루트가 {}뿐 아니라 []도 될 수 있다는 점
 
 List<dynamic>을 List<String>으로 변환할 땐 .from()을 꼭 써야 하는 점
 
 클래스 안에서 fromJson, toJson을 직접 구현해야 실수가 줄어든다는 점
 
 ---
 
 ## 🛠 사용 기술
 
 - VSCode + Dart CLI
 - dart:convert 라이브러리 (jsonEncode, jsonDecode)
 - Flutter 3.7
 - Dart
 - Cupertino-style Dialog
 - Git & GitHub
 
 ---
 
 ## 👨‍💻 개발자
 - GitHub: [Linayoo01](https://github.com/Linayoo01)
