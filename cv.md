# Tatiana Harlamova

### Contact details:
- phone: +375 (25) 617-91-14;  
- e-mail: ustinya88@gmail.com.  

### Goals:   
- development in the field of information technology, in particular - front-end;
- personal qualities: polite, helpful, hard-working.  

### Skills:  
- HTML Basic,  
- CSS Basic, 
- Javascript Basic,  
- Photoshop, CorelDraw.

### Code examples:
Find numbers which are divisible by given number:
```
function divisibleBy(numbers, divisor){
return numbers.filter((x) => !(x % divisor));
}
```
Incrementer:
```
function incrementer(nums) {
  return nums.map((item, index)=>{
    const num = item + ++index;
    return num < 10 ? num : num % 10;
  });
}
```