### login npm
```sh
  npm login
```

### publish
```sh
  npm pusblish --access public
```
<hr/>

<br/>
<br/>


### usage
```sh
  npm install @pereiraadiel/sum-js@1.0.1
```

file: test.ts
```ts
import Test from '@pereiraadiel/sum-js';

const sum = new Test.Sum();

console.log(sum.execute(1,1));
```