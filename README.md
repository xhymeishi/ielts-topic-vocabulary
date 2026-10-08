# IELTS Topic Vocabulary

A Codex skill for learning IELTS and practical English vocabulary through themed articles, topic packs, and review. Choose topics such as education, the environment, business, technology, AI, Web3, or a field of your own.

## What it does

- Adapts vocabulary and reading difficulty to the learner's stated level and responses.
- Teaches words through coherent context, Chinese meanings, collocations, and examples.
- Separates 10–15 priority words from larger exposure lists such as a requested 100-word lesson.
- Includes short recall practice and can recycle missed vocabulary when prior lesson history is available.
- Offers a compact [sample lesson](references/example-lesson.md).

It is a vocabulary-learning aid, not a complete IELTS course, official test material, or a guarantee of a score.

## Install

Clone the repository into your Codex skills directory:

```bash
git clone https://github.com/xhymeishi/ielts-topic-vocabulary.git ~/.codex/skills/ielts-topic-vocabulary
```

Restart Codex, then invoke `$ielts-topic-vocabulary` or ask naturally, for example:

> Create a vocabulary lesson about AI at an intermediate level, with 12 focus words, Chinese meanings, collocations, and a short quiz.

For later updates, run `git pull` from the installed skill folder.

See [SKILL.md](SKILL.md) for instructions and [references/topics.md](references/topics.md) for the topic map.


## 中文快速上手

这是一个按主题生成雅思与实用英语词汇练习的 Codex Skill，适合用文章、搭配、例句和小测来学词；它不是完整雅思课程，也不保证考试分数。

安装后可这样试：

> 用中级难度，围绕 AI 客服写一篇雅思词汇学习文章，列出 10 个重点词，提供中文释义、搭配、例句和 5 道回忆题。

用户答题后，可以继续贴出答案，让 Skill 指出具体问题并给针对性重练。词汇来源和实际输出的回归检查见 [行为测试用例](references/behavior-tests.md)。没有查验可靠词表时，不应把词汇说成精确的高频词或正式等级词表。
