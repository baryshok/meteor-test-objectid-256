## Steps to reproduce

1. `meteor npm i`
2. `meteor`
3. Open `http://localhost:3000` in browser
4. Click on "Click Me" button
5. Check the browser's console – `oid` field should be an object containing `_bsontype` and `id` fields:

![38141136-C9D4-4D31-B085-75CF13F2AB32](https://user-images.githubusercontent.com/16780712/167315826-30a3f324-6efa-4725-bad6-1473e0e3b94f.png)
