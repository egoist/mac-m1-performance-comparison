# Mac M1 Performance Comparison

Feel free to add your benchmark result here.

## Building [Vite](https://github.com/vitejs/vite)

<details><summary>Steps</summary>

```sh
git clone https://github.com/vitejs/vite.git
cd vite
git checkout 06663a7
yarn
yarn workspace vite build
```

</details>

- Mac Mini M1 (16GB): 23.44s
- Dell XPS 15 9500 i7-6core (16GB): 36.01s
- NUC10 i7-6core (32GB): 36.72s
- Macbook Pro 2015 i5-2core (8GB): 54.22s

## Building Node.js

<details><summary>Steps</summary>

Follow https://github.com/nodejs/node/blob/master/BUILDING.md, run `time make -j4` to build Node.js and measure the time.

</details>

- Mac Mini M1 (16GB): 744s
