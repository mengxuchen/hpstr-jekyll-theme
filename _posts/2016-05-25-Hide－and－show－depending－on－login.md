---
layout: post
title: Hide and Show a DIV Depending On Login
tags: [WordPress]
---
<a href="http://stackoverflow.com/questions/27640100/hide-and-show-a-div-depending-on-login" target="_blank">Hide and Show a DIV Depending On Login</a>

I'm creating my own navigation. I need to show and hide a button based on the login status. If users are logged in, it shows up, if they are not, it does not show. Regardless of their permission settings.

{% highlight php %}
<?php if (is_user_logged_in()): ?>
<div id="user">
      My Profile
</div>
<?php elseif (is_admin()): ?>
<div id="admin">
      Admin Profile
</div>
<?php else: ?>
<div id="login">
      Login...
</div>
<?php endif; ?>
{% endhighlight %}

https://developer.wordpress.org/reference/functions/is_user_logged_in/