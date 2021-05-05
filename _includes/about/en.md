
<div class="container col-11 mx-auto">
    <h3 class="text-warning">Blue Geek Channel</h3>
    <h4>Blue Geek，an "useful" channel.</h4>
    <h4>Main Contents:</h4>
    <ul>
        <li>machin learning, programming, math and other sci-tech articles and videos</li>
        <li>some useful sci-tech and interesting knowledge books</li>
        <li>technical tutorials</li>
    </ul>
    {% if site.ad_wechat_img %}
    <h4>Wechat Public【Blue Geek】</h4>

    <div class="block container"><img class="block col-lg-6 col-md-12 col-sm-12" src="{{ site.ad_wechat_img }}" /></div>
    {% endif %}

    {% if site.tg_link %}
    <h4>Telegram Channel</h4>
    <p><a href="{{ site.tg_link }}">Blue Geek Channel</a></p>
    {% endif %}

    {% if site.wechat_qr %}
    <h4>Personal Wechat</h4>
    <div style="text-align:left;width:100%;"><img width="150" height="150" style="margin-left:2em;" src="{{ site.wechat_qr | prepend: site.baseurl }}" /></div>
    {% endif %}
</div>
