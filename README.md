# -408-
6.2.7
int printVertices(MGraph G) {
	int K = 0;
	int Ocount = 0;
	int Icount = 0;
	//入度
	for (int i = 0; i < G->numVertices; i++) {
		for (int j = 0; j < G->numEges; j++) {
			Ocount += G->Edge[i][j];
		}
		for (int k = 0; k < G->numVertices; k++) {
			Icount += G->Edge[k][i];
			}
		if (Ocount > Icount) {
			cout << Ocount << " " << Icount;
			K++;
		}
		
	}
	return K;






	
}
