:: BASE_DOC ::

## API
### Navbar Props

名称 | 类型 | 默认值 | 说明 | 必传
-- | -- | -- | -- | --
className | String | - | 类名 | N
style | Object | - | 样式，TS 类型：`React.CSSProperties` | N
animation | Boolean | true | 是否添加动画效果 | N
background | String | - | 背景 | N
fixed | Boolean | true | 是否固定在顶部 | N
homeIcon | TNode | - | 首页图标。值为 true 表示显示默认返回图标，值为 false 表示不显示首页图标，值为其他表示自定义图标。TS 类型：`boolean | TNode`。[通用类型定义](https://github.com/Tencent/tdesign-mobile-react/blob/develop/src/common.ts) | N
leftIcon | TNode | false | 左侧图标。值为 true 表示显示默认返回图标，值为 false 表示不显示左侧图标，值为其他表示自定义图标。TS 类型：`boolean | TNode`。[通用类型定义](https://github.com/Tencent/tdesign-mobile-react/blob/develop/src/common.ts) | N
rightIcon | TElement | - | 右侧图标，可自定义。TS 类型：`TNode`。[通用类型定义](https://github.com/Tencent/tdesign-mobile-react/blob/develop/src/common.ts) | N
title | TNode | - | 页面标题。TS 类型：`string | TNode`。[通用类型定义](https://github.com/Tencent/tdesign-mobile-react/blob/develop/src/common.ts) | N
titleMaxLength | Number | - | 标题文字最大长度，超出的范围使用 `...` 表示 | N
visible | Boolean | true | 是否显示 | N
onHomeClick | Function |  | TS 类型：`() => void`<br/>点击 home 图标时触发 | N
onLeftClick | Function |  | TS 类型：`() => void`<br/>点击左边按钮时触发 | N
