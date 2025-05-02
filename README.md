# Libft

42 Ecole에서 진행된 Born2beRoot 과제입니다. Debian 서버 설정 및 VirtualBox를 이용한 서버 구축 과정을 담고 있습니다.

## 목차

1.  [프로젝트 목표](#프로젝트-목표)
2.  [주요 기능](#주요-기능)
    * 2.1. [Part 1: Libc Functions](#part-1-libc-functions)
    * 2.2. [Part 2: Additional Functions](#part-2-additional-functions)
    * 2.3. [Bonus Functions](#bonus-functions)
3.  [사용 방법](#사용-방법)
4.  [기술 스택](#기술-스택)
5.  [참고 자료](#참고-자료)

## 프로젝트 목표

이 프로젝트의 목표는 C 표준 라이브러리(libc)의 일부 함수들을 재구현하고, </br>
추가적으로 유용한 함수들을 개발하여 C 프로그래밍에 대한 이해도를 높이는 것입니다. </br>
특히, 메모리 관리ㆍ문자열 처리ㆍ알고리즘 구현 능력의 향상을 꾀합니다.

## 주요 기능

Libft는 크게 두 부분으로 구성되어 있습니다.

### Part 1: Libc Functions

C 표준 라이브러리의 함수들을 재구현한 함수들입니다.
함수의 이름은 원래 함수 이름에 `ft_` 접두사를 붙여서 사용합니다.

* `ft_isalpha`
* `ft_isdigit`
* `ft_isalnum`
* `ft_isascii`
* `ft_isprint`
* `ft_strlen`
* `ft_memset`
* `ft_bzero`
* `ft_memcpy`
* `ft_memmove`
* `ft_strlcpy`
* `ft_strlcat`
* `ft_strchr`
* `ft_strrchr`
* `ft_strncmp`
* `ft_memchr`
* `ft_memcmp`
* `ft_strnstr`
* `ft_atoi`
* `ft_calloc`
* `ft_strdup`

### Part 2: Additional Functions

C 표준 라이브러리에는 없지만 유용한 함수들, 또는 다른 형태로 존재하는 함수들입니다.
* `ft_substr`
* `ft_strjoin`
* `ft_strtrim`
* `ft_split`
* `ft_itoa`
* `ft_strmapi`
* `ft_striteri`
* `ft_putchar_fd`
* `ft_putstr_fd`
* `ft_putendl_fd`
* `ft_putnbr_fd`

### Bonus Functions

연결 리스트를 다루는 함수들입니다.

* `ft_lstnew`
* `ft_lstadd_front`
* `ft_lstsize`
* `ft_lstlast`
* `ft_lstadd_back`
* `ft_lstdelone`
* `ft_lstclear`
* `ft_lstiter`
* `ft_lstmap`

## 사용 방법

1.  저장소를 클론합니다.

    ```bash
    git clone https://github.com/Function-m/Ecole42-Libft.git
    cd libft
    ```

2.  Libft 디렉터리 내부로 이동해서 Makefile을 사용하여 라이브러리를 컴파일합니다.

    ```bash
    make
    ```

3.  생성된 `libft.a` 파일을 여러분의 프로젝트에 링크하여 사용합니다.

## 기술 스택

* C
* Makefile

## 참고 자료

* [프로젝트 명세](subject.pdf)
