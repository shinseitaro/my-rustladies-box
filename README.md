# my-rustladies-box

RustLadies - connpass - https://rustladies.connpass.com/ でやったことを載せていきます。


自分にメモ : 

```
<filename> does not have a commit checked out fatal: adding files failed
```
みたいなエラーが出るときは、配下の `.git` を削除してください。`cargo new` で作ったプロジェクトには `.git` が入っているのでこれを意図的に消さないと、git add できないよ。

参照：[gitlab - How to fix: error: '<filename>' does not have a commit checked out fatal: adding files failed when inputting "git add ." in command prompt - Stack Overflow](https://stackoverflow.com/questions/56873278/how-to-fix-error-filename-does-not-have-a-commit-checked-out-fatal-adding/58530721#58530721)

