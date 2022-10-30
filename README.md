# LesserJs

## Install

- Browsers:

```html
<script src="LsserJs.min.js"></script>
<script>
    const ljs = new LesserJs();

    window.onload = () => {
        const script = document.querySelector('textarea').value;
        const div = document.querySelector('div').innerText = ljs.minify(script);        
    }
</script>
```

## Known Issues

- class will not work properly if the class is read.

## License

[MIT](LICENSE)
