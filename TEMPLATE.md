## Hi, I'm Jesus 👋

I joined GitHub on `{{ f.date(REGISTRATION_DATE, {date:true}) }}`.
I contributed to `{{ REPOSITORIES_CONTRIBUTED_TO }}` repositories and made `{{ COMMITS }}` commits.

<!-- Talking about you -->
### 👨‍💻 About me

- 👦 I'm interested in distributed systems and cloud architecture.
- 🌱 I’m currently learning F# and functional programming
- 👯 I’m looking forward to collaborate on Open Source projects.
- ⚡️ I have a blog at https://jsantanders.dev
- 😄 Pronouns: he/him

### 🏆 Achievements

<%- await embed(`achievements`, {achievements:true, achievements_display:"compact", achievements_threshold:"B", achievements_secrets: "yes"}) %>

### 🈷️ Most used languages

<%- await embed(`languages`, {languages:true, languages_details:"percentage, bytes-size", languages_ignored: "html, css", languages_aliases: "JavaScript:JS, TypeScript:TS", languages_threshold: "2%", languages_sections: "most-used, recently-used"}) %>

### 📢 Find me elsewhere

<p>
  <a target="_blank" href="https://linkedin.com/in/jsantanders">
    <img src="https://github.com/jsantanders/jsantanders/blob/master/img/linkedin.svg" alt="LinkedIn" style="vertical-align:top; margin:4px">
  </a>
  
  <a target="_blank" href="https://stackoverflow.com/users/7318331/jesus-santander">
    <img src="https://github.com/jsantanders/jsantanders/blob/master/img/stackoverflow.svg" alt="StackOverflow" style="vertical-align:top; margin:4px">
  </a>
  
  <a target="_blank" href="http://twitter.com/jsantanders">
    <img src="https://github.com/jsantanders/jsantanders/blob/master/img/twitter.svg" alt="Twitter" style="vertical-align:top; margin:4px">
  </a>
</p>
