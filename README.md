### Hi there! Welcome to Borja's profile
Hi, I'm Borja Alonso-Majagranzas 🙋🏻‍♂️, a pasionate self-taught full-stack web and app developer from Spain.

```js
const { isOnline } = require('@balonsom/activity');

module.exports = {
  name: 'Borja Alonso-Majagranzas',
  email: 'balonso@hubenue.com',
  aliases: ['Me', 'balonsom'],
  languages: ['Javascript', 'Typescript', 'HTML', 'PHP', 'CSS', 'Java'],
  dailyKnowledge: ['Node', 'React', 'React Native', 'Electron', 'Mongoose', 'GraphQL', 'Express', 'Laravel'],
  getStatus: async () => {
    const online = await isOnline();
    return `Borja is currently ${online ? '👀 online' : '😴 offline, try to reach him through his email'}.`;
  },
};
```

<!--
**balonsom/balonsom** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
