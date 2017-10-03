# What

* サブプロジェクト上にあるシーンの読み込みをサポートします
* シーンがビルドに含まれているのか AssetBundle による Streamed なのかを問わず読み込みを可能にします

# Why

* 通常の `UnityEngine.SceneManagement.SceneManager.LoadScene()` では AssetBundle の事前読み込みをサポートしていません
* また、サブプロジェクト化されたプロジェクトのシーンを読み込む際に [`@umm/project_assetbundle_loader`](https://github.com/umm-projects/project_assetbundle_loader) を用いる必要があるため、ラッパーを実装します

# Requirement

* Unity 2017.1

# Install

```shell
$ npm install github:umm-projects/project_scene_loader
```

# Usage

* 

# License

Copyright (c) 2017 Tetsuya Mori

Released under the MIT license, see [LICENSE.txt](LICENSE.txt)

