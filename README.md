# HTM_Team_Data

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
