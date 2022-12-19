REACT

JS에서 HTML로 보낼 수 있음. 기존에는 HTML에서 JS로의 연산만 가능함.

니코쌤이 쓰는 prettier 쓰면 코딩할때 매우매우매우매우 편해짐
setting 가서 default formatting > prettier 하고 format on save > 체크 해주면 코드 개간편해짐.

<script src="https://unpkg.com/react@17.0.2/umd/react.production.min.js"></script>
<script src="https://unpkg.com/react-dom@17.0.2/umd/react-dom.production.min.js"></script>

일단 React를 사용하려면 script로 react를 가져와야됨.
또한 JSX라는 걸 사용해서 JS에서 html element를 html문법처럼 만들수 있게하는 문법이 있음.
그걸 위해서 작성하는 script에 아래와같은 바벨주소를 보내줘야함.

<script src="https://unpkg.com/@babel/standalone/babel.min.js">
<script type="text/babel">
    여기다 JSX작성함. 
</script>
