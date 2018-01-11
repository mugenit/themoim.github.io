---
sectionid: layout-design
sectionclass: h3
parent-id: layout
title: 레이아웃 디자이너
number: 2210
---
{% highlight yaml %}
레이아웃 디자이너는 컨텐츠 작성의 핵심입니다. 새 레이아웃을 만들거나 기존 디자인을 변경해야 할 때마다 레이아웃 디자이너가 사용됩니다.
레이아웃을 처음부터 디자인 할 때 모든 기본 템플릿에는 아래에 그려진 하나의 전체 화면 빈 영역이 있습니다.
{% endhighlight %}
![layout02](./img/layout02.png)
{% highlight yaml %}
레이아웃은 디자이너 창에서 축소 된 의도 한 해상도로 디자인되었습니다. 레이아웃 디자이너는 스크롤 바를 사용하여 브라우저를 패닝하지 않고도 디자인을 수행 할 수 있도록 작은 디자인 해상도를 제공합니다. 작은 디자인 창은 중요하지 않으며 각 디스플레이에서 손실없이 끊임없이 크기가 조절됩니다.
{% endhighlight %}
__레이아웃 상태__ 
{% highlight yaml %}
레이아웃 디자이너가 열리면 CMS에서 레이아웃을 정기적으로 확인하여 재생할 준비가 되었는지 확인합니다. 이를 레이아웃 상태라고 하며 작업 탭 및 작업 탭 헤더 아이콘에서 볼 수 있습니다.
유효하지 않은 레이아웃은 일정에서 제외되며 재생되지 않습니다.
{% endhighlight %}
__레이아웃 기간__ 
{% highlight yaml %}
레이아웃 기간은 화면 상단에 표시되며 CMS에서 레이아웃 상태를 확인할 때마다 업데이트됩니다. 레이아웃 기간은 레이아웃에서 가장 오래 실행되는 지역을 기반으로 계산됩니다.
지역 기간은 함께 추가 된 재생 목록에 포함 된 모든 미디어의 기간을 기준으로 합니다.
플레이어에 레이아웃이 표시되면 일정 기간 동안 레이아웃이 실행 된 다음 일정에서 다음 레이아웃을 위해 제거됩니다.
{% endhighlight %}
__도구 상자__ 
{% highlight yaml %}
레이아웃 디자이너의 맨 위에는 레이아웃에서 수행 할 수 있는 가장 많이 사용되는 모든 작업이 포함 된 도구 상자가 있습니다. 도구 상자에는 두 개의 탭, "Designer"및 "Actions"가 있습니다.
{% endhighlight %}
![layout002](./img/layout002.png)
__배경__
{% highlight yaml %} 
배경 이미지, 색상 및 종횡비를 변경합니다.  
{% endhighlight %}
__범위__ 
{% highlight yaml %}
추가 배치 (끌어 놓기) 및 크기 조정이 가능한 새 영역을 배치에 추가합니다. 그런 다음 콘텐츠에 할당 할 수 있습니다.
{% endhighlight %}
__위치 잠금__ 
{% highlight yaml %}
실수로 움직일 수 없도록 영역을 끌어다 놓을 수 없습니다.
{% endhighlight %}
__Controls 숨기기__ 
{% highlight yaml %}
영역 위로 마우스를 움직일 때 Region 컨트롤이 표시되지 않게 합니다.
{% endhighlight %}
__- icon__ 
{% highlight yaml %}
디자인 창을 작게 만듭니다.
{% endhighlight %}
__+ icon__ 
{% highlight yaml %}
디자인 창을 크게 만듭니다.
{% endhighlight %}
__아이콘 저장__
{% highlight yaml %}
현재 디자인 창 크기를 기본값으로 저장합니다. 디자인 창을 더 크게 만듭니다.
{% endhighlight %}
__되돌리기__
{% highlight yaml %}
영역이 드래그 앤 드롭으로 이동하거나 크기가 조정 된 경우 해당 위치 변경을 취소합니다.
{% endhighlight %}
__저장하기__
{% highlight yaml%}
드래그 앤 드롭으로 이동하거나 크기가 조정 된 경우 해당 위치 변경 사항을 저장하십시오.
{% endhighlight %}
![layout003](./img/layout003.png)
__미리보기__
{% highlight yaml %}
브라우저에서 직접 전체 화면 레이아웃 미리보기를 봅니다. 
{% endhighlight %}
__예약하기__ 
{% highlight yaml %}
레이아웃 디자이너에서 직접 디스플레이에 레이아웃을 예약하십시오.
{% endhighlight %}
__Template 저장하기__ 
{% highlight yaml %}
디자인을 다시 사용 합니다. 템플릿으로 저장할 수 있습니다. 템플릿을 저장하면 영역, 재생 목록 및 미디어를 포함하여 레이아웃의 정확한 사본이 저장됩니다.
{% endhighlight %}

__레이아웃 선택기__ 
{% highlight yaml %}레이아웃 선택기는 레이아웃 관리 페이지로 이동할 때마다 현재 사용자가 편집 할 수 있는 권한이 있는 모든 레이아웃 간의 탐색을 제공합니다.
{% endhighlight %}
![layout_sel](./img/layout_sel.png)
{% highlight yaml %}
클릭하면 레이아웃 이름 목록이 표시됩니다. 이름을 클릭하면 해당 레이아웃이 디자이너 창에 로드 됩니다.
{% endhighlight %}
