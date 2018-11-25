### recharts
---
http://recharts.org/en-US/api

https://github.com/recharts/recharts
```js

```

```sh
npm install recharts

git clone https://github.com/recharts/recharts.git
cd recharts
npm install
npm run build
npm run[-script] demo
curl http://localhost:3000
```

```
<LineChart
  width={400}
  height={400}
  data={data}
  margin={{ top: 5, right: 20, left: 10, bottom: 5 }}
>
  <XAxis dataKey="name" />
  <Tooltip />
  <CartesianGrid stroke="#f5f5f5" />
  <Line type="monotone" dataKey="uv" stroke="#ff7300" yAsixId={0} />
  <Line type="monotone" dataKey="pv" stroke="#387908" yAxisid={1} />
</LineChart>

<script src="https://unpkg.com/react/umd/react.production.min.js"></script>
<script src="https://unpkg.com/react-dom/umd/react-dom.production.min.js"></script>
<script src="https://unpkg.com/prop-types/prop-types.min.js"></script>
<script src="https://unpkg.com/recharts/umd/Recharts.min.js"></script>
```


