---
sectionid: schedule-daytime
sectionclass: h2
parent-id: schedule
title: 시간대 설정
number: 1200
---
{% highlight yaml %}
요일 예외가 있는 여러 시간대 작성을 지원하므로 하루를 필요한 만큼 많은 미리 정의 된 부분으로 분할 할 수 있습니다.
일반적인 사용 사례는 아침, 점심 및 저녁 식사로 표시 할 내용이 다른 접대 사용자입니다. 시간대 지정을 사용하면 해당 사용자가 아침, 점심 및 저녁 시간대를 만들 수 있으며 각기 다른 날에 시작하고 끝납니다.
시간대를 관리 할 권한이 있는 사용자는 기본 탐색에서 액세스 할 수 있는 "시간대 지정" 메뉴를 갖습니다.
아래 시간대 양식은 아침 식사 시간대의 예를 보여줍니다.
{% endhighlight %}
![daytime_moning](./img/daytime_moning.png)
{% highlight yaml %}
토요일과 일요일은 예외로 구성되어 있어서 그 날 아침에 다른 시간에 아침 식사가 시작되고 끝납니다.
{% endhighlight %}
![daytime_ex](./img/daytime_ex.png)
{% highlight yaml %}
시간대 업데이트 
시간대에 대한 시작 / 종료 시간 또는 예외를 업데이트하면 기존 이벤트가 새로운 시간으로 업데이트됩니다. 또한 현재 시간 이후에 반복되는 기존 되풀이 일정에 대해 새로운 되풀이 일정을 만듭니다. 이전 되풀이 일정은 그대로 유지되며 새 일정에는 새로운 시작 / 끝 시간이 포함됩니다.
{% endhighlight %}
