# alpha-book
蔵書管理システム(PHP版)

## 現状把握しているバグ、及び対応状況

### <font color="RED">重要度 高</font>
- [x] 書籍情報ページの貸出で存在しないUserIDを使用不可にする（OK）
- [x] ユーザ登録でユーザ名が空の時は登録できなくする（OK）
- [x] カテゴリ登録でカテゴリが空の時は登録できなくする（OK）
- [x] 同じカテゴリの登録をできなくする(dbの設定でいけるんじゃない？)
- [ ] 各ページのタイトルをリンクにする
- [ ] indexを作成
- [ ] 本の追加でカテゴリが空の時はエラーにする

### <font color="yellow">重要度 中</font>
- [ ] ユーザページで存在しないID指定の時エラー表示
- [ ] ユーザ登録ページでエラー表示
- [ ] カテゴリ登録ページでエラー表示
- [x] 書籍情報ページの貸出履歴からユーザページに飛べるように
- [x] 書籍情報ページの返却ボタンのカスタマイズ
- [ ] 本のカテゴリIDを連番にする
- [ ] 蔵書登録で完了メッセージ表示するようにする

### <font color="GREEN">変更予定</font>
- [x] 蔵書一覧でBook IDをカテゴリにする
- [ ] カテゴリ検索可能にする

### 対応予定なし
- ユーザIDに前半0がつくもの
- 10桁程度のID(DBでuser_idがint型だから)