Insertion Sort Projesi
www.patika.dev

[22,27,16,2,18,6]       n

1.  [2,27,16,22,18,6]   (n-1);
[2,6,16,22,18,27]   (n-2);
[2,6,16,18,22,27] : (n-3) : dizinin son hali
    
2.  n.(n+1)/2 => n^2+n /2 => buradaki dominant faktör n^2 olduğu için Big-O notation şöyledir: O(n^2);

3.  Time complexity: 
Dizinin son hali: [2,6,16,18,22,27] ;

4.  Burada aradığımız sayının (18) ortada olması average case kapsamındadır.
      
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı:
Adım 1: [2,3,5,8,7,9,4,15,6];
Adım 2: [2,3,4,8,7,9,5,15,6];
Adım 3: [2,3,4,5,7,9,8,15,6];
Adım 4: [2,3,4,5,6,9,8,15,7].
