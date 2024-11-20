---
layout: default
---

<ul>
  <% collections.posts.each do |post| %>
    <li>
      <a href="<%= post.relative_url %>"><%= raw post.data.title %></a>
    </li>
  <% end %>
</ul>
