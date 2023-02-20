# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

![Image of Luchadortocat](https://octodex.github.com/images/luchadortocat.png)

```
int main()
{
    int numArray[10];
    int arraySum = 0;
    float arrayAvg = 0;
    
    printf("Input the 10 numbers: \n");
    
    /* Recieves 10 int inputs and adds each elements to arraySum */
    for(int i = 0; i < 10; i++){
        printf("Number-%d : ", i + 1);
        scanf("%d", &numArray[i]);
        arraySum = arraySum + numArray[i];
    }
    
    arrayAvg = arraySum / 10.0; //Calulate average
    
    /*Outputs sum of the 10 number list and list average */
    printf("The sum of 10 no is: %d\n", arraySum);
    printf("The Average is: %f\n", arrayAvg);
    
    return 0;
}
```

- [ ] Turn on GitHub Pages
- [ ] Outline my outline
- [ ] Introduce myself to the world
