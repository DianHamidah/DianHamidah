const number = [1,2,3,4,5,];
function printMultiplesThenSum(item) {
 for (let i = 0; i< items.length; i++) { // 0(n)
  for(let j = 0; j < items.length; j++) { // 0 (n)
   console.log(items[i]);//0(1)
  }
 }
 const sum = items.reduce((acc, item)=> { // 0(n)
   return acc += item; // 0(1)
 }, 0);
  return sum; // 0(1)
 }
