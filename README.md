## 简介

本系列介绍从零开始搭建商业级语音合成系统（TTS合成系统）。

选择加入可获得：

* 构建TTS，情感TTS的方法
* 构建风格控制的TTS方法
* 构建超拟人TTS的方法
* 语音合成问题深度解答

<img src="https://zlunai.com/wp-content/uploads/2024/12/2024122809312537.png" style="width:300px" />

## 1. 快速入门

了解语音合成系统的技术发展方向及其特点，例如情感非情感TTS, Prompt TTS和超拟人TTS等。

[1.1 我们应该如何开始进行TTS系统的构建？](https://articles.zsxq.com/id_dmk3c1s5aqut.html)

## 2. TTS数据准备

构建TTS合成系统需要的训练数据是决定系统能否构建成功的关键，通过本章节你可以学会如何构建、处理数据等关键问题。

[2.1 我需要准备什么样的数据？](https://articles.zsxq.com/id_887wrb4fdmja.html) - 掌握需要什么样的数据才能构建一个商业级的TTS系统。

[2.2 如何进行录音文本制作？](https://articles.zsxq.com/id_a0ot7xm56mhz.html) - 掌握制订录音文本的方法，确保模型构建质量和录音效果。

[2.3 如何进行正确录音？](https://articles.zsxq.com/id_sirt95pecw78.html) - 掌握录音技巧和规范，确保录音效果。

[2.4 如何剪辑录音？](https://articles.zsxq.com/id_wwdzri0xam1h.html) - 掌握剪辑录音的方法和注意事项，确保获取高质量录音用于模型训练。

## 3. TTS录音文本处理

[3.1 中文文本转拼音](https://articles.zsxq.com/id_f4f03z1eks3k.html) - 掌握如何使用非模型方式将中文文本序列转换为拼音序列。

[3.2 pypinyin错误拼音修复](https://articles.zsxq.com/id_juqu40pl8vde.html) -掌握修复pypinyin转汉字为拼音时拼音转错的方法。

[3.3 中文Grapheme与Phoneme](https://articles.zsxq.com/id_lig4xd1cmzl8.html) - 掌握中文Grapheme与Phoneme的关系和处理方法。

[3.4 为什么要把汉语拼音拆分为（声母，韵母音调）的方式？](https://articles.zsxq.com/id_bi2xlibfugs5.html) - 了解TTS中汉语拼音的处理方式。

3.5 多音字如何处理？

3.6 儿化音如何处理？

3.7 特殊音调如何处理？

3.8 如何将汉语拼音转换为音素（Phoneme）

3.9 如何在生成的音素中增加韵律信息？

## 4. TTS音频文件处理

4.1 如何获取音频Mel谱信息？

4.2 如何获取音量信息（Energy）？

4.3 如何获取基频信息（F0）？

## 5. TTS模型构建
## 6. 情感TTS构建
## 7. Prompt TTS构建
## 8. 超拟人TTS构建
## 9.常见问题

