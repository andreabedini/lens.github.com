---
layout: site
title: Home
---


This package provides families of [lenses](https://github.com/ekmett/lens/blob/master/src/Control/Lens/Type.hs), [isomorphisms](https://github.com/ekmett/lens/blob/master/src/Control/Lens/Iso.hs), [folds](https://github.com/ekmett/lens/blob/master/src/Control/Lens/Fold.hs), [traversals](https://github.com/ekmett/lens/blob/master/src/Control/Lens/Traversal.hs), [getters](https://github.com/ekmett/lens/blob/master/src/Control/Lens/Getter.hs) and [setters](https://github.com/ekmett/lens/blob/master/src/Control/Lens/Setter.hs).

<blockquote>
  <p>Costate Comonad Coalgebra is equivalent of Java's member variable update technology for Haskell</p>
  <small><a href="https://twitter.com/PLT_Borat/">@PLT_Borat</a> <cite title="twitter">on twitter</cite></small>
</blockquote>

The [FAQ](https://github.com/ekmett/lens/wiki/FAQ), which provides links to a large number of different resources for learning about lenses and an overview of the [derivation](https://github.com/ekmett/lens/wiki/Derivation) of these types can be found on the [Lens Wiki](https://github.com/ekmett/lens/wiki) along with a brief [overview](https://github.com/ekmett/lens/wiki/Overview) and some [examples](https://github.com/ekmett/lens/wiki/Examples).

Documentation is available through [github](http://ekmett.github.com/lens/frames.html) (for HEAD) or [hackage](http://hackage.haskell.org/package/lens) for the current and preceding releases.

### <a href="/rss.xml"><img src="/img/feed-icon-28x28.png"></a> Recent Activity

<div class="content">
  <div class="related">
    <ul>
      {% for post in site.posts %}
      <li>
        <span>{{ post.date | date: "%B %e, %Y" }}</span> &middot; <span>{{post.author}}</span> &middot; <span><a href="{% if post.link != null %}{{ post.link }}{% else %}{{ post.url }}{% endif %}">{{ post.title }}</a></span>
      </li>
      {% endfor %}
    </ul>
  </div>
</div>

### Video from New York Haskell: Lenses, Folds and Traversals

[Slides from this talk](http://comonad.com/haskell/Lenses-Folds-and-Traversals-NYC.pdf) are also available.

<iframe width="1200" height="720" src="https://www.youtube.com/embed/cefnmjtAolY?hd=1&amp;start=74" frameborder="0" allowfullscreen="1"></iframe>

