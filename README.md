```sh
cd packages/ui

while true; do
  yarn repro
done
```

## log

```
❯ while true; do
yarn repro
done
turbo 2.0.13

• Packages in scope: @repo/new-ui
• Running echo in 1 packages
• Remote caching disabled
@repo/new-ui:echo: cache bypass, force executing bf8632cae4664734
@repo/new-ui:echo: ...

 Tasks:    1 successful, 1 total
Cached:    0 cached, 1 total
  Time:    600ms 

turbo 2.0.13

• Packages in scope: @repo/new-ui
• Running echo in 1 packages
• Remote caching disabled
@repo/new-ui:echo: cache bypass, force executing bf8632cae4664734
@repo/new-ui:echo: ...

 Tasks:    1 successful, 1 total
Cached:    0 cached, 1 total
  Time:    607ms 

turbo 2.0.13

  × No package found with name '@repo/ui' in workspace

```