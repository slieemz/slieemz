int f3(char *a,char *b,char *c,char *n){
    int c1=0;
    if (*n==*a){
        c1+=1;
    }
    if (*n==*b){
        c1+=1;
    }
    if (*n==*c){
        c1+=1;
    }
    return c1;
}
