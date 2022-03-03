# partytown-jsonp-issue

Run:
```
npm i
npm start
```
Go to:
```
localhost:3000
```
Open the browser console. `jsonpCallback result:` log will be missing.
Remove the `type="text/partytown"` from both `<script>` tags. Then `jsonpCallback result:` log will be visible.
