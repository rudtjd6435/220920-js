# 220920-js

## js 문제
* if 조건문
  * 사용자의 점수를 입력받되<br>100점이상 입력되면 __100점 이하로 입력해주세요__ 출력<br>80점 이상은 __상__<br>60점 이상은 __중__<br>그 이하는 __하__ 로 출력
  



 -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------




<html>
    <script>

//if 조건문

/*
사용자의 점수를 입력받되
100점이상 입력되면 100점 이하로 입력해주세요 출력
80점 이상은 상
60점 이상은 중
그 이하는 하 로 출력
*/

let score = prompt('점수를 입력해주세요.');


if (score>=100) {//참일 떄 실행
  alert('100점 이하로 입력해주세요')
} else if(score>80){
 alert('상')
} else if(score>60){
 alert('중')
} else{
 alert('하')
}

    </script>
</html>



220920

<<<<<<< HEAD
##집에서 공부함 
##학원에서 공부함

