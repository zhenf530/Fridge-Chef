# 🥗 冰箱食谱助手 | Fridge Chef

> 打开冰箱，看看有什么，剩下的交给 Claude～ 🧑‍🍳✨
> *Open the fridge, see what's inside, and let Claude do the rest!*

![HTML](https://img.shields.io/badge/made%20with-HTML%20%2B%20JS-ff9f43?style=flat-square)
![Powered by Claude](https://img.shields.io/badge/powered%20by-Claude-8e6bd8?style=flat-square)
![No build needed](https://img.shields.io/badge/no%20build-just%20one%20file-2f7d57?style=flat-square)

---

## 🌱 这是什么 | What is this?

**中文**
一个简单好用的食谱助手 🍃
把冰箱里的食材告诉它，它就会帮你排出**抗炎、减脂、好做**的中式家常菜单，还会写清楚每一步怎么做。
快坏的食材会被优先安排，不浪费一点点 🥬

**English**
A tiny, cozy recipe helper 🍃
Tell it what's in your fridge, and it plans **anti-inflammatory, light, easy-to-cook** Chinese home-style meals, with clear step-by-step instructions.
Ingredients that are about to go bad get used first, so nothing goes to waste 🥬

---

## 🍳 功能 | Features

| | 中文 | English |
|---|---|---|
| 🧺 | 添加、删除食材，浏览器会记住你的冰箱 | Add or remove ingredients; your fridge is remembered in the browser |
| ⏰ | 点一下标记「快坏了」，生成时优先用掉 | Tap to mark "expiring soon" so they get used first |
| 🍚 | （自定义）午饭有米饭，晚饭不吃米饭 | Rice at lunch, no rice at dinner |
| 🥢 | 每餐一个荤素同炒，晚饭再配一碗汤 | One stir-fry of meat plus veggies per meal, plus a soup at dinner |
| 🎯 | 目标可选：抗炎减脂、高蛋白、病后清淡 | Goals: anti-inflammatory fat loss, high protein, or light recovery meals |
| 🌶️ | 口味可选：家常、川味、粤式、江浙 | Tastes: home-style, Sichuan, Cantonese, Jiangzhe |
| 🔄 | 每道菜可以「换一道」「更清淡」「更快手」「更饱腹」 | Per dish: swap it, make it lighter, quicker, or more filling |
| 💬 | 直接说"大葱用完了"或"不想吃牛肉"，马上改 | Just say "no more scallions" or "no beef today" and it adapts |
| 🛒 | 自动汇总需要补买的东西 | Auto-collected shopping list for missing items |

---

## 🚀 怎么用 | How to use

1. 🧺 **检查冰箱**：增删食材，把快坏的点成红色
   *Check your fridge: add or remove items, tap the ones expiring soon*
2. 🎛️ **选偏好**：天数、目标、口味，想说的话写在备注里
   *Pick your preferences: days, goal, taste, and any extra notes*
3. ✨ **点「生成食谱」**：等半分钟左右
   *Hit "Generate" and wait about half a minute*
4. 🔧 **不满意就调整**：用每张卡片下面的按钮或输入框
   *Not quite right? Use the buttons or text box under each card*
5. 👩‍🍳 **开饭！**
   *Dig in!*

---

## ⚠️ 小小提醒 | A little heads-up

**中文**
"生成食谱"这个功能依靠 **claude.ai** 提供的 Claude 调用能力。
所以把这个页面放到 GitHub Pages 或自己的服务器上时，页面可以正常打开、管理食材，但**不能生成食谱**，会提示"请在 claude.ai 里打开"。
想真正使用，请打开 claude.ai 上发布的版本 👉 [点这里](https://claude.ai/artifact/MKdPhZKufYJ8tqmT1ZMVzW)
生成时会用到你自己的 Claude 额度，第一次点击会弹出授权窗口，选择允许就好。

**English**
The "Generate" feature relies on Claude access provided by **claude.ai**.
If you host this page on GitHub Pages or your own server, it will open and let you manage ingredients, but **it can't generate recipes** and will ask you to open it in claude.ai.
To actually use it, open the published version on claude.ai 👉 [here](https://claude.ai/artifact/MKdPhZKufYJ8tqmT1ZMVzW)
Generation uses your own Claude usage, and the first click shows a permission prompt. Just allow it.

---

## 🧩 文件结构 | Project structure

```
fridge-chef/
├── fridge-chef.html   ← 全部代码都在这一个文件里 🎁 (everything lives in this one file)
└── README.md          ← 你正在看的这个 📖 (you are here)
```

没有依赖，不用安装，不用构建 🪄
*No dependencies, no install, no build step* 🪄

---

## 🔮 未来想做 | Maybe someday

- [ ] 🍽️ 做完一道菜，自动从冰箱里划掉用到的食材 / *Auto-remove used ingredients after cooking*
- [ ] 📅 食材保质期提醒 / *Expiry date reminders*
- [ ] 🌍 独立版本，使用自己的 API Key 脱离 claude.ai / *Standalone version with your own API key*
- [ ] 📸 拍照识别冰箱里的食材 / *Recognize ingredients from a fridge photo*

---

## 🩺 免责声明 | Disclaimer

**中文**：食谱由 AI 生成，仅供日常参考，不能代替医生或营养师的建议。有疾病、过敏或特殊饮食要求时，请先咨询专业人士 💚

**English**: Recipes are AI-generated for everyday reference only and are not a substitute for advice from a doctor or dietitian. If you have a medical condition, allergies, or special dietary needs, please consult a professional first 💚

---

<p align="center">
  Made with 🥬 + 🍤 + ☕ and a little help from Claude
  <br>
  祝你每一餐都吃得开心！ 🍚✨
  <br>
  <i>Wishing you happy, healthy meals!</i>
</p>
