---
"partysocket": patch
---

Rebuild a replacement socket when its options change again before it connects, so `usePartySocket` never returns a socket connected with stale options.
