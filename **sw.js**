// PWA 단독 앱 설치 요건 충족용 서비스 워커
self.addEventListener('install', (e) => {
  self.skipWaiting();
});

self.addEventListener('activate', (e) => {
  e.waitUntil(clients.claim());
});

self.addEventListener('fetch', (e) => {
  // 오프라인/캐시 없이 네트워크 통과
});
