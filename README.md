
```mermaid
graph LR;
      Untracked --"git add" --> Staged ;
      Modified -- "git add"-->Staged;
      Staged -- "git commit"--> Tracked;
      Tracked-- modifications -->Modified;
```
