---
layout: clean
title: Status Updates
permalink: /posts/
---

<div style="max-width: 800px; margin: 0 auto; padding: 0 20px;">
    <img src="../media/image.png" alt="UCCUMO Logo" style="max-width: 200px; margin-bottom: 15px;">
    
    <h1 style="color: #333; margin-bottom: 30px;">Status Update History</h1>

    <div class="posts">
        {% for post in site.posts %}
        <div style="background-color: #fff; border: 1px solid #ddd; border-radius: 5px; padding: 20px; margin-bottom: 20px;">
            <h2 style="margin: 0 0 10px 0;">
               {{ post.title }}
            </h2>
            <div style="color: #666; font-size: 0.9rem; margin-bottom: 10px;">
                {{ post.date | date: "%B %d, %Y at %I:%M %p" }}
            </div>
            {% if post.excerpt %}
            <div style="color: #444; margin-top: 10px;">
                {{ post.excerpt }}
            </div>
            {% endif %}
        </div>
        {% endfor %}
    </div>

    <div style="margin-top: 40px; text-align: center;">
        <a href="{{ site.baseurl }}/" style="display: inline-block; background-color: #28a745; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px;">Back to Status Page</a>
    </div>
</div>
