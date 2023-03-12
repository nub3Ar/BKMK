# BKMK
A chatGPT-powered web app to do Q&A with your bookmarks using retrieval augmented generation

### Motivation:
1. My friend [https://www.linkedin.com/in/michael-agaby/] and I both have an overflowing knowledge base stored in our bookmarks. We wanted to have a bing-like experience with that knowledge base
2. It's just one of those afternoons where two non-engineers want to build something :3


### What we built:
We built a quick and dirty prototype (in under 2 hours!) with the help of chatGPT. It's a locally hosted web app that will index website urls you add semantically based on its content, and answer any questions for you, similar to Bing but personalized to your own knowledge base. It has a lot of limitations (mainly in what it is able to index), but most of the techniques are quite transferrable if you are interested in expanding its capability.


### Techniques/Learnings:
- Ada-text-embedding-002 with a local store for semantic retrieval
- Segmentation and recursive summarization to fit long articles into chatgpt context window
- ChatGPT API + Prompt engineering to explain the task and enforce formatting
- Used chatGPT GENEROUSLY to learn, code, debug, and iterate (neither of us are engineers by trade)


### What you would need to use this:
- an OPENAI API key: https://openai.com/blog/openai-api, the home page of the web app will prompt you to enter it and you will bear the cost for the usage


### enter API key

<img
  src="/img/Add_key.png"
  style="display: inline-block; margin: 0 auto; max-width: 100px">

### add article and article store

<img
  src="/img/add article.png"
  style="display: inline-block; margin: 0 auto; max-width: 50px">
<img
src="/img/store.png"
style="display: inline-block; margin: 0 auto; max-width: 50px">

### Different QAs:
<img
src="/img/QA.png"
style="display: inline-block; margin: 0 auto; max-width: 50px">

<img
src="/img/did I.png"
style="display: inline-block; margin: 0 auto; max-width: 50px">

<img
src="/img/no answer.png"
style="display: inline-block; margin: 0 auto; max-width: 50px">

<img
src="/img/adjacent answer.png"
style="display: inline-block; margin: 0 auto; max-width: 50px">


