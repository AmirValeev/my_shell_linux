# MyShell-simulator-linux

Translator of the model language. The semantics of the model language is taken from Pascal.


To demonstrate the work of the translator, the following code was performed

```Pascal
program
{
    int w = 1, a = 2, b = 1, c;
    bool p = 12b, e = 0b, y = 1b;
    read(c);
    a=c;
    do {a=a*c; b=b+1; } while(1);
    /*ab = 1;*/
    write(a);
}
```
