# sample04

### コメント（注釈）付きの場合
git tag -a タグ -m 'タグのコメント'
ex) git tag -a v1.0.0 -m 'initial commit'

### 後からtagをつける場合
git tag -a タグ -m 'コメント' コミット
ex) git tag -a v1.0.1 -m 'second commit' 9fceb02

### tagの共有
git push origin タグ名
ex) git push origin v1.0.0

### 一覧の表示
git tag
