# demo-egg

[Egg.js Typescript] Demo.

## 开发

```bash
npm i
npm run dev
open http://localhost:7001/
```

> 注意

运行部署命令`npm run tsc`会在同名目录下编译生成`*.js`文件。
需要在运行开发命令`npm run dev`前，先进行清理`npm run clean`。

## 部署

```bash
npm run tsc
npm start
```

## 命令

|      命令       |                      |
| --------------- | -------------------- |
| `npm run lint`  | 代码检查             |
| `npm test`      | 单元测试             |
| `npm run tsc`   | 编译部署文件（*.js） |
| `npm run clean` | 清理编译文件（*.js） |

### 依赖

- Node.js 8.x
- Typescript 2.8+

> 方跃明
> 2020-09-20

[Egg.js Typescript]: https://eggjs.org/zh-cn/tutorials/typescript.html
