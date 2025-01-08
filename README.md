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

[3.1 使用Text Normalization处理文本中的时间、分数、数字等](https://articles.zsxq.com/id_ckm3qjukufcr.html) - 掌握中文文本标准化的方法。

[3.2 如何在中文文本中增加韵律信息？](https://articles.zsxq.com/id_bmrwm69f90rc.html) - 掌握在汉语文本中增加不同韵律的方法。

[3.3 中文文本转拼音](https://articles.zsxq.com/id_f4f03z1eks3k.html) - 掌握如何使用非模型方式将中文文本序列转换为拼音序列。

[3.4 pypinyin错误拼音修复](https://articles.zsxq.com/id_juqu40pl8vde.html) -掌握修复pypinyin转汉字为拼音时拼音转错的方法。

[3.5 多音字如何处理？](https://articles.zsxq.com/id_i6spgbgn7owb.html) - 掌握TTS合成语音时，遇到多音字时的处理方法。

3.6 儿化音如何处理？

3.7 特殊音调如何处理？

[3.8 中文Grapheme与Phoneme](https://articles.zsxq.com/id_lig4xd1cmzl8.html) - 掌握中文Grapheme与Phoneme的关系和处理方法。

[3.9 为什么要把汉语拼音拆分为（声母，韵母音调）的方式？](https://articles.zsxq.com/id_bi2xlibfugs5.html) - 了解TTS中汉语拼音的处理方式。

[3.10 如何将汉语拼音转换为音素（Phoneme）？](https://articles.zsxq.com/id_6qixlk4ggguv.html) - 掌握将拼音转换为对应音素的方法。

## 4. TTS音频文件处理

[4.1 音频采样率（Sample Rate）基础](https://articles.zsxq.com/id_b5d1j92663ve.html) - 了解音频采样率在读音音频信息时的作用。

4.2 如何获取音频Mel谱信息？

4.3 如何获取音量信息（Energy）？

4.4 如何获取基频信息（F0）？

## 5. TTS模型构建

在本章节中，我们将以VITS 2为项目案例讲解如何构建非情感的TTS模型。

[5.1 TTS模型的两种基本架构](https://articles.zsxq.com/id_pvx2f6ms3rze.html) - 了解TTS的两种架构是什么，它们之间有什么区别。

[5.2 训练配置文件构建与解析](https://articles.zsxq.com/id_swt2rsmuaiq6.html) - 掌握构建TTS模型时配置文件的构建与解析过程。

## 6. 情感TTS构建
## 7. Prompt TTS构建
## 8. 超拟人TTS构建
## 9. 语音合成标记语言 (SSML)
## 10.常见问题

[10.1 可以使用被压缩后的音频文件来训练TTS模型吗？](https://articles.zsxq.com/id_hpwjic5wf55m.html) - 获知能否使用压缩音频构建TTS模型的答案及其原因。

[10.2 怎么解决TTS合成语音时合成语音不能停下来的问题？](https://articles.zsxq.com/id_zxd16p94gkcl.html) - 获取TTS合成语音不能停下来的原因和解决方案。


