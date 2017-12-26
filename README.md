# A1065528_HW01
大學入門_作業4

#include <stdio.h>
#include <stdlib.h>

int main()
{
	int a=3;
	float b=5.5;

	printf("%d\n",b+a);
	printf("%d\n",b-a);
	printf("%d\n",b*a);
	printf("%d\n",b/a);//%d輸出結果是錯誤的，不是0就是很大的數字
	
	printf("%f\n",b+a);
	printf("%f\n",b-a);
	printf("%f\n",b*a);
	printf("%f\n",b/a);//%f輸出結果是正確的

	//我認為是因為int和float做運算之後，會被轉換成float，而float用%d輸出會因為轉換問題而出現0或很大的數字，用%f就不會有問題，是正確的答案
	//參考網址:https://zhidao.baidu.com/question/32943314.html	http://blog.sina.com.cn/s/blog_97b4973a0101j9eo.html

}
