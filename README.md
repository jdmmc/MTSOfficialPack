# MTS Official Pack

forked from DonBruce64/MTSOfficialPack

# 概要

Immersive Vehiclesで利用するコンテンツパックをビルドするためのツールが設定されています。

# MODとしての設定

- MTSOfficialPack\src\main\resources\META-INF\mods.toml
- MTSOfficialPack\src\main\resources\assets\mtsofficialpack\packdefinition.json

# パックの画像変更

以下を置き換えるのが簡単。  
MTSOfficialPack\src\main\resources\vingette.png

ファイル名を変更した場合はmods.tomlにも記載する。

# 使い方

事前に以下のフォルダを作成してください。

```
MTSOfficialPack\build\libs
```

Windowsの場合はcompile.batを実行します。  
すると、`build/libs`にパックのjarファイルが作成されます。