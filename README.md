# 欢迎来到Pallas-Bot的帮助页面

## 目录

- ## [-项目简介](#项目简介)

- ## [-插件列表](#插件列表)

- ## [-使用帮助](#使用帮助)

## [项目简介](#-项目简介)

这是牛牛的私人版哦，原版在[Pallas-Bot](https://github.com/MistEO/Pallas-Bot)，是一款~~智能~~的~~全功能~~机器人。

这版牛牛在原版的基础上添加了许多nonebot的插件，以实现各种功能！其实本牛牛也就是个**小众**的自用机器人罢了（千万不要拿牛牛干奇怪的事情啊！！！）

## [插件列表](#-插件列表)

---原生插件---

- [roulette](#轮盘抽奖roulette)
- [greeting](#进群问候greeting)
- [repeater](#复读机repeater)
- [drink](#酒后乱性drink)

---额外插件---

- [nonebot_plugin_naturel_gpt](#更人性化拟人的gpt聊天nonebot_plugin_naturel_gpt)
- [nonebot_plugin_skland_arksign](#森空岛自动签到nonebot-plugin-skland-arksign)
- [nonebot_plugin_arktools](#明日方舟小工具箱插件nonebot_plugin_arktools)
- [nonebot_plugin_withdraw](#简单撤回插件nonebot_plugin_withdraw)
- [nonebot_plugin_youthstudy](#青年大学习插件nonebot_plugin_youthstudy)

## [使用帮助](#-使用帮助)

### 轮盘抽奖[roulette](https://github.com/MistEO/Pallas-Bot)

这个功能需要牛牛拥有**管理权限**才能使用!也就是得牛牛是**管理员**才行

#### 开启新游戏

`牛牛轮盘`
>激活默认模式

`牛牛轮盘禁言/踢人`
>开启禁言/踢人模式轮盘

#### 开枪

`牛牛开枪`

### 进群问候[greeting](https://github.com/MistEO/Pallas-Bot)

没有触发词嘞,有人进群就会欢迎

### 复读机[repeater](https://github.com/MistEO/Pallas-Bot)

嘿嘿这个也没有触发词,有人说话就开始学了

**所以!!!**

牛牛的说什么完全依赖于大家聊什么，希望大家不要故意教牛牛一些不好的东西。发现牛牛学了一些不合适的话及时帮忙删除。
>群管理对着牛牛说的话**回复**`不可以`牛牛就不学这个话力

大家一起教出更棒更聪明的牛牛！✿✿ヽ(°▽°)ノ✿

### 酒后乱性[drink](https://github.com/MistEO/Pallas-Bot)

`牛牛喝酒`
>进入醉酒状态

醉酒状态下牛牛的发言频率会大幅度增加!

~~给牛牛灌很多酒后牛牛可能断片哦~~

### 更人性化(拟人)的GPT聊天[nonebot_plugin_naturel_gpt](https://github.com/KroMiose/nonebot_plugin_naturel_gpt)

日常使用中at牛牛并加上要说的话就可以激活了

`rg <on|off>`
>会话人格开关

`/rg [help]`
>查看当前可用的预设

`/rg help -admin`
>查看管理员帮助(全局命令只有超管能用哦)

`/rg new <preset_key> <preset_intro>`
>添加人格 | preset_key - 人格名 | preset_intro - 人格自我介绍 |

`/rg edit <preset_key> <preset_intro>`
>编辑人格预设 | preset_key - 人格名 | preset_intro - 人格自我介绍 |

`/rg del <preset_key>`
>人格删除 | preset_ket - 人格名 |

`/rg rename <old_preset_key> <new_preset_key>`
>人格重命名 | old_preset_key - 旧人格名 | new_preset_key - 新人格名 |

`rg query <preset_key>`
>人格查询 | preset_key - 人格名 |

`rg reset <preset_key>`
>重置会话人格 (清除除人设外的所有记忆和上下文) | preset_key - 人格名 |

### 森空岛自动签到[nonebot-plugin-skland-arksign](https://github.com/GuGuMur/nonebot-plugin-skland-arksign)

#### 添加账户(可以在群里也可私聊)

``skland add 舟游戏ID [森空岛token] [-n 可选备注]``

> 在群聊中使用时，一定不要带上token，否则会有盗号风险\
> 缺少的token会在私聊中补充：[使用 bind 命令]\
> `舟游戏ID`指的是你名字下面那串**数字**！\
>备注栏建议填自己的**游戏昵称**记得带数字

#### 私聊补充token

``skland bind \<token>``

#### Token获取  

- 登入[森空岛官网](https://www.skland.com/)</br>
- 进入[这个网页](https://web-api.skland.com/account/info/hg)获取你的Token

```html
{
  "code": 0,
  "data": {
    "content": "<Token>"
  },
  "msg": "接口会返回您的鹰角网络通行证账号的登录凭证，此凭证可以用于鹰角网络账号系统校验您登录的有效性。泄露登录凭证属于极度危险操作，为了您的账号安全，请勿将此凭证以任何形式告知他人！"
}
```

#### 删除账号

``skland del 舟游戏ID/备注``

#### 立即手动签到

``skland signin 舟游戏ID/备注``

只能手动签到自己的哦

### 明日方舟小工具箱插件[nonebot_plugin_arktools](https://github.com/NumberSir/nonebot_plugin_arktools)

#### 功能实现

- 可以查询推荐的公招标签(截图识别/手动输文字)
- 可以查询干员的技能升级材料、专精材料、精英化材料、模组升级材料
- 可以通过网易云点歌，以卡片形式发送
- 猜干员小游戏，玩法与 wordle 相同
- 可以查看生日为今天的干员
- 可以记录当前理智，等回复满后提醒
- ~~指定群聊自动推送最新游戏公告~~
- 查询、订阅、推送 MAA 作业站的作业

`方舟帮助/arkhelp`
>查看指令列表

#### 猜干员小游戏

`猜干员`
>开始新游戏

`#[干员名]`
>猜干员，如：#艾雅法拉

`提示`
>查看答案干员的信息

`结束`
> 结束当前局游戏

#### 干员生日

`今日干员`
>查看今天过生日的干员

#### 塞壬点歌

`塞壬点歌 [关键字]`
>网易云点歌，以卡片形式发到群内

#### 干员信息查询

`干员 [干员名]`
>查看干员的精英化、技能升级、技能专精、模组解锁需要的材料

#### 公开招募查询

`公招 [公招界面截图]`\
`回复截图：公招`\
`公招 [标签1] [标签2] ...`
>查看标签组合及可能出现的干员

#### 理智提醒

>注意!这个不是游戏内的真实理智,是假定的!实际是个计时器

`理智提醒 [当前理智] [回满理智]`
>默认记当前理智为0，回满到135时提醒

`理智查看`
>查看距离理智回满还有多久，以及当期理智为多少

#### ~~公告推送~~

>目前该功能请求的网站好像有点问题?

这个功能找**超管**添加嗷

#### MAA 作业站相关

`maa添加订阅 / ADDMAA [关键词1 关键词2 ...]`
> 添加自动推送的关键词

`maa删除订阅 / DELMAA [关键词1 关键词2 ...]`
>删除自动推送的关键词

`maa查看订阅 / GETMAA`
>查看本群自动推送的关键词

`maa查作业 [关键词1 关键词2 ...] | [热度/最新/访问]`
> 按关键词组合查作业，默认为最新发布的第一个作业,可指定按什么顺序查询

### 简单撤回插件[nonebot_plugin_withdraw](https://github.com/noneplugin/nonebot-plugin-withdraw)

`/撤回 [num]`
>撤回发送的倒数第num条消息(num从0开始)\
>不填num值的时候撤回最后一条

`要撤回的消息回复:撤回`
>撤回指定消息

### 青年大学习插件[nonebot_plugin_youthstudy](https://github.com/ayanamiblhx/nonebot_plugin_youthstudy)

`大学习帮助`
>获取命令列表

`青年大学习/大学习`
>获取大学习答案

`开启/关闭大学习推送`
>在群聊中仅有超级用户能开启推送，私聊任何人都能开启推送，但需要加好友

`大学习截图`
>获取主页截图

`完成截图`
>获取大学习完成截图
