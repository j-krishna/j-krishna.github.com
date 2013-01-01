---
layout: page
title: Krishna's
tagline: Software. Business.
---
{% include JB/setup %}


<ul class="posts">
     {% for post in site.posts %}
     <li>
          <h3>
              <a href="{{ post.url }}">
                  {{ post.title }}
              </a>
              <span class="post-date">
                  {{ post.date | date_to_string }}
             </span>
         </h3>
     </li>
     {% endfor %}
 </ul>

