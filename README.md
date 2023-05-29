#include <stdio.h>

int main (){
	int n, m , k;
	scanf("%d%d%d", &n, &m, &k);
	int a[n];
	for( int i = 0 ; i < n ; i++) scanf("%d", &a[i]);
	int cnt = 0 ;
	for( int i = 0 ; i < n ; i++){
		if( a[i] % m ==0 && a[i] % k != 0){
			 cnt++;
		}
	}
	printf("%d", cnt);
}

