# jh-tslint
Tslint preset and Typescript Style Guide. 

## Installation
`jh-tslint` peer 依赖于`tslint`(^5.6.0), `tslint-eslint-rules`(^4.1.1), `tslint-react`(^3.2.0), `typescript`(^2.4.2), 所以再次之前需要安装要这些依赖.

```
yarn add jh-tslint -D
```
或者通过npm
```
npm i jh-tslint --save-dev
```

## Usage
创建你自己的`tslint.json`, 并通过`extends`选项继承`jh-tslint`
```json
{
  "extends": ["jh-tslint"],
  "rules" {
    // 覆盖你自己的规则
  }
}
```

## Style Guide
[typescript-style-guide](./style-guide.md)
