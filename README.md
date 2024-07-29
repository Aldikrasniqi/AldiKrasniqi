### Hi I'm Aldi Krasniqi 
- 🌱 I’m learning advanced techniques for performance-driven programming in js at the moment.
- ⚡ Fun fact: Im a Fisher, Downhill biker and League of legends proffesional player.

```
  function workLifeBalance(task: string, mood: string = 'neutral'): string {
    /**
     * A function to balance work and fun for front-end engineers.
     * 
     * Args:
     * - task (string): The task to execute.
     * - mood (string): Your current mood. Default is 'neutral'.
     * 
     * Returns:
     * - string: A fun yet professional message.
     */
    
    const funEmojis: { [key: string]: string } = {
        'happy': '😄',
        'neutral': '😐',
        'frustrated': '😤'
    };

    const professionalAdvice: { [key: string]: string } = {
        'happy': "Awesome! Keep that energy while debugging.",
        'neutral': "Stay focused, a balanced approach is key.",
        'frustrated': "Take a deep breath, maybe a walk outside will help."
    };

    if (!(mood in funEmojis)) {
        return "Invalid mood! Please choose between 'happy', 'neutral', or 'frustrated'.";
    }

    return `Task to complete: ${task} ${funEmojis[mood]}. Advice: ${professionalAdvice[mood]}`;
}

const message: string = workLifeBalance("Refactor the CSS grid layout", "happy");
console.log(message);
```


<h3>Things I code with</h3>
<p>
  <img alt="TypeScript" src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img alt="Remix" src="https://img.shields.io/badge/remix-%23000.svg?style=for-the-badge&logo=remix&logoColor=white"/>
  <img alt="Nuxt" src="https://img.shields.io/badge/NuxtJS-black.svg?style=for-the-badge&logo=NuxtJS&logoColor=white"/>
  <img alt="Node" src="https://img.shields.io/badge/node.js-%2343853D.svg?style=for-the-badge&logo=node-dot-js&logoColor=white"/>
  <img alt="React" src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB"/>
  <img alt="ReactNative" src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img alt="Vue" src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D"/>
  <img alt="Ionic" src="https://img.shields.io/badge/Ionic-3880FF?style=for-the-badge&logo=ionic&logoColor=white"/>
  <img alt="TailwindCSS" src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
  <img alt="Docker" src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white"/>
  <img alt="GitHub Actions" src="https://img.shields.io/badge/githubactions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img alt="Apollo-GraphQL" src="https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql"/>
  <img alt="Nginx" src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white"/>
  <img alt="Kubernetes" src="https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white"/>
  <img alt="aws" src="https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white"/>
</p>
<!--
**Aldikrasniqi/AldiKrasniqi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:


-->
