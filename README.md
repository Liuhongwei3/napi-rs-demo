## napi-rs
> [napi-rs](https://napi.rs/)

NAPI-RS is a framework for building pre-compiled Node.js addons in Rust.

## install rust
[rust-lang](https://www.rust-lang.org/tools/install)

## install napi-rs
```shell
yarn global add @napi-rs/cli
// or
npm install -g @napi-rs/cli
```

## create project
```shell
napi new

// 按照提示填写相关信息即可
```

## run
```shell
yarn
yarn build
yarn test
```

关注文件：

- index.js 主文件
- index.d.ts 自动生成的相关类型
- src/lib.rs rust 源文件
- __test__\index.spec.mjs 测试用例

## 参考
> https://juejin.cn/post/7243413934765408315
