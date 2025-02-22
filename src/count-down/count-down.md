:: BASE_DOC ::

## API
### CountDown Props

名称 | 类型 | 默认值 | 说明 | 必传
-- | -- | -- | -- | --
className | String | - | 类名 | N
style | Object | - | 样式，TS 类型：`React.CSSProperties` | N
autoStart | Boolean | true | 是否自动开始倒计时 | N
content | TNode | 'default' | 最终倒计时的展示内容，值为'default'时使用默认的格式，否则使用自定义样式插槽。TS 类型：`string | TNode`。[通用类型定义](https://github.com/Tencent/tdesign-mobile-react/blob/develop/src/common.ts) | N
format | String | HH:mm:ss | 时间格式，DD-日，HH-时，mm-分，ss-秒，SSS-毫秒 | N
millisecond | Boolean | false | 是否开启毫秒级渲染 | N
size | String | 'small' | 倒计时尺寸。可选项：small/medium/large | N
splitWithUnit | Boolean | false | 使用时间单位分割 | N
theme | String | 'default' | 倒计时风格。可选项：default/round/square | N
time | Number | - | 必需。倒计时时长，单位毫秒 | Y
onChange | Function |  | TS 类型：`(time: TimeData) => void`<br/>时间变化时触发。[详细类型定义](https://github.com/Tencent/tdesign-mobile-react/tree/develop/src/count-down/type.ts)。<br/>`interface TimeData {  days: number; hours: number; minutes: number; seconds: number; milliseconds: number }`<br/> | N
onFinish | Function |  | TS 类型：`() => void`<br/>倒计时结束时触发 | N
