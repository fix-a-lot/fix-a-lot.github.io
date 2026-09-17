# AGENTS.md

## Response/Writing Style

- Respond concisely.
- 모든 문서는 문어체 + 반말로 작성한다.

## Tool Usage

- 웹 검색/크롤링이 필요한 작업(WebSearch, WebFetch 직접 호출 포함)을 시작하기 전에 반드시 `web-content-retrieval` 스킬을 먼저 불러와 그 판단 순서(crawl4ai-local → firecrawl → playwright)를 따른다.
