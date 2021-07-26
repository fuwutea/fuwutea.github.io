---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
# commission sheet
![CommissionInfo](/assets/commission-info.png)

# portfolio
## emotes ($30-$35 each)
<div>
{% for img in site.data.emotes %}
    <a class="thumbnail"
      data-fancybox="emotes"
      data-src="/assets/{{ img.file }}"
      data-caption="{{ img.desc }}"
    >
      <img class="thumbnail" src="/assets/thumbs/{{ img.file }}" width="100px"/>
    </a>
{% endfor %}
</div>
## full body art ($20-$50)
<div>
{% for img in site.data.full%}
    <a class="thumbnail"
      data-fancybox="full"
      data-src="/assets/{{ img.file }}"
      data-caption="{{ img.desc }}"
    >
      <img class="thumbnail" src="/assets/thumbs/{{ img.file }}" width="100px"/>
    </a>
{% endfor %}
</div>
