 ________________
< Hello World 2! >
 ----------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
               ||----w |
                ||     ||


## [Wasmer](https://wasmer.io/)

`curl https://get.wasmer.io -sSfL | sh`

```sh
$ wapm install cowsay

$ wapm run cowsay Hello World 2!
```

>.
>├── README.md
>├── wapm.lock
>└── wapm_packages
>    └── _
>        └── cowsay@0.2.0
>            ├── LICENSE
>            ├── README.md
>            ├── target
>            │   └── wasm32-wasi
>            │       └── release
>            │           └── cowsay.wasm
>            └── wapm.toml
>
>6 directories, 6 files
