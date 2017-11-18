# \<nickel-level-bar\>
(Built with Polymer 2.0)

A very simple and customizable level bar (progress bar).

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="./nickel-level-bar.html"/>
    <script>
      (() => {
        document.addEventListener('level-changed', (e) => {
          document.getElementById('value').textContent = e.target.value;
        });
      })();
    </script>
    <next-code-block></next-code-block>
    <div>Value : <span id="value"></span></div>
  </template>
</custom-element-demo>
```
-->
```html
<nickel-level-bar size="300" level="25"></nickel-level-bar>
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

GNU General Public License version 3.0.
