# homework 1 
## 2.61
### A
    !(~x)
### B
    !x
### C
    !(~(0xFFFFFF00 | x))
### D
    !(x & 0xFF000000)
## 2.62
    int int_shifts_are_arithmetic()
    {
      return !(~(-1 >> ( 8 * sizeof(int)));
    }
## 2.65
    int odd_ones(unsigned x)
    {
        x ^= ( x >> 16 );
        x ^= ( x >> 8 );
        x ^= ( x >> 4 );
        x ^= ( x >> 2 );
        x ^= ( x >> 1 );
        return x & 1;
    }
    
