# git checkout

[Reference](https//git-scm.com/docs/git-checkout)

## 構文

`git checkout [<options>] <branch>` Or
`git checkout [<options>] [<branch>] -- <file>...`

## option

| option | description |
| :--- | :--- |
| `-q , --quiet` | チェックアウト詳細ログを非表示にする |
| `-b <branch>` | 新しいブランチを作成してチェックアウトする |
| `-B <branch>` | ブランチを作成/リセットしてチェックアウトする |
| `-l` | 新しいブランチのreflogを作成する |
| `--detach` | 名前付きのコミットでHEADを切り替える |
| `-t , --track`  | 新しいブランチのリモート情報を設定する |
| `--orphan <new-branch>` | 親がない新しいブランチを作成 |
| `-2, --ours`            | マージされていないファイルをチェックアウトする |
| `-3, --theirs`          | マージされていないファイルのバージョンをチェックアウトする |
| `-f, --force`           | チェックアウトを強制的に行う(ローカルの変更は破棄される) |
| `-m, --merge`           | 新しいブランチとの3者間でマージを行う |
| `--overwrite-ignore`    | ignoreファイルを更新する(デフォルトで有効) |
| `--conflict <style>`  | 競合時のスタイル設定(merge or diff3) |
| `-p, --patch`           | 競合時の対話的ハンクを選択する |
| `--ignore-skip-worktree-bits` | パス指定をスーパスエントリのみに制限しない？ |
| `--ignore-other-worktrees` | 他のWorktreeが参照を保持しているかどうかを確認しない |
| `--recurse-submodules[=<checkout>]` | サブモジュールの再帰的更新を制御する |
| `--progress`           | 進捗をプログレスバーで表示 |