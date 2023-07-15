# Korean-Syllable

Korean-Syllable is the module that make any korean syllable.

- github: https://github.com/jacealan/korean-syllable
- npm: https://www.npmjs.com/package/korean-syllable

# Installation

```shell
npm install korea-syllable
```

# Usage

## Importing Korean-Syllable

```js
import { koreanSyllable } from "korean-syllable"
```

## Making any korean syllable(s)

### 1 syllable

```ts
const ex: string = koreanSyllable()
console.log(ex) // 촒
```

### more syllables

```ts
const length: number = 10
const ex: string = koreanSyllable(length)
console.log(ex) // 줩뇅쳱펻뻘껨즰쌍쉁뺼죓
```

`length` is the length of syllables

### with space

```ts
const length: number = 10
const withspace: boolean = true
const ex: string = koreanSyllable(length, withspace)
console.log(ex) // 둎찍굍 뺍푡롁 쯚럔
```

## references

- https://github.com/pengooseDev/goose
- https://ko.wikipedia.org/wiki/%ED%95%9C%EA%B8%80_%EC%9D%8C%EC%A0%88
- https://jsikim1.tistory.com/161
- https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/Math/random
