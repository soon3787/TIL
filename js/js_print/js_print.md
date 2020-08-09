# JS 출력
## window.alert() 메소드
자바스크립트에서 가장 간단하게 데이터를 출력할 수 있는 방법은 window.alert() 메소드를 이용하는 것입니다.
window.alert() 메소드는 브라우저와는 별도의 대화 상자를 띄워 사용자에게 데이터를 전달해 줍니다.
```
예) 
<script>
    function alertDialogBox() {
        alert("확인을 누를 때까지 다른 작업을 할 수 없어요!");
    }

</script>
```

## HTML DOM 요소를 이용한 innerHTML 프로퍼티
document 객체의 getElementByID()나 getElementsByTagName() 등의 메소드를 사용하여 HTML 요소를 선택합니다.
그리고서 innerHTML 프로퍼티를 이용하면 선택된 HTML 요소의 내용(content)이나 속성(attribute)값 등을 손쉽게 변경할 수 있습니다.
```
예)
<script>
    var str = document.getElementById("text");
    str.innerHTML = "이 문장으로 바뀌었습니다!";
</script>
```

## document.write() 메소드
document.write() 메소드는 웹 페이지가 로딩될 때 실행되면, 웹 페이지에 가장 먼저 데이터를 출력합니다.
따라서 document.write() 메소드는 대부분 테스트나 디버깅을 위해 사용됩니다.
```
예)
<script>
    document.write(4 * 5);
</script>
```
## console.log() 메소드
console.log() 메소드는 웹 브라우저의 콘솔을 통해 데이터를 출력해 줍니다.
대부분의 주요 웹 브라우저에서는 F12를 누른 후, 메뉴에서 콘솔을 클릭하면 콘솔 화면을 사용할 수 있습니다.
이러한 콘솔 화면을 통한 데이터의 출력은 좀 더 자세한 사항까지 출력되므로, 디버깅하는데 많은 도움을 줍니다.
```
예)
<p>F12를 눌러서 콘솔 화면을 열면 결과를 확인할 수 있습니다.</p>
<script>
    console.log(4 * 5);
</script>
```
