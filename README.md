# HTM_Team_Data
```markdown
# WIP 😇: Will be implementing, Post Features soon
```
This is an API Service to CRUD Core team data.
<br/>
Helps you to get team data.
```js
const Team_GitHub = `https://sudan-s-tech.github.io/HTM_Team_Data/team/cleandata.json`;

let res = await Axios({
      method: "GET",
      url: Team_GitHub,
      headers: { "Content-Type": "application/json" }
    });

let { data } = res;
console.log(data);
```

Helps you to get OpCodes ( Card Color and Font Color) Configuration based on designation/ role.

```js
const Team_Opcodes = `https://sudan-s-tech.github.io/HTM_Team_Data/opcodes/opcode.json`;

let res = await Axios({
      method: "GET",
      url: Team_Opcodes,
      headers: { "Content-Type": "application/json" }
    });

let { data } = res;
console.log(data);
```
