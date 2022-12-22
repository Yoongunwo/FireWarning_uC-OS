# FireWarning

## ABOUT
- 이 프로젝트는 `nucleo-f429zi`보드를 이용해서 uC/OS 기반으로 만든 것이다. 
- 불꽃 감지 센서가 불꽃을 감지하고 LED와 능동BUZZER를 통해서 경고를 주는 동작을 한다.
- 자세한 동작 원리(`Task Message Queue`)는 코드는 `app.c`를 보면 알 수 있다.

## VERSION
- 개발 보드 : Nucleo-f429zi
- 컴파일러 : TrueSTUDIO_Win 9.3.0
- [ST-link to J-link convert](https://www.segger.com/products/debug-probes/j-link/models/other-j-links/st-link-on-board/) : 해당 사이트에서 3개의 파일을 다운로드 받으면 된다.

## MODULE
- 불꽃 감지 센서 ( DOIT-M005 )
- 2색 LED
- 능동 부저

## 동작영상
- [영상 링크](https://www.youtube.com/watch?v=X6-PAXA8oOo)

## LICENSE
Code released under the [MIT](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll/blob/master/LICENSE) license.
