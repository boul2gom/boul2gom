---
name: Bug report
about: Report a bug with one of my projects
title: 'bug: '
labels: bug
assignees: nullptr-rs

---
### 🔍 In which project did you find a bug?
I found a bug in the project: `nullptr-rs/nullptr-rs`

### 🐛 What's the bug ?
A short description of what the bug is.

I can't serialize properly the Pair type.

### 🔍 In which context, with which release/commit of the project, and with which code did you encounter the problem ?
A clear and concise description of the context, the release/commit and the code that caused the problem.

This issue appears in the release 1.2.0 of the library, with this code:
```java
final String serialized = new Gson().toJson(new Pair<>(1, 2));
```

### 📸 Additional details / Screenshots