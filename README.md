# Anchor Test action
Github action for running Anchor tests


### Example action
```yaml
anchor-test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - name: Anchor Test
        uses: mrgnlabs/anchor-test-action@0.1.0
        with:
          args: <anchor test args>
```
