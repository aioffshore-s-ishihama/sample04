# sample04

### コメント（注釈）付きの場合
git tag -a タグ -m 'タグのコメント'
git tag -a v1.0.0 -m 'initial commit'

### 後からtagをつける場合
git tag -a タグ -m 'コメント' コミット
git tag -a v1.2 -m 'version 1.2' 9fceb02

### tagの共有
git push origin タグ名
例) git push origin v1.5

### 一覧の表示
git tag
