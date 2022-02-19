# Reproduce https://github.com/vercel/turborepo/issues/460

Running `yarn turbo run dev --parallel` does not honor build dependencies

Graph:
![Graph dev command](./graph-1645300710972407553.jpg)

The following error occurs:
![Error](./error.png)
