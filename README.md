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
- NUC10 i7-6core (32GB): 36.72s
- Macbook Pro 2015 i5-2core (8GB): 54.22s
- Dell XPS 15 9500 i7-6core (16GB): 36.01s
