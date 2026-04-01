# Ceiba 设计规范

## 基本信息
- **规范名称**: Ceiba 交互设计规范
- **Figma 文件**: https://www.figma.com/design/bofdyofyvpT23XjdYg0H1D/Ceiba-%E4%BA%A4%E4%BA%92
- **最新更新**: 2025-08-05
- **维护人**: dorrawang

## 组件库结构

### 1. 基础组件

#### 按钮 (Button)
- **类型**: base(基础)、outline(描边)、ghost(幽灵)、text(文字)
- **尺寸**: small(小)、medium(中)、large(大)
- **主题**: default(默认)、primary(主要)、danger(危险)、warning(警告)、success(成功)
- **形状**: rectangle(矩形)、square(方形)、circle(圆形)
- **状态**: normal(默认)、hover(悬浮)、active(点击)、disabled(禁用)
- **图标位置**: prefixIcon(前置)、suffixIcon(后置)、singleIcon(独立)

#### 输入框 (Input)
- **尺寸**: small(小)、medium(中)
- **状态**: normal(默认)、hover(悬浮)、focus(聚焦)、filled(填充)、disabled(禁用)
- **特性**: prefixIcon(前置图标)、suffixIcon(后置图标)、clearable(可清空)、tips(提示)

#### 选择器 (Select)
- **尺寸**: small(小)、medium(中)、large(大)
- **状态**: normal(默认)、hover(悬浮)、focus(聚焦)
- **填充**: filled(填充) / unfilled(无填充)
- **多选**: multiple(支持多选)
- **图标**: prefixIcon(前置图标)

#### 搜索框 (Search)
- **配置**: prefix(前缀图标)、fill(填充)、popup(联想搜索)、multiline(批量搜索)
- **清空**: clearable(可清空)

### 2. 表单组件

#### 多选框 (Checkbox)
- **状态**: checked(已选)、unchecked(未选)、indeterminate(半选)
- **禁用**: disabled

#### 单选框 (Radio)
- **状态**: checked(已选)、unchecked(未选)
- **类型**: radio(圆点)、radioButton(按钮组)

#### 开关 (Switch)
- **尺寸**: medium(中)、large(大)
- **标签**: text(文字标签)、none(无标签)
- **状态**: checked(开启)、loading(加载中)

#### 滑块 (Slider)
- **布局**: horizontal(水平)、vertical(垂直)
- **双游标**: rang(支持双游标)
- **数字输入**: inputnumber(带数字输入框)
- **刻度**: marks(显示刻度)

#### 颜色选择器 (ColorPicker)
- **模式**: bothMonochrome(单色)、bothGradient(渐变色)
- **透明度**: alpha(支持透明通道)
- **格式**: CSS(格式输出)

#### 文本框 (Textarea)
- **自动高度**: autosize
- **限制字符**: maxcharacter

### 3. 数据展示

#### 表格 (Table)
- **尺寸**: medium(中)、large(大)
- **对齐**: left(左对齐)、center(居中)、right(右对齐)
- **固定表头**: fixedrow
- **多选**: check(支持多选)
- **单选**: radio(支持单选)
- **展开图标**: expandIcon
- **单元格类型**: 
  - text(文字)
  - icon(图标)
  - operations(操作)
  - button(按钮)
  - tag(标签)
  - state(状态)
- **斑马纹**: zebra

#### 标签 (Tag)
- **类型**: light(亮色)、dark(深色)、outline(描边)
- **主题**: default、primary、danger、warning、success
- **形状**: square(矩形)
- **关闭**: closable

#### 徽标 (Badge)
- **颜色**: green
- **用途**: 显示未读消息数量、状态指示

#### 分割线 (Divider)
- **布局**: horizontal(水平)、vertical(垂直)
- **样式**: 实线、虚线
- **文字分割线**: 支持文字

### 4. 导航组件

#### 选项卡 (Tabs)
- **位置**: top(顶部)、bottom(底部)、left(左侧)、right(右侧)
- **尺寸**: small(小)、medium(中)、large(大)
- **图标**: icon(支持图标)
- **添加**: add(可添加选项卡)
- **删除**: removable(可删除选项卡)
- **滑动**: chevron(支持滑动)

