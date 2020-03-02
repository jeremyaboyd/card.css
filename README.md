# card.css
Everything is a Card (except the things that aren't)

## Usage
Card.css is a farely minimalistic microframework that has only one component defined: the `card`.

A `card` is defined as a block element with two optional child block elements, a `media`, and a `body`.

A `card.media` is defined as a block element.

A `card.body` is defined as a block element with three optional child block elements, a `title`, a `subtitle`, and a `description`.

The `card.body.title` and `card.body.subtitle` are defined as block elements that are meant to be used with text.

A `card.body.description` is defined as a block element.

### Example Card

```html
    <div class="card">
        <img class="media" src="https://placekitten.com/200/300?image=4" />
        <div class="body">
            <h2 class="title">An Addorable Kitten</h2>
            <p class="subtitle">Who doesn't love it?</p>
            <div class="description">
                <p>Donec non placerat tortor. Vestibulum vestibulum vel turpis ut tincidunt. Fusce eu libero a odio condimentum suscipit. Quisque dictum dui nec odio viverra, sed pulvinar arcu pretium. Donec hendrerit nibh.</p>
            </div>
        </div>
    </div>
```