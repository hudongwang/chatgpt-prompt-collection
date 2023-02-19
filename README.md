# chatgpt-prompt-collection

- 翻译
- 语法检查
- emoji
- 研发
- 文案生成

## 翻译

```
翻译成英文：
骑行算不算一项业余爱好？

翻译成中文：
君の中国语本当上手
```
连续对话版：
```
接下来我说的话，除非以 // 开头，否则都是要你帮我在中文和英文之间来回翻译，只回复我译文就好，不需要其他的文字，可以吗？

（实测中间还是会有些文字被当做命令而不是要翻译的内容，这时候可以临时用一下单句翻译版）
（过一段时间效果会丢失，重新发一次上面的 prompt 即可）
...

...
```

## 语法检查

```
语法检查：xxx

grammer check: xxx
```

```
接下来我说的话，除非以 // 开头，否则都是要你帮我做语法检查，只回复我语法检查的结果就行，不需要其他的文字，可以吗？
```

## emoji

```
用 emoji 表示一下：
白日依山尽，黄河入海流

all emoji about: test
🧪 - test tube
📝 - memo
📋 - clipboard
📄 - page facing up
💻 - computer
...
```

## 研发

```
show me an regex to match "我的手机号13333333333"，the "13333333333" should be a submatch of number

show me a regular expression to match the next sentences, and the different part should be sub matches
...
...

will this regex: `xxx`
match next sentences:
...
...


help me write some go code.
I want use aes to encrypt a.txt then save as ae.txt
...
...


go sha-224 demo
```
