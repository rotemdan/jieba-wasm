# v2.0.0
- Switch to exports field instead of subpath import [(#6)](https://github.com/fengkx/jieba-wasm/pull/6)

Instead of
```javascript
import init, {cut} from 'jieba-wasm/pkg/web/jieba_rs_wasm';
```
Use 
```typescript
import init, {cut} from 'jieba-wasm';
```

More info on exports field https://nodejs.org/api/packages.html#community-conditions-definitions and typescript [customCondition config](https://nodejs.org/api/packages.html#community-conditions-definitions)


# v1.0.0
- Stable semver version
- compress data at build time shrink wasm about 3MB
- add deno build at `pkg/deno` dir
- add better documentation and github page playground