#### 面包屑 (Breadcrumb)
- **分隔符**: ">"
- **图标**: icon(支持图标)

#### 菜单 (Menu)
- **样式**: light(亮色)
- **展开**: expanded
- **分组**: group(支持分组)
- **子集**: submenu(支持子菜单)

#### 下拉菜单 (Dropdown)
- **箭头**: showArrow(带箭头)
- **主题**: light(亮色)
- **分割线**: divider

### 5. 反馈组件

#### 全局提示 (Message)
- **主题**: success(成功)、error(错误)、warning(警告)、info(提示)、loading(等待)
- **关闭**: closeBtn(关闭按钮)

#### 消息通知 (Notification)
- **主题**: success、default
- **图标**: icon
- **底部按钮**: footerBtn
- **关闭按钮**: closeBtn

#### 对话框 (Dialog)
- **位置**: top-center(上中)
- **关闭按钮**: closeBtn
- **分割线**: divider
- **全屏**: fullscreen

#### 抽屉 (Drawer)
- **位置**: right(右侧)
- **蒙层**: overlay(黑色蒙层)
- **按钮位置**: left(左对齐)

#### 警告 (Alert)
- **主题**: info(提示)
- **图标**: icon
- **关闭**: close
- **操作**: operation
- **描述**: description
- **标题**: title
- **折叠**: collapse

#### 气泡确认框 (Popconfirm)
- **位置**: top-center
- **箭头**: showArrow

### 6. 其他组件

#### 文字提示 (Tooltip)
- **方向**: Top(上)、Bottom(下)、Left(左)、Right(右)
- **内容**: 简单的文本弹窗提示

#### 步骤条 (Steps)
- **布局**: horizontal(横向)、vertical(纵向)
- **状态**: finish(完成)、process(进行中)、default(默认)
- **最后项**: last(最后项样式)

#### 分页 (Pagination)
- **总条数**: totalContent
- **条数设置**: pagesize
- **跳转**: jumper

#### 上传 (Upload)
- **主题**: image(图片上传)
- **状态**: before(上传前)
- **拖拽**: draggable(支持拖拽)

### 7. 表单 (Form)
- **标题位置**: left(左对齐)、right(右对齐)
- **布局**: inline(横向)、vertical(纵向)
- **标题长度**: labelLength
- **必填**: required(显示星号)
- **只读**: readonly
- **说明**: help(帮助文本)
- **状态图标**: statusIcon

## 设计规范特点

### 尺寸系统
- **小尺寸**: small - 适用于密集场景
- **中尺寸**: medium - 默认尺寸
- **大尺寸**: large - 适用于重要操作或突出显示

### 状态系统
所有组件都遵循统一的状态定义:
- **normal**: 默认状态
- **hover**: 鼠标悬浮
- **active**: 点击激活
- **focus**: 聚焦状态
- **disabled**: 禁用状态
- **checked**: 选中状态
- **indeterminate**: 半选状态

### 主题色系
- **primary**: 主要色(品牌色)
- **success**: 成功色(绿色)
- **warning**: 警告色(橙色)
- **danger**: 危险色(红色)
- **default**: 默认色(中性灰)
- **info**: 提示色(蓝色)

### 圆角规范
- 按钮: 3px (矩形)、4px (方形)
- 输入框: 3px
- 标签: 6px
- 其他组件: 4px

### 间距规范
- 组件内间距: 8px, 12px, 16px
- 组件外间距: 8px, 12px, 16px, 24px

## 设计原则

### 一致性
- 所有组件遵循统一的尺寸、颜色、状态系统
- 交互行为保持一致

### 可访问性
- 清晰的视觉反馈(状态变化)
- 合适的点击区域
- 良好的对比度

### 灵活性
- 组件支持多种变体和配置
- 可组合使用

### 可维护性
- 组件库结构清晰
- 命名规范统一
