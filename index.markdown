---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---										  

<aside class="social-share">
    <h2>Share this:</h2>
    <ul>
        <li class="twitter"><a href="https://twitter.com/intent/tweet?url={{ site.url }}{{ page.url }}{% if page.description %}&text={{ page.description | url_escape }}{% else %}{{ page.title | url_escape }}{% endif %}{% if site.twitter %}&via={{ site.twitter }}{% endif %}" title="Share on Twitter">Twitter</a></li>
        <li class="facebook"><a href="https://www.facebook.com/sharer/sharer.php?u={{ site.url }}{{ page.url }}{% if page.description %}&t={{ page.description | url_escape }}{% else %}{{ page.title | url_escape }}{% endif %}" title="Share on Facebook">Facebook</a></li>
        <li class="googleplus"><a href="https://plus.google.com/share?url={{ site.url }}{{ page.url }}" title="Share on Google Plus">Google+</a></li>
    </ul>
</aside>

<iframe src="https://www.google.com/maps/d/u/0/embed?mid=1rMVt1bc2Xd8mjDe3hJpEtVabljleHwMF" width="640" height="480"></iframe>
