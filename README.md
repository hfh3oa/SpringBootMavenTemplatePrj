# SpringBootのテンプレート
1. Java12(pom.xmlを編集してください)
1. SpringBoot
1. Maven
1. jar をサーバにデプロイ出来る形式で配布
1. IntelliJ IDEAで作成

# やること
1. git clone
1. 「SpringBootMavenTemplatePrj.iml」 を「プロジェクト名.imi」に変更
1. pom.xml で以下を編集
    1. Before : <artifactId>SpringBootMavenTemplatePrj</artifactId>
    1. After : <artifactId>プロジェクト名</artifactId>
1. maven build & install
1. http://localhost:8080/hello にアクセスして結果が表示されればOK
1. お好きな Repository に push してください
