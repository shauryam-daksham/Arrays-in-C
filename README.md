# DSC_Exp-2
## Arrays

### Code:-


      #include <stdio.h>

      int main()
      {
          int i;
          int x[5] = {0, 14, 1, 7, 11};
          char y[] = "SAS";

          printf("%d\n",x[3]);
          printf("%s\n",y);
          scanf("%d",&x[0]);

          for(i = 0; i < 5; i++) {
              printf("\nArray element %d: %d", i, x[i]);
          }

          return 0;
      }


### Output:-

![image](https://user-images.githubusercontent.com/124967782/230787438-b9e1c194-d683-4368-91fa-d3f8fbf50f9f.png)
