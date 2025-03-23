# -408-
6.2.7
using namespace std;
#include <iostream>;
#define MaxSize 100
#include <string>
int IsExistEL(MGraph G) {
	//遍历每行，确定度==0或2的点有 cout个
	int i, j, cout, degree;
	cout = 0;
	for (i = 0, i < numVertisize; i++) {
		degree = 0;
		for (j = 0; j < numEdges; j++) {
			degree+=Edege[i][j]
		}
		if (degree % 2 == 1) {
			cout++
		}
	}
	if (cout == 0 || cout == 2)
		return 1;
	else
		return 0;



}




