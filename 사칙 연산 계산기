#include <stdio.h>

int main(void)

{
	
	int num1 = 0; // int 자료형 num1를 0으로 초기화 
	int num2 = 0; // int 자료형 num2를 0으로 초기화 
 	int value = 0; // int 자료형 value를 0으로 초기화 
	char a = 0; // char 자료형 a를 0으로 초기화
	 
	printf("수식을 입력해주세요 : "); 
	scanf("%d %c %d", &num1, &a, &num2); // scanf 함수를 이용하여 num1에 정수, a에 문자 한글자, num2에 정수 입력 
	
	
	switch(a){ //char a의 값에 따라, case (상황)를 설정 
	case '+' : //char a의 값이 +일 경우 + (더하기) 연산을 한다. 
		value = num1 + num2; //value의 값은 num1 + num2 
		printf("%d %c %d = %d", num1, a, num2, value);
		break;
	
	case '-' : //char a의 값이 -일 경우 - (빼기) 연산을 한다.
		value = num1 - num2; //value의 값은 num1 - num2 
		printf("%d %c %d = %d", num1, a, num2, value);
		break;
		
	case '*' : //char a의 값이 *일 경우 * (곱하기) 연산을 한다.
		value = num1 * num2; //value의 값은 num1 * num2
		printf("%d %c %d = %d", num1, a, num2, value);
		break;
	
	case '/' : //char a의 값이 /일 경우 /(나누기) 연산을 한다.
		value = num1 / num2; // value의 값은 num1 / num2
		printf("%d %c %d = %d", num1, a, num2, value);
		break; 
	
	default :
		printf("잘못된 값 계산할 수 없음"); 
		break;
	
	}
	
	return 0;
	
}
