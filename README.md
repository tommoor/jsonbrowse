# JSON Browse

<img width="954" alt="screenshot 2016-12-06 00 20 30" src="https://cloud.githubusercontent.com/assets/31465/20918070/05b3b170-bb4a-11e6-8a95-7c9b79f723f7.png">

Browse, filter and manipulate your JSON inside the browser.

- Fetch external JSON or paste local code
- Filter JSON like you would filter JS objects in the browser (e.g. `data.values[1].message`)
- Copy filtered output to your clipboard as a javascript object or JSON string
- Manipulate filtered output in your browser's javascript console

Live version hosted at [jsonbrowse.com](https://jsonbrowse.com).

## Installation

To run development server:

```
git clone https://github.com/jorilallo/jsonbrowse.git
cd jsonbrowse

npm install
npm run dev
```

To build and start production server:

```
npm run build
npm run start
```

JSON Browse is build using [`next.js`](https://github.com/zeit/next.js/), [`styled-components`](https://github.com/styled-components/styled-components) and
easily deployable using [`now`](https://zeit.co/now/).

## License

MIT
