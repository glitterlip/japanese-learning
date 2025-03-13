# Gemini
> 国内的AI目前英语听说基本没问题,但是没发现一个能听说日语的😭

谷歌大善人,AI Studio,[地址](https://aistudio.google.com/apikey) 大部分模型每天100w token,新的多模态模型 `gemini-2.0-flash-exp` 支持日语对话

最主要的配合大佬的项目[gemini-next-chat](https://github.com/u14app/gemini-next-chat),一键部署到vercel,绑定个域名可以直接使用

[我部署的](https://gemininextchat.tonihon.top/)

## 使用方法

### 获取API key

[地址](https://aistudio.google.com/apikey)

### 配置

[打开网站](https://gemininextchat.tonihon.top/),打开设置

注意模型必须选`gemini-2.0-flash-exp`,目前只有这个模型支持对话


<img width="575" alt="Screenshot 2025-03-13 at 22 37 20" src="https://github.com/user-attachments/assets/99600c30-af7b-4d66-a4ee-acbc3a27d43c" />

配置好以后点击右下角voice mode即可

**缺点是依旧要翻墙,国内被禁止访问,只能说日语和英语,中文会降智成🦍**

优点也很明显,chatgpt api收费,这个免费,可以集成到自己的网站,做个`websocket relay`就可以
