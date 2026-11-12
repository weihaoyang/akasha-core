# 全息计算 · akasha core

全息物理计算与知识条目。本仓从 [知几排盘](https://github.com/weihaoyang/qimen-llm-chart) 提取 TypeScript 源码及对应测试，可独立安装依赖并运行；支持 ESM、CommonJS 与 TypeScript。

## 运行

需要 Node.js 20 或更高版本。

```sh
npm install
npm test
npm run typecheck
```

发布后安装：`npm install @singseq/akasha-core`。入口 `@singseq/akasha-core`；其他模块可按 `@singseq/akasha-core/模块名` 导入。源码与测试位于 `src/`。

## 资料与案例

- [原项目研究论文](https://github.com/weihaoyang/qimen-llm-chart/blob/main/docs/research/calculation-audit-paper.md)
- [原项目来源及技术说明](https://github.com/weihaoyang/qimen-llm-chart/blob/main/docs/THIRD_PARTY_NOTICES.md)

- ships the concept entries, timeline, protocol and ethics（`src/chart.test.ts`）
- keeps the classical fractal dimensions（`src/chart.test.ts`）
- computes the Schwarzschild radius and horizon area（`src/chart.test.ts`）
- puts one nat per four Planck areas and reproduces the known magnitudes（`src/chart.test.ts`）
- shows the area law is far smaller than the volume law（`src/chart.test.ts`）

这些案例验证列出的计算或文本字段，不代表预测效果经过验证。对于现代知识或几何构造，资料链接标注其实际来源，不冒称古籍。

## 授权

本仓代码按 [GPL-3.0-only](LICENSE) 发布，源自知几排盘。

- 本目录未登记移植的第三方代码；见原项目的第三方声明。

外部资料和影像按各自来源的使用条件处理，本仓不附古籍影像。
