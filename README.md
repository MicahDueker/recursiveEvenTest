# recursiveEvenTest

var isEven=function(num,num2){
  while (num2==undefined) num2==num;
  if (num==0)
    return "true";
  else if ((num==1)||(num==-1))
    return "false";
  else return (isEven(num-2,num2)||test(num+2,num2));
  }
