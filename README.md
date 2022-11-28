# 25.-odev

// say�y� 10 ile �arp�p 8 ile toplayan fonksiyon

#include<stdio.h>
int carp(int);

int main(void)
{
	int x;
	printf("sayi gir:");
	scanf("%d" , &x);
	
	printf("sonuc: %d" , carp(x));
	
	return 0;
}

int carp(int x)
{
	return x*10+8;
}
