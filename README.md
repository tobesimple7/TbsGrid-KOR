# TbsGrid-kor

# 안내

TbsGrid에 오신걸 환영 합니다. 

찾아주셔서 감사드리며, 별을 주셔서 또 감사합니다.

아직 완성도와 일관성, 안정성에서 조금 떨어집니다.

계속적으로 업데이트 하도록 하겠습니다.

TbsGrid에 궁금한 점이 있으시면 이슈에 적어주시면, 답변 드리겠습니다.

개선되어야 할 사항이나 추가 기능에 대해서도 자유롭게 얘기해주시면,

검토 후 기능 개선 혹은 수정하도록 하겠습니다.

감사합니다~~

# 히스토리

### 계획

1. options 정리

2. cellType 확장

3. let, const 변수 정리(메모리 감소)

4. 사용자 함수 정리

5. 문서/가이드 작업

### 2024-09-24

1. 순수 자바스크립트로 된 소스를 모듈 프로그램으로 변경

2. esm 지원하도록 소스 개선

* webpack 을 통한 esm 파일 생성

3. cdn 배포 테스트

* Dependency
  
* <script src="https://cdnjs.cloudflare.com/ajax/libs/FileSaver.js/2.0.5/FileSaver.min.js" />
 
* <script src="https://cdn.jsdelivr.net/npm/mobile-detect@1.4.5/mobile-detect.min.js" />

--- 

* image root path : https://cdn.jsdelivr.net/npm/tbsgrid@0.0.9/dist/img

* <style src="https://cdn.jsdelivr.net/npm/tbsgrid@0.0.12/dist/css/tbsgrid.css" />
 
* <script src="https://cdn.jsdelivr.net/npm/tbsgrid@0.0.12/dist/tbsgrid-configs.js" />
 
* <script src="https://cdn.jsdelivr.net/npm/tbsgrid_test@0.0.12/dist/tbsgrid.min.js" />
 
4. npm 배포 테스트

* https://www.npmjs.com/package/tbsgrid

* npm install tbsgrid_test

* import { TbsGrid } from 'tbsgrid_test';

* import { tbsGridConfigs } from 'tbsgrid_test/dist/tbsgrid-configs.mjs';

5. typescript 지원은 올해 연말 까지 계획 중 

### 2024-09-20

1. 불필요한 소스라인 삭제

2. 소스 경량화 작업








