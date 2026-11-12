# 查词 / Word Lookup

一个单文件的英汉查词小工具：英文查中文、中文查英文，中文释义、词性、美/英发音，支持按字母拼写和四步记单词。

Live: https://qishenmeqi.github.io/word-lookup/

## 说明

- 内置约 27,000 个常用词，离线可查
- 中文查英文：输入中文，按词条的中文释义反查英文词，主释义优先
- 词库数据来自 [ECDICT](https://github.com/skywind3000/ECDICT)（MIT License）
- 音节拆分数据来自 [cmu-syllable-counter](https://www.npmjs.com/package/cmu-syllable-counter) / CMU Pronouncing Dictionary
- 发音使用浏览器 SpeechSynthesis
- 生僻词联网查词使用 dictionaryapi.dev 与 MyMemory
