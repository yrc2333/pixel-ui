---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: "Pixel-UI"
  text: "基于CSS_Houdini的像素风组件库🐱"
  image:
    src: /images/homelogo.png
  actions:
    - theme: brand
      text: 开始使用
      link: /get-started

features:
  - icon: 🎨
    title: 像素风格自定义渲染
    details: 利用CSS Houdini Paint Worklet实现像素化渲染效果，为组件带来独特的像素艺术外观。用户可以通过CSS自定义变量动态调整像素大小、颜色风格、边框样式等，打造独一无二的UI风格。
  - icon: ⚙️
    title: 全面类型支持与TypeScript友好
    details: 所有组件均使用TypeScript编写，并提供完整类型定义。支持智能提示、类型校验以及良好的IDE体验，帮助开发者高效构建类型安全的项目。
  - icon: 🧩
    title: 单文件组件结构+Monorepo管理
    details: 每个组件以独立的SFC单文件形式开发，利于维护和按需加载。使用Monorepo管理架构，支持模块化构建与统一版本控制，适配现代前端工程化流程。
  - icon: 🧪
    title: 完整测试覆盖
    details: 使用Vitest提供单元测试保障，核心逻辑覆盖率达到100%。每个组件均配套测试用例，确保组件稳定性与长期可维护性。
  - icon: 📖
    title: VitePress+Storybook 双文档系统
    details: 使用VitePress提供Markdown风格的文档网站，结合Storybook实现组件级交互演示。支持Playground、属性切换与源码查看，提升学习与使用体验。
  - icon: 💡
    title: 像素风字体与主题系统
    details: 内置多种像素风格字体，并支持自定义注册字体。提供像素风主题变量系统，实现不同视觉风格快速切换，支持夜间模式和复古配色方案。
  - icon: 🧱
    title: 兼容Vue3+UnoCSS
    details: 基于Vue3 setup语法糖开发，完美适配Composition API。同时使用UnoCSS作为原子化样式系统，支持极速开发与极致按需打包。
  - icon: 🚀
    title: 支持渐进式集成
    details: 支持完整引入与单组件引入，便于逐步迁移。你可以在不影响现有项目的前提下，按需引入任意组件进行替换或增强，实现平滑升级。

---

