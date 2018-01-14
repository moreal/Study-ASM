# Assembly Language skill

## Comment
**;** 을 이용해서 주석처리를 할 수 있다. (이것은 다른 곳에서도 적용되는 곳이 있더라 ini 라거나..)  
```nasm
add eax, ebx ;  this program is mine :)
```

## Syntax
[instruction] [operands] [;comment]  
명령어는 mnemonic이라고도 하는 모양이다.

## Compile (NASM)
### Options
#### -f
ASM lang의 확장자 명은 asm이다.  
asm을 compile 할때는 다음과 같은 명령어를 사용한다.  
```command
nasm -f elf hello.asm
```
만약 파일명이 hello.asm이면 hello.o로 출력이 된다.  

#### -l
source_code의 list를 생성해 준다.
```command
nasm -f elf hello.asm -l myfile.lst
```

**ld** 는 GNU 링커의 이름이다. 이 링커로 많은 파일들을 링킹 하여 하나의 프로그램 파일로 출력할 수 있다.

ld의 기본 형식은 다음과 같다.
```linux
ld
```
