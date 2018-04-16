# graphQL_study
graphql 是一个套API 的查询语言，目标是替换REST API 。
2012年 facebook内部开始使用、2015年开源。[语言规范中文翻译](http://graphql.cn)

#### 优势
传统 web 应用通过开发服务给客户端提供接口是很常见的场景。而当需求或数据发生变化时，应用需要修改或者重新创建新的接口。长此以后，会造成服务器代码的不断增长，接口内部逻辑复杂难以维护。而 GraphQL 则通过以下特性解决这个问题：
* 声明式。查询的结果格式由请求方（即客户端）决定而非响应方（即服务器端）决定。你不需要编写很多额外的接口来适配客户端请求
* 可组合。GraphQL 的查询结构可以自由组合来满足需求。
* 强类型。每个 GraphQL 查询必须遵循其设定的类型才会被执行。
也就是说，通过以上的三个特性，当需求发生变化，客户端只需要编写能满足新需求的查询结构，如果服务端能提供的数据满足需求，服务端代码几乎不需要做任何的修改。



graphql 服务端可以由各种语言实现 ,目前主流语言在github上均由响应的服务端 比如  go 、Java C++等20种语言。

js 实现 比较知名的是 meteor 的 apollo套装 [官网](https://www.apollographql.com/) 
Apollo 除了提供服务端的实现之外还有 各种客户端。 有适配 vue、react angular 以及Android ios平台的客户端，屏蔽了数据请求层，前端只需要写graphql 即可完成数据操作

graphql 还有一个强大的接口[调试工具graphiql](https://github.com/graphql/graphiql) 方便调试接口以及查看接口文档。


#### 一些入门资料

* [什么是 GraphQL？](https://www.zhihu.com/question/264629587/answer/283187920)
* [GraphQL入门](https://segmentfault.com/a/1190000008226927)
* [前端调用 GraphQL API，从未如此方便](https://zhuanlan.zhihu.com/p/33380928)
* [How To Create A Universal Vue App With GraphQL](https://medium.com/@jonaskuiler/how-to-create-a-universal-vue-app-with-graphql-39ce35a07e93)
* [GraphQL，你准备好了么？](https://zhuanlan.zhihu.com/p/23647589)
* [Meteor推出的数据框架APOLLO](http://onetwo.ren/Meteor%E6%8E%A8%E5%87%BA%E7%9A%84%E6%95%B0%E6%8D%AE%E6%A1%86%E6%9E%B6APOLL)
* [GraphQL 核心概念](https://segmentfault.com/a/1190000006132986)
* [安息吧 REST API，GraphQL 长存](http://zcfy.baomitu.com/article/rest-apis-are-rest-in-peace-apis-long-live-graphql-3935.html )
* 解读graphql 系列 
  * [解读GraphQL(一): WHAT & WHY](http://insights.thoughtworkers.org/interpretation-graphql-what-and-why/)
  * [解读GraphQL(二): 使用Apollo Data构建GraphQL应用](http://insights.thoughtworkers.org/interpretation-graphql-what-and-why-2/)
  * [解读GraphQL(三)：Relay—面向未来的前端框架](http://insights.thoughtworkers.org/interpretation-graphql-what-and-why-3/)
* [GraphQL 入门: Apollo Client](https://segmentfault.com/a/1190000008862505)
* [搭建你的第一个 GraphQL 服务器](https://zhuanlan.zhihu.com/p/20468051)
* [入门 GraphQL & Apollo](https://www.aliyun.com/jiaocheng/356236.html)
* [GraphQL初探:从REST到GraphQL，更完善的数据查询定义](https://segmentfault.com/a/1190000005766732)
* [在Egg中使用GraphQL](https://zhuanlan.zhihu.com/p/30604868)
* [Learn Apollo A hands-on tutorial for Apollo GraphQL Client](https://www.learnapollo.com/introduction/get-started)
* [Apollo GraphQL 服务端实践](https://zhuanlan.zhihu.com/p/34219480)
* [apollo client chrome 调试插件](https://github.com/apollographql/apollo-client-devtools)
* [Full-stack React + GraphQL Tutorial](https://dev-blog.apollodata.com/full-stack-react-graphql-tutorial-582ac8d24e3b)
* [awesome-graphql graphql相关开源工具](https://github.com/chentsulin/awesome-graphql)
* [graphql优化工具 DataLoader介绍](https://www.jianshu.com/p/fbd1257116b0)
* [Node.js 服务端实践之 GraphQL 初探](http://taobaofed.org/blog/2015/11/26/graphql-basics-server-implementation/)
* [深入理解 GraphQL](http://taobaofed.org/blog/2016/03/10/graphql-in-depth/)
* [GraphQL:你需要知道的一切](https://juejin.im/post/5ad353986fb9a028c14ae909)
* [Input object type as an argument for GraphQL mutations and queries](https://medium.com/graphql-mastery/json-as-an-argument-for-graphql-mutations-and-queries-3cd06d252a04)
* [GraphQL quick tip: How to pass variables in GraphiQL](https://medium.com/graphql-mastery/graphql-quick-tip-how-to-pass-variables-into-a-mutation-in-graphiql-23ecff4add57)



