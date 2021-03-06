---
sectionid: resolution
sectionclass: h2
parent-id: design
title: 해상도 관리
number: 2400
---
레이아웃은 특정 해상도에서 실행되도록 설계되었으며 일치하는 해상도의 간판 플레이어에 표시 될 때 가장 잘 작동합니다.  
다른 해상도의 간판 플레이어에 표시되면 자동으로 크기가 조정됩니다.

__올바른 해상도 선택__
{% highlight yaml %} 
대부분의 디지털 사이니지 응용 프로그램 (예 : LCD TV, 프로젝터, 세로 화면)에 적합한 기본 해상도가 선택되어 제공됩니다.
선택한 모양 레이아웃을 화면에 맞추기 위해 최선을 다할 것입니다. 그러나 클라이언트가 16 : 9 TV에 연결될 때 4 : 3 종횡비로 레이아웃을 전송하면 콘텐츠의 양쪽에 2 개의 막대가 낭비됩니다.
레이아웃을 표시 할 화면에 가장 가까운 해상도를 선택해야합니다.
{% endhighlight %}
__세로 표시__ 
{% highlight yaml %}
플레이어 하드웨어에서 지원하는 경우 세로 해상도를 사용할 수 있습니다.
{% endhighlight %}
