#include<unistd.h>
#include<stdio.h>

int main(){
        int pid;
        pid = fork();
        if(pid == 0){
                printf("I am child");
        }
        else if(pid > 0){
                printf("I am parent");
        }
        return 0;
}
