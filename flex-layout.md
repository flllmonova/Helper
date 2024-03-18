styles for list of cards
```css
.container {
  display: flex;
  gap: 25px; /* gap will set horisontal and vertical space. it is convenient */
}

.card {
  flex-grown: 1; /* so that she takes up all the space in her row before more cards appear */
  width: 450px;
  min-height: 395px;
}
```

> layout for cards list
```html
<ul class="lots__card-list">
  <li class="lots__card-list-item">
    <a class="card-link">
      <article class="card card_type_book">
        <h2 class="card__title"></h2>
        <div class="card__text">
          <p></p>
          <p></p>
        </div>
      </article>
    </a>
  </li>
  <li class="lots__card-list-item">
    <a class="card-link">
      <article class="card card_type_book">
        <h2 class="card__title"></h2>
        <div class="card__text">
          <p></p>
          <p></p>
        </div>
      </article>
    </a>
  </li>
</ul>
```
