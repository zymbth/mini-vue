# Fork [MiniVue](https://github.com/woai3c/mini-vue/)

拷贝 [MiniVue v0.1](https://github.com/woai3c/mini-vue/tree/v0.1) 代码，方便个人本地调试运行，学习 vue v1.0 基本原理。

重新配置了webpack，供本地运行调试使用。

克隆项目之后，安装、运行：

```bash
npm install
npm run start
```

以下是原仓库部分说明，详见 [MiniVue](https://github.com/woai3c/mini-vue/)

---

## Vue1 和 Vue2 的区别

其实 Vue1 和 Vue2 最大的区别就是 Vue2 多了一个虚拟 DOM，其他的区别都是很小的。所以理解了 Vue1 的源码，就相当于理解了 Vue2，中间差了一个虚拟 DOM 以及 Diff 算法

## 网友的学习笔记

- [Mr.大哥](https://www.yuque.com/mrdage/qnzf2d)

## 文档

- [Vue 简介](https://github.com/woai3c/mini-vue/blob/master/doc/introduce.md)
- [数据双向绑定](https://github.com/woai3c/mini-vue/blob/master/doc/%E6%95%B0%E6%8D%AE%E5%8F%8C%E5%90%91%E7%BB%91%E5%AE%9A.md)
- [Vue 主流程走向](https://github.com/woai3c/mini-vue/blob/master/doc/Vue%E7%9A%84%E4%B8%BB%E6%B5%81%E7%A8%8B%E8%B5%B0%E5%90%91.md)
- [组件](https://github.com/woai3c/mini-vue/blob/master/doc/%E7%BB%84%E4%BB%B6.md)
- [nextTick 异步更新](https://github.com/woai3c/mini-vue/blob/master/doc/nextTick%E5%BC%82%E6%AD%A5%E6%9B%B4%E6%96%B0.md)

## MVVM

[先来科普一下 MVVM 的概念及原理](https://github.com/woai3c/mini-vue/blob/master/doc/mvvm.md)

## 配套插件

[mini-vuex](https://github.com/woai3c/mini-vuex)

## 实现一个迷你版的 vue

原仓库 [MiniVue v0.1](https://github.com/woai3c/mini-vue/tree/v0.1)
