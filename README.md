# Q.TwoNumberInputAndOutputFirstNumberMulBySecondNumber


## *정수 두개를 입력받아 첫 번째 수를 두 번째 수의 횟수만큼 곱한 값을 반환하는 함수*

````
func inputTwoNum(num: Int, num2: Int)->Int{

var result: Int = 0

for _ in 1 ... num2 {
    result *= num
}

return result
}

inputTwoNum(num: 5 , num2: 5)
````

````
func repeatFn(num: Int ,num2: Int) -> Int{
    var sum = 0
    for _ in 0...num2 {
        sum = num * num2
    }
    return sum
}
print(repeatFn(num: 2,num2:2))
````
