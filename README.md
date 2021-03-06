# Search Bar

Search bar in the style of Google.

![img](/assets/screenshot.jpg)

## Code below

### HTML

```javascript
<form>
    <input type="text" placeholder="Search..." name='film'/>
    <input type="submit"/>
</form>
```

### CSS

```javascrip
form{
    width: 16rem;
    margin: 1rem auto 1rem auto;
    border-radius: 25px;
    background-color: rgb(230, 228, 228);
}

input[type="text"] {
    border: none;
    border-radius: inherit;
    background: transparent;
    color: inherit;
    font-size: 14px;
    margin: 0;
    padding: 7px 8px;
}

input[type="text"]::placeholder {
    color: #bbb;
}

input[type="submit"] {
    width: 40px;
    padding: 0;
    margin: 0;
    border: none;
    border-radius: inherit;
    text-indent: -999px;
    overflow: hidden;
    background: transparent url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16' class='bi bi-search' viewBox='0 0 16 16'%3E%3Cpath d='M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z'%3E%3C/path%3E%3C/svg%3E") no-repeat center;
    cursor: pointer;
    opacity: 0.7;
}

input[type="submit"]:hover {
    opacity: 1;
}

input[type="submit"]:focus,
input[type="text"]:focus {
    outline: none;
}
```
