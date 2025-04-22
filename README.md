# library-starter

Features:

- Bundle with [tsup](https://github.com/egoist/tsup)
- Test with [vitest](https://vitest.dev)

# Usage

### 安装

```bash
pnpm add @oiij/ai-editor
```

### 使用

```vue
<script setup lang="ts">
import { useAiEditor } from '@oiij/ai-editor'
const { domRef } = useAiEditor()
</script>

<template>
  <div ref="domRef" style="width: 100%; height: 100%;" />
</template>
```

pnpm link --global <package name>

```

## License

MIT
```
