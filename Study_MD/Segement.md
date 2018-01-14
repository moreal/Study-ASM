# Segement

## BSS [DS]
초기화 된 변수들이 있는 구역이다.
```nasm
section.bss
```

## text [CS]
실제 코드들을 가지고 있는 구역이다.(명령어들 위치)  
global _start 를 초기화하는 것 부터 시작할 필요가 있다. (커널에게 프로그램의 실행이 어디부터 시작인지 알려준다)

## data [DS]
초기화 된 데이터들 혹은 상수들을 위한 구역이다. 그 데이터 들은 실행되는 동안 바뀌지 않는다.

## Stack
지역변수들이 사용하는 구역이다.

### 참고문서
https://www.tutorialspoint.com/assembly_programming/assembly_basic_syntax.htm
