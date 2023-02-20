<h1>반응형 웹디자인&웹퍼블리셔<br>양성과정 버전기록</h1>
<h2>23.02.13 시작 - HTML</h2>
<p>ex) 코드연습을 위한 타이핑</p>
<p>H1~H6,p,br,inline,block</p>
<p>H1~H3은 검색 키워드로 활용 가능하다. H4~H6 꼭 필요한 경우만 이용하거나 권장안함</p>
<p>block과 inline태그는 의미에 맞게 외부/내부 구조로 구성해서 사용해야 한다.(의미 중첩되지 않도록)</p>
<hr>
<h2>23.02.14_html_문서태그+네비게이션 개념</h2>
<p>hr,em,strong,del,sub,sup,adress,blockquote,code,q,s,&l &g t;</p>
<p>gnb,lnb,snb,fnb,Breadcrumbs</p>
<hr>
<h2>23.02.15_html_순차/비순차 목록태그</h2>
<p>오늘의 태그 ol(순서에 관계있는 순차목록태그),ul(순서에 관계없는 비순차목록태그)</p>
<p>ol,ul(순차태그)안에는 li(목록태그)만 들어올수있다.</p>
<p><strong>주의사항</strong> ol 혹은 ul -&gt li만 이루어지며 strong or em태그와 같은 강조나 다른것등을 나타내는 태그를 쓸시에는 li(목록태그)안에 쓸수있다.</p>
<ul>
<li>순서가 없는태그</li>
<li>ol태그와 헷갈리지 말것</li>
</ul>
<ol>
<li>순서가 있는태그</li>
<li>ul태그와 헷갈리지 말것</li>
</ol>
또한 순차태그는 다중으로 둘수있는데 ul(비순차 목록태그)를 작성하고 li(목록태그)안에 ol(순차 목록태그)를 넣거나 그 반대의 경우로 하는등 다중으로 작성이 가능하다.
<br>
정의형 목록태그 (dl,dt,dd)
dl:기본 틀 dt:제목 dd:내용
기본 구조는 dl태그안에 dt,dd가 들어가는 구조로 dt1개를 쓸때마다 dd1개 혹은 여러개가 필요하다. dt가 1개일경우 dd가 여러개여도 무관하지만
dt는 여러개가될 수 없다. dt를 1개이상 쓸 경우 반드시 dd가 1개이상 필요하며 dt가 2개일경우엔 dd도 2개 혹은 그 이상이 필요하다.
<dl>
  <dt>정의형 목록 제목</dt>
  <dd>정의형 목록 내용</dd>

  <dt>정의형 목록 제목</dt>
  <dd>정의형 목록 내용</dd>
  <dd>정의형 목록 내용</dd>

  <dt>정의형 목록 제목</dt>
  <dd>정의형 목록 내용</dd>
  <dt>정의형 목록 제목</dt>
  <dd>정의형 목록 내용</dd>

위와같이 dt와 dd의 구조를 참고해 보도록하자.
  </dl>
  <br>
<div class="study">
  <h2>23.02.16-html-시맨틱태크,그룹태그</h2>
<dl>
  <dt>레이아웃 태그</dt>
  <dd>div는 2개이상의 인라인혹은 블록요소를 묶어주는 그룹태그 ex)포토샵으로 따지면 그룹기능이거나 피그마에서도 그룹기능인듯하다.</dd>
  <dd>span은 2개이상의 인라인 요소만 묶을수있다.</dd>
  <dd>시맨틱는 html5부터 생긴 의미가 있는 태그를 의미한다.(사실 잘 모르겠다.)</dd>
  <dd>연습이 많이 필요한듯하다. 이제 이해하기 빡쌔진거같다.</dd>
  <dt>class태그</dt>
  <dd>class태그는 모든태그들에 이름을 부여할수있는 태그이다. 이것도 잘 모르겠다.</dd>
</div>
</dl>
<br>
<h2>23.02.17</h2>
<p>사실 기억이 잘 나지않는다 집에가서 복습을 꼭다시 해봐야 조금 알것같다.</p>
<br>
<h2>23.02.20-Table</h2>
<table>
  <thead>
    <tr>
      <th>구분</th>
      <th>태그명</th>
      <th>의미</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="3">block</td>
      <td>&lttr&gt</td>
      <td>가로행 태그</td>
    </tr>
        <tr>
      <!--<td></td>--!>
      <td>&lttd&gt</td>
      <td>내용(열)태그</td>
    </tr>
        <tr>
      <!--<td></td>--!>
      <td>&ltth&gt</td>
      <td>제목(열)태그</td>
    </tr>
  </tbody>
</table>
