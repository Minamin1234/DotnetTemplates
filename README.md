# .NETテンプレート
## ConsoleApp (`consoleapp`)
### インストール
- `./ConsoleApp`を任意のフォルダに配置します。
- カレントディレクトリを`[配置したパス]/ConsoleApp`に移動します。
```shell
$ cd [配置したパス]/ConsoleApp
$ dotnet new --install .
```
正常にインストールされると以下の出力が得られるはずです。
```shell
次のパッケージがインストールされます:
   C:~~~\ConsoleApp

成功: C:~~~\ConsoleAppにより次のテンプレートがインストールされました。
テンプレート名  短い名前    言語  タグ
--------------  ----------  ----  --------------
ConsoleApp      consoleapp  [C#]  Common/Console
```
作成する際は
```shell
$ dotnet new consoleapp
```
で作成できます。