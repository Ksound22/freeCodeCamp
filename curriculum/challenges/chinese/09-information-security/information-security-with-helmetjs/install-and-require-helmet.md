---
id: 587d8247367417b2b2512c36
title: 安装和引入 Helmet
challengeType: 2
forumTopicId: 301581
dashedName: install-and-require-helmet
---

# --description--

你可以采用下面的任意一种编写代码的方式来完成这些挑战：

- 克隆<a href="https://github.com/freeCodeCamp/boilerplate-infosec/" target="_blank" rel="noopener noreferrer nofollow">这个 GitHub 仓库</a>，并在本地完成这些挑战。
- Use <a href="https://gitpod.io/?autostart=true#https://github.com/freeCodeCamp/boilerplate-infosec/" target="_blank" rel="noopener noreferrer nofollow">our Gitpod starter project</a> to complete these challenges.
- 使用你选择的网站生成器来完成项目。 需要包含我们 GitHub 仓库的所有文件。

Helmet 通过设置各种 HTTP 头来保护你的 Express 应用程序。

# --instructions--

你在这些课程中写的所有代码都在 `myApp.js` 文件中，在初始代码之间。 不要改变或删除我们为你添加的代码。

Helmet `3.21.3` 版已经安装完毕，所以在 `myApp.js` 中请求它作为 `helmet`。

# --hints--

`helmet` 版本 `3.21.3` 应该在 `package.json` 中。

```js
(getUserInput) =>
  $.get(getUserInput('url') + '/_api/package.json').then(
    (data) => {
      const packJson = JSON.parse(data);
      const helmet = packJson.dependencies.helmet;
      assert(helmet === '3.21.3' || helmet === '^3.21.3');
    },
    (xhr) => {
      throw new Error(xhr.responseText);
    }
  );
```

