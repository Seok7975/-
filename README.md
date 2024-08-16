240813, STS4에서 start project를 만드는데 발생한 에러

'Import Getting Started Content' has encountered a problem.<br>
ClassNotFoundException: org.apache.commons.io.build.AbstractStreamBuilder cannot be found by org.apache.commons.commons-compress_1.26.2
java.lang.reflect.InvocationTargetException

아직 해결 못함..
1) window ->  Preferences -> java -> Installed JREs -> jdk를 변경했으나 실패<br>
cf) https://jiurinie.tistory.com/132

2) spring initializer로 만들고 임포트는 됨

240816, lombok @Data를 써도 getter setter메서드가 만들어지지 않는 에러

dto에서 만들고 service에서 불러들이려는데 자꾸 getter setter메서드가 없다고 뜸.

1) https://ldgeao99-developer.tistory.com/612 참고하여, 의존성 주입뿐만아니라 직접 사이트에서 jar파일을 다운받고 cmd에서 install하니 해결
