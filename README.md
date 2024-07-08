# 強化学習アルゴリズム実装プロジェクト

## 概要
このプロジェクトは、マルコフ決定過程における価値反復法から深層Q学習（DQN）に至るまでの様々な強化学習アルゴリズムの実装を目的としています。基本的な概念から最新の手法まで、段階的に学習と実装を進めることで、強化学習の理解を深めることを目指しています。

## 実装アルゴリズム
- マルコフ決定過程（MDP）
- 価値反復法（Value Iteration）
- 方策反復法（Policy Iteration）
- Q学習（Q-Learning）
- SARSA
- 深層Q学習（DQN）
- その他実装予定のアルゴリズム

## プロジェクト構造
プロジェクトはchapterごとに分かれており、各チャプターで異なるアルゴリズムや概念を扱っています。
```
project/
├── chapter1/ [MDP関連のコード]
├── chapter2/ [価値反復法関連のコード]
├── chapter3/ [方策反復法関連のコード]
├── chapter4/ [Q学習関連のコード]
├── chapter5/ [SARSA関連のコード]
├── chapter6/ [DQN関連のコード]
└── [その他のチャプター]
```

## 環境セットアップ
このプロジェクトを実行するには、Python環境にGymもしくはGymnasiumをインストールする必要があります。
```bash
pip install gym
```
または
```bash
pip install gymnasium
```

## 使用方法
各チャプターのディレクトリに移動し、対応するスクリプトを実行してください。

## 参考資料
このプロジェクトは、以下の資料を主な参考としています：

- [baby-steps-of-rl-ja](https://github.com/icoxfog417/baby-steps-of-rl-ja)

  本プロジェクトの多くの実装は、この資料を参考にしています。
