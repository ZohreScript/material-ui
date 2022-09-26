# Palette 调色板

<p class="description">通过一些实用的颜色程序类的颜色传达意义。 这也包括了支持带悬停状态（hover states）的样式链接。</p>

## Color 颜色

{{"demo": "Color.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ color: 'primary.main' }}>…
<Box sx={{ color: 'secondary.main' }}>…
<Box sx={{ color: 'error.main' }}>…
<Box sx={{ color: 'warning.main' }}>…
<Box sx={{ color: 'info.main' }}>…
<Box sx={{ color: 'success.main' }}>…
<Box sx={{ color: 'text.primary' }}>…
<Box sx={{ color: 'primary.main' }}>…
<Box borderColor="secondary.main">…
<Box borderColor="error.main">…
<Box borderColor="grey.500">…
<Box borderColor="text.primary">…
<Box sx={{ color: 'secondary.main' }}>…
<Box sx={{ color: 'error.main' }}>…
<Box sx={{ color: 'warning.main' }}>…
<Box sx={{ color: 'info.main' }}>…
<Box sx={{ color: 'success.main' }}>…
<Box sx={{ color: 'primary.main' }}>…
<Box borderColor="secondary.main">…
<Box borderColor="error.main">…
<Box borderColor="grey.500">…
<Box borderColor="text.primary">…
<Box sx={{ color: 'secondary.main' }}>…
<Box sx={{ color: 'error.main' }}>…
<Box sx={{ color: 'warning.main' }}>…
<Box sx={{ color: 'info.main' }}>…
<Box sx={{ color: 'success.main' }}>…
<Box sx={{ color: 'primary.main' }}>…
<Box borderColor="secondary.main">…
<Box borderColor="error.main">…
<Box borderColor="grey.500">…
<Box borderColor="text.primary">…
<Box sx={{ color: 'secondary.main' }}>…
<Box sx={{ color: 'error.main' }}>…
<Box sx={{ color: 'warning.main' }}>…
<Box sx={{ color: 'info.main' }}>…
<Box sx={{ color: 'success.main' }}>…
<Box sx={{ color: 'primary.main' }}>…
<Box borderColor="secondary.main">…
<Box borderColor="error.main">…
<Box borderColor="grey.500">…
<Box borderColor="text.primary">…
<Box sx={{ color: 'secondary.main' }}>…
<Box sx={{ color: 'error.main' }}>…
<Box sx={{ color: 'warning.main' }}>…
<Box sx={{ color: 'info.main' }}>…
<Box sx={{ color: 'success.main' }}>…
<Box sx={{ color: 'text.primary' }}>…
<Box sx={{ color: 'text.secondary' }}>…
<Box sx={{ color: 'text.disabled' }}>…
<Box sx={{ color: 'text.secondary' }}>…
<Box sx={{ color: 'text.disabled' }}>…
<Box sx={{ color: 'text.secondary' }}>…
<Box sx={{ color: 'text.disabled' }}>…
<Box sx={{ color: 'text.secondary' }}>…
<Box sx={{ color: 'text.disabled' }}>…
<Box sx={{ color: 'text.disabled' }}>…
```

## 背景颜色

{{"demo": "BackgroundColor.js", "defaultCodeOpen": false}}

```jsx
<Box sx={{ bgcolor: 'primary.main' }}>…
<Box sx={{ bgcolor: 'secondary.main' }}>…
<Box sx={{ bgcolor: 'error.main' }}>…
<Box sx={{ bgcolor: 'warning.main' }}>…
<Box sx={{ bgcolor: 'info.main' }}>…
<Box sx={{ bgcolor: 'success.main' }}>…
<Box sx={{ bgcolor: 'primary.main' }}>…
<Box borderColor="secondary.main">…
<Box borderColor="error.main">…
<Box borderColor="grey.500">…
<Box borderColor="text.primary">…
<Box sx={{ bgcolor: 'secondary.main' }}>…
<Box sx={{ bgcolor: 'error.main' }}>…
<Box sx={{ bgcolor: 'warning.main' }}>…
<Box sx={{ bgcolor: 'info.main' }}>…
<Box sx={{ bgcolor: 'success.main' }}>…
<Box sx={{ bgcolor: 'primary.main' }}>…
<Box borderColor="secondary.main">…
<Box borderColor="error.main">…
<Box borderColor="grey.500">…
<Box borderColor="text.primary">…
<Box sx={{ bgcolor: 'secondary.main' }}>…
<Box sx={{ bgcolor: 'error.main' }}>…
<Box sx={{ bgcolor: 'warning.main' }}>…
<Box sx={{ bgcolor: 'info.main' }}>…
<Box sx={{ bgcolor: 'success.main' }}>…
<Box sx={{ bgcolor: 'primary.main' }}>…
<Box borderColor="secondary.main">…
<Box borderColor="error.main">…
<Box borderColor="grey.500">…
<Box borderColor="text.primary">…
<Box sx={{ bgcolor: 'secondary.main' }}>…
<Box sx={{ bgcolor: 'error.main' }}>…
<Box sx={{ bgcolor: 'warning.main' }}>…
<Box sx={{ bgcolor: 'info.main' }}>…
<Box sx={{ bgcolor: 'success.main' }}>…
<Box sx={{ bgcolor: 'primary.main' }}>…
<Box borderColor="secondary.main">…
<Box borderColor="error.main">…
<Box borderColor="grey.500">…
<Box borderColor="text.primary">…
<Box sx={{ bgcolor: 'secondary.main' }}>…
<Box sx={{ bgcolor: 'error.main' }}>…
<Box sx={{ bgcolor: 'warning.main' }}>…
<Box sx={{ bgcolor: 'info.main' }}>…
<Box sx={{ bgcolor: 'success.main' }}>…
<Box sx={{ bgcolor: 'text.primary' }}>…
<Box sx={{ bgcolor: 'text.secondary' }}>…
<Box sx={{ bgcolor: 'text.disabled' }}>…
<Box sx={{ bgcolor: 'text.secondary' }}>…
<Box sx={{ bgcolor: 'text.disabled' }}>…
<Box sx={{ bgcolor: 'text.secondary' }}>…
<Box sx={{ bgcolor: 'text.disabled' }}>…
<Box sx={{ bgcolor: 'text.secondary' }}>…
<Box sx={{ bgcolor: 'text.disabled' }}>…
<Box sx={{ bgcolor: 'text.secondary' }}>…
<Box sx={{ bgcolor: 'text.disabled' }}>…
```

## API

```js
import { palette } from '@mui/system';
```

| 导入名称      | 属性        | CSS 属性            | Theme key                                                                    |
|:--------- |:--------- |:----------------- |:---------------------------------------------------------------------------- |
| `color`   | `color`   | `color`           | [`palette`](/material-ui/customization/default-theme/?expand-path=$.palette) |
| `bgcolor` | `bgcolor` | `backgroundColor` | [`palette`](/material-ui/customization/default-theme/?expand-path=$.palette) |