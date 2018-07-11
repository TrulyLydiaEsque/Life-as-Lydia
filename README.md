<div class="masthead">
  <div class="masthead__inner-wrap">
    <div class="masthead__menu">
      <nav id="site-nav" class="greedy-nav">
        <a class="site-title" href="{{ '/' | relative_url }}">{{ site.title }}</a>
           <ul class="visible-links">
          {% for link in site.data.navigation.main %}
            {% if link.url contains 'http' %}
              {% assign domain = '' %}
            {% else %}
              {% assign domain = site.url | append: site.baseurl %}
            {% endif %}
            <li class="masthead__menu-item">
              <a href="{{ domain }}{{ link.url }}" {% if link.description %}title="{{ link.description }}"{% endif %}>{{ link.title }}</a>
            </li>
          {% endfor %}
        </ul>
        {% if site.search == true %}
        <button class="search__toggle" type="button">
          <svg class="icon" width="16" height="16" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 15.99 16">
            <path d="M15.5,13.12L13.19,10.8a1.69,1.69,0,0,0-1.28-.55l-0.06-.06A6.5,6.5,0,0,0,5.77,0,6.5,6.5,0,0,0,2.46,11.59a6.47,6.47,0,0,0,7.74.26l0.05,0.05a1.65,1.65,0,0,0,.5,1.24l2.38,2.38A1.68,1.68,0,0,0,15.5,13.12ZM6.4,2A4.41,4.41,0,1,1,2,6.4,4.43,4.43,0,0,1,6.4,2Z" transform="translate(-.01)"></path>
          </svg>
        </button>
        {% endif %}
        <button class="greedy-nav__toggle hidden" type="button">
          <span class="visually-hidden">{{ site.data.ui-text[site.locale].menu_label | default: "Toggle Menu" }}</span>
          <div class="navicon"></div>
        </button>
        <ul class="hidden-links hidden"></ul>
      </nav>
    </div>
  </div>
</div>

# Life as Lydia
      

### __okay, cool.__
a short phrase  use to conclude plans, finish an excerpt of conversation, or anything, really.

### What are my Interests?

1. cooking/baking 
2. ballet
3. sketchbook
4. street style
5. veganism
6. sustainability

**ooo here are a couple of my links** 
[my insta](https://www.instagram.com/lydia__lauren/) & [my twitter](https://twitter.com/lydiaesque) 

### Content
this is the epitome of a trashy blog. there is no real theme, little organizaion, and general rants about life are plentiful. please enjoy my awkward tangents and ethusing abut miselaeous topics. 
