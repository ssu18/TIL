## 문자열
-------------------------
- 문자열에 사용되는 기본 풀이 및 메소드 정리.

### 1. 문자찾기 
- [정리](https://github.com/ssu18/TIL/blob/main/Inflearn/String/P1.md)
- toUpperCase()
- toLowerCase()
- toCharArray() <br><br>
### 2. 대소문자 변환
- [정리](https://github.com/ssu18/TIL/blob/main/Inflearn/String/P2.md)
- char배열의 정수형 연산 
- 아스키코드 (65~90 / 97~122)
- String 배열에 char형을 더했을 때
- isUpperCase()
- isLowerCase()<br><br>
### 3. 문장 속 단어
- [정리](https://github.com/ssu18/TIL/blob/main/Inflearn/String/P3.md)
- split()
- indexof()
- substring() <br><br>
### 4. 단어 뒤집기
- [정리](https://github.com/ssu18/TIL/blob/main/Inflearn/String/P4.md)
- 두개의 임시변수를 이용한 문자열 조절.
- StringBuilder
  - reverse()
  - toString()
- String.valueOf() <br><br>
### 5. 특정 문자 뒤집기
- [정리](https://github.com/ssu18/TIL/blob/main/Inflearn/String/P5.md)
- if/else로 경우의 수 나눌 때 최대한 간략히
- 두개의 임시변수를 이용해 index 선택
- Character.isAlphabetic() <br><br>
### 6. 중복문자제거
- [정리](https://github.com/ssu18/TIL/blob/main/Inflearn/String/P6.md)
- '\0' 사용과 주의 <br><br>
### 7. 회문 문자열
- [정리](https://github.com/ssu18/TIL/blob/main/Inflearn/String/P7.md)
- equals()
- equalsIgnoreCase() <br><br>
### 8. 유효한 팰린드롬
- [정리](https://github.com/ssu18/TIL/blob/main/Inflearn/String/P8.md)
- replaceAll() <br><br>
### 9. 숫자만 추출
- [정리](https://github.com/ssu18/TIL/blob/main/Inflearn/String/P9.md)
- replaceAll()
- Integer.parseInt()
- Character.isDigit() <br><br>
### 10. 가장 짧은 문자거리
- [정리](https://github.com/ssu18/TIL/blob/main/Inflearn/String/P9.md)
- 배열에서 특정 index ~ 각 index 최소거리 갱신하는 ps
- 단계별로 진행하는 습관 들여볼 것
- 예외처리로 얼타지 말기! <br><br>
### 11. 문자열 압축
- [정리](https://github.com/ssu18/TIL/blob/main/Inflearn/String/P9.md)
- 과연 진짜 2중 for문이 필요한가? (for문에 맞는 단계별 진행 하기)
- index관련 오류시 ""(공백) 추가하는 센스 <br><br>
### 12. 암호
- [정리](https://github.com/ssu18/TIL/blob/main/Inflearn/String/P9.md)
- 형변환을 너무 복잡하게 생각하지 말자.
- substring() 인자 2개와 1개 차이
- 지금 가장 필요한 것은 단계별 진행.