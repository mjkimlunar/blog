---
layout: post
title:  "GitHub 첫 블로그"
date:   2026-07-10 00:10:00 +0900
categories: notes
---

GitHub Pages와 Jekyll로 첫 블로그를 만들었습니다.

별도의 서버나 호스팅 비용 없이, 저장소에 마크다운 파일만 추가하면 GitHub이 알아서 사이트를 빌드하고 배포해줍니다.

### 글 쓰는 방법

`_posts` 폴더에 아래 형식으로 파일을 추가하면 새 글이 됩니다.

```
YYYY-MM-DD-제목.md
```

파일 맨 위에는 다음과 같은 정보(front matter)를 적어줍니다.

```yaml
---
layout: post
title:  "글 제목"
date:   2026-07-10 00:00:00 +0900
categories: notes
---
```

그 아래부터 마크다운으로 본문을 자유롭게 작성하면 됩니다.
