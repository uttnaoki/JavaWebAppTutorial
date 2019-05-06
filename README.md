# JavaWebAppTutorial

## 環境変数

### Tomcat

| 環境変数 | 設定値 | 備考 |
|:--|:--|:--|
| JAVA_HOME |C:\Program Files(x86)\jdk1.8.0_121 | jdkのパス |
| CATALINA_HOME | C:\work\tomcat | Tomcatのパス |
| CATALINA_OPTS | -Dfile.encoding=UTF-8 | Tomcatの動作の設定 |

### Javaのコンパイル

| 環境変数 | 設定値 | 備考 |
|:--|:--|:--|
| PATH | %JAVA_HOME%\bin;%PATH% | javacコマンドなどを使用するため |
| CLASSPATH | %CATALINA_HOME%\lib\servlet-api.jar | サーブレットに必要なクラスが含まれているjarファイルのパス |