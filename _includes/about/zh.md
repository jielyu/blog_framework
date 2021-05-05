
<div class="container col-11 mx-auto">
    <h3 class="text-warning">青衣极客频道</h3>
    <h4>青衣极客，一个“有用”的频道。</h4>
    <h4>主要发布内容：</h4>
    <ul>
        <li>机器学习、编程、数学以及其他科技类文章和视频。</li>
        <li>有用的技术类和有趣的知识类书籍资源</li>
        <li>技术类教程资源</li>
    </ul>
    {% if site.ad_wechat_img %}
    <h4>微信公众号【青衣极客】</h4>

    <div class="block container"><img class="block col-lg-6 col-md-12 col-sm-12" src="{{ site.ad_wechat_img }}" /></div>
    {% endif %}

    {% if site.tg_link %}
    <h4>电报频道</h4>
    <p><a href="{{ site.tg_link }}">青衣极客频道</a></p>
    {% endif %}

    {% if site.wechat_qr %}
    <h4>个人微信</h4>
    <div style="text-align:left;width:100%;"><img width="150" height="150" style="margin-left:2em;" src="{{ site.wechat_qr | prepend: site.baseurl }}" /></div>
    {% endif %}

</div>
