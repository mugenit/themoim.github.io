---
sectionid: Embedded
sectionclass: h3
parent-id: module
title: Embedded
number: 3130
---
{% highlight yaml %}
임베디드 컨텐트 모듈을 사용하면 HTML 및 JavaScript를 레이아웃 영역에 포함 할 수 있습니다. 코어 응용 프로그램을 수정하지 않고도 사용자 지정 향상을 적용 할 수 있습니다. 이것이 유용한 곳의 예는 시계 또는 날씨 지역을 표시하는 것입니다.
 {% endhighlight %}
__출력시간__
{% highlight yaml %}
이 항목이 지역에 남아 있어야하는 기간 (초).
{% endhighlight %}
__투명배경__
{% highlight yaml %}
항목을 투명한 배경으로 렌더링 해야합니까?  사용자 정의 컨텐츠에 의해 무시 될 수 있습니다.
{% endhighlight %}
__HTML 콘텐츠__
{% highlight yaml %}
범위에 로드 해야하는 HTML.
{% endhighlight %}
__HEAD 콘텐츠__
{% highlight yaml %}
문서의 HEAD에 삽입 할 내용 - JavaScript는 script태그 로 묶어야 합니다.  자동으로 jQuery를 추가합니다.
 EmbedInit()메서드는 Display Client에서 호출되며 적절한 시간에 모든 사용자 정의 JavaScript를 안전하게 시작하는 데 사용할 수 있습니다. 이 메서드는 모든 새 Embedded Media 항목에서 기본값으로 설정됩니다.
{% endhighlight %}
