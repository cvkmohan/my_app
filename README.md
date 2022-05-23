This application is companion application for the blog post
[Using Parcel as Build Tool for Phoenix](https://blog.cvkmohan.com/using-parcel-as-build-tool-for-phoenix)

Though `phoenix` comes with `esbuild` as the default build tool for asset management, there are certain cases where you would need the modern build tools like `vite` or `parcel`.
This article is a code walk-through where we replace the `esbuild` with `parcel` and integrate `tailwindcss` into the application.
