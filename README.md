# dalang-dialect

大浪天国的常用语百科

记录我们的独家记忆

## 提交规范

### 书写格式

- 请使用 markdown 语法编写

```markdown
## AAAA

- 出处
  - 时间：2020.01.01
  - 事件：XX在YY时说AAAA
- 含义
  - 表示XX对YY感到CC
  - 也可以表示XX感到DD
- 例句
  - YY太AAAA了
```

### Commit 规范

- 一个 commit 只能针对一个常用语做出一种操作
- 基本格式：[commit 类型]: [commit 信息]
- commit 类型
  - add：初次添加某常用语；commit 信息为被添加常用语
  - fix：修复常用语中某些不正确的部分；commit 信息中解释对哪个常用语修复了什么内容
  - format：修正书写格式；commit 信息为被修正的常用语

