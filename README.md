# FreshersTask

## my content

text- alignmnet
view helpder

[a home](Home.md)

[a newhome](newHome.md)

<nav>
  <ul>
   {% for item in site.navigation %}
      <li>
      {%  [a home](Home.md) %}
         </li>
         <li>
      {%  [a new](newhome.md)  %}
         </li>
       <li>
       {%  [a test](test.md)  %}
      </li>
   {% for item in site.navigation %}
  </ul>
</nav>
