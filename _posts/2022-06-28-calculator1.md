---
layout: single
title: "C project1 - 두 숫자의 사칙연산"
categories:
  - C project
---

두 숫자의 사칙연산
```c
#include <stdio.h>

void main()
{
	float a, b;
	char i;
	
	printf("연산자를 입력하세요: ");
	scanf_s("%c", &i);
	printf("첫번째 숫자를 입력하세요: ");
	scanf_s("%f", &a);
	printf("두번째 숫자를 입력하세요: ");
	scanf_s("%f", &b);
	
	
	switch (i)
	{
	case '+':
		printf("%f + %f = %f", a, b, a+b);
		break;
	case '-':
		printf("%f - %f = %f", a, b, a-b);
		break;
	case '*':
		printf("%f * %f = %f", a, b, a*b);
		break;
	case '/':
		printf("%f / %f = %f", a, b, a/b);
		break;
	}
}
```
