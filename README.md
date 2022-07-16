# RepositoryTemplate

T.B.D.
Make template for README.md.

# ディレクトリ構造

 - project\_name
     - 直下にコードを置かない
     - project\_name(app)
         - 固定
         - libs
            - 任意
            - このプロジェクトでしか使わないライブラリ
         - (app)models
         - (app)views
         - (app)templates
         - (app)static
         - (
     - libs
         - 任意
         - 汎用的に使うライブラリ
     - data
         - 任意
         - 各種データの格納先
     - config
         - 固定
         - 各種設定ファイルを格納
     - logs
         - 固定
         - アプリケーションが出力するログファイルを格納
     - docs
         - 固定
         - プロジェクトに関するドキュメント一式を格納
         - wiki
         - specification
     - examples
         - 任意
         - プログラム使用例を格納
     - tests
         - 固定
         - テストコードを格納
     - README.md
         - 固定
     - requirements.txt
         - 固定
         - pipコマンドで必要なモジュールを一括インストールする際に使用
     - setup.py(run.py)
         - 固定
         - 例外、コードを置く
     - LICENSE
         - 固定
