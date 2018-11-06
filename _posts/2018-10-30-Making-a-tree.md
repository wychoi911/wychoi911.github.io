# Making-a-tree.md

## 트리 만들기

	-n = 30
	-print('\n'.join(' '*(n-1-i)+'*'*(1+2*i)+' '*(n-1-i) for i in range(n)))
	-print('\n'.join(' '*int(n*0.85)+'*'*int(n*0.3) for i in range(int(n/4)))) #나무줄기

