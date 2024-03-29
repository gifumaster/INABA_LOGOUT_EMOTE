# INABA_LOGOUT_EMOTE

VRC INABA用　VRChat用標準衣装対応ログアウトモーション

liltoonのDissolve機能を利用したログアウトエフェクトの設定を補助するパッケージです。  
アバター本体は付属していません。 本パッケージに関する一切の質問は受け付けません。ある程度Unityがわかっている必要があります。

## ダウンロード
https://github.com/gifumaster/INABA_LOGOUT_EMOTE/raw/main/inaba_fadeout.unitypackage

## 内容物
 - パラメータ設定済みのprefab variant
 - Modular Avatar用のコンポーネント設定済みのprefab
 - アニメーション、メニュー

【重要】
 - 設定前にアバター本体、liltoon、Modular Avatarをimportしてください。
   - オリジナル3Dモデル「INABA」https://booth.pm/ja/items/4213786
   - Modular Avatar https://modular-avatar.nadena.dev/ja/
   - liltoon https://booth.pm/ja/items/3087170
 - Prefab variantはmaterialをdessolve対応のモードに変えたものがセットされています。
   - Dissolveがfurに対応していないため、尻尾はもふもふ感が失われております。
 - そのままアップロードしていただければ対応完了です。
 - 標準以外の衣装や小物（メッシュ）を追加した場合には別途アニメーションに追加する必要があり、Unityの知識を必要とします。

【Prefab Variantを使わず標準対応する場合】
 - FadeoutModuleをアバターの直下に入れてください。
 - 各メッシュのliltoonシェーダーをDessolve対応のモードに切り替えます。
 ![image](https://user-images.githubusercontent.com/34181574/215459237-a6e92c4e-37b2-4c2d-beda-05942a318b05.png)
 
【その他】
 - FadeoutSoundに音源を設定できます。消失時のみ音が1回再生されます。
 - fadeOutEffect 消失時に発生するパーティクルの設定ができます。
   - Shapeをアバターのメッシュにしておくと良い感じです。
   ![image](https://user-images.githubusercontent.com/34181574/215459778-1c87495a-374f-4522-bfb5-b6f3c1917f0d.png)
   
   
   
