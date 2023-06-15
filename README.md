<!-- 
  [CSS 적용된 배너 만드는 방법]
  1. 배너 스타일 작성
    # Making Banner Application URL: https://www.canva.com/design/DAFl2y3Kd6w/TJbhZG05KsV6Q3VsUYHDDA/edit?ui=eyJBIjp7IkEiOiJkb3dubG9hZF9wbmciLCJGIjp0cnVlfSwiRSI6eyJBPyI6IkUifSwiRyI6eyJEIjp7IkEiOiJNQUZsMjY0OGdfYyIsIkIiOiJNVFprWkdRMU1USXRaREk0TnkwMFl6RTBMV0kxWXpZdFpqUTVNVGhoWmpVMk1qSXguaUNraG1VZzFhMkJ0Ml9LMzhXWDNZVWNmYl9rc3pXYXJZcFk4SzFBdmZuNCIsIkQiOnsiQT8iOiJBIiwiQSI6IkQifX19fQ
  2. img 태그에 추가할 svg 파일 생성 (foreignObject + HTML + CSS)
  3. svg 내부에 img 태그 생성 및 src에 base64 encoding image 할당
    # image -> base64 Application URL : https://www.base64-image.de/
-->

<style>
  .test {
    width: 300px;
    height: 200px;
    border: 1px solid white;
  }
  .test:hover {
    border: 2px solid blue;
  }
</style>

<div style="width: 100%; margin-bottom: 10px;">
  <img src="assets/svgs/header.svg" alt="README Header" title="README Header" />
</div>

<div style="width: 100%;">
  <img src="assets/svgs/body.svg" alt="README Header" title="README Header" />
</div>

<div class='test'>
  dsta
</div>