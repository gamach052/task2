### [Task 7 kyv](https://www.codewars.com/kata/5f0ed36164f2bc00283aed07)

You've just moved into a perfectly straight street with exactly n identical houses on either side of the road. Naturally, you would like to find out the house number of the people on the other side of the street.

### My solution

```Java
public class main {

class CodeWars {
public static long overTheRoad(long address, long n) {
long inv = 1 + n * 2;
return inv - address;
}
}
}
```

### Favourite solution

```Java
class CodeWars {
public static long overTheRoad(long address, long n) {

if (address%2 == 0){
long x = (n*2) - address;
return 1+x;
}
else {
long x = (n*2) - address;
return x+1;
}

}
}
```

I like this solution because I like it
