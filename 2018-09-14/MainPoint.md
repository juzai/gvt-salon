# 基础知识

- 指令
    1. 介绍 vue 内置指令
    2. 实战: 开发一个 click_out_side 指令

- 过滤器
    1. 介绍 vue 内置过滤器
    2. 实战:开发一个 filter, 并在 main.js(入口文件) 中全局注册 filter
    3. 安利:常用 node_module, 如: numeral、moment 等

- 混入
    1. 介绍 mixins
    2. 实战: 开发一个 break_table_point mixins
    3. 安利: unique_key mixins

- 组件通讯
    1. 父子组件通讯 (vue.$emit() && v-on)
    2. 兄弟组件通讯 (eventBus or Vuex)
    3. 爷孙组件通讯 (eventBus or Vuex)
    4. 其他一些骚操作
    5. 实战: 介绍 EOS 采购计划单详情中的: 组件拆分、通讯等


# 三大痛点

- 环境变量
    1. 依据 process.env.NODE_ENV 动态定义环境变量
    2. 依据 env.js 获取环境变量

- 请求拦截
    1. diff ajax & axios
    2. 实战: 封装一个匹配自家服务端(UMS)的 HTTP Request Module

- 数据校验
    1. 介绍 async-validator
    2. 定义 rules 常量
    3. 结合 iview Form Component 进行数据校验
    