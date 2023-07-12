<div class="side-bar">
  <div class="site-header" role="banner">
    <a href="{{ '/' }}" class="site-title lh-tight">Home</a>
    <button id="menu-button" class="site-button btn-reset" aria-label="Toggle menu" aria-pressed="false">
    btn
    </a>
  </div>
  <nav aria-label="Main" id="site-nav" class="site-nav">
    
      <ul class="nav-list">
      {% if pages_top_size > 0 %}
          <li class="nav-list-item external">
            <a href="/home.html" class="nav-list-link external">
              home             
            </a>
          </li>
     {% endif %}
      </ul>
 
   
  </nav>

    <footer class="site-footer">
      This site uses <a href="https://github.com/just-the-docs/just-the-docs">Just the Docs</a>, a documentation theme for Jekyll.
    </footer>

</div>
