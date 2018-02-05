#include<stdio.h>//     #->preprocessor, io->for i/o
#include<stdlib.h>//   for main()
int main()
{
	printf("Hello World!\n");
	printf("%d is greater than %d\n",5,4);/*   %d is a placeholder which tells about the data
	                                        type*/
	printf("single char-->%c\n",'m');//      single char must be in ''
	
	printf("%d \n",213124125553);
	printf("%ld \n",43340034430);
	printf("%f \n",3.4);
	printf("%lf \n",34.23459989839);
	printf("%c \n",'a');
	printf("%s \n","hello world!");
	printf("%x\n",16);// hex
	
	puts("this is my c program");
	return 0;// for executing the fuction succesfully
}
