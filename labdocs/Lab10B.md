﻿# ラボ 10B: データ ドリフトの監視

時間の経過とともに、データの傾向が変化すると、モデルによる予測の精度が低下する場合があります。この*データ ドリフト*の監視と必要に応じての再トレーニングは、機械学習ソリューションが正確に予測し続けられるようにするための重要な方法です。

## 開始する前に

このラボを開始する前に、このラボで使用する Azure Machine Learning ワークスペースと他のリソースを作成するタスクを含む[ラボ 1A](Lab01A.md) と[ラボ 1B](Lab01B.md) を完了させてください。

## タスク 1: データセットのデータ ドリフトの監視

このタスクでは、データセットのデータのドリフトを監視します。

1. [Azure Machine Learning Studio](https://ml.azure.com)で、ワークスペースの**コンピューティング** ページを表示し、**コンピューティング インスタンス** タブでコンピューティング インスタンスを開始します。
2. コンピューティング インスタンスが実行されている場合は、ブラウザーで Azure Machine Learning Studio の Web ページを更新して、認証セッションの有効期限が切れていないことを確認します。次に、**Jupyter** リンクをクリックして、新しいブラウザー タブで Jupyter のホーム ページを開きます。
3. Jupyter のホーム ページの**Users/DP100** フォルダーで、**10B - Monitoring Data Drift.ipynb** Notebook を開きます。次に、Notebook 内の注意事項を読み、各コード セルを順番に実行します。
4. Notebook 内のコードの実行が終了したら、**ファイル(Files)** メニューの**閉じて停止(Close and Halt)**をクリックして閉じ、Python カーネルをシャットダウンします。その後、すべての Jupyter ブラウザー タブを閉じます。
5. Azure Machine Learning Studio の**コンピューティング** ページで、コンピューティング インスタンスを選択し、**停止**をクリックしてシャットダウンします。
