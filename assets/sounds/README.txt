ここに音声ファイルを配置してください。
対応フォーマット：.mp3（デフォルト）

フォルダ構成：
/assets/sounds/bgm/   ← BGM（背景音楽）を配置
/assets/sounds/se/    ← SE（効果音）を配置

推奨ファイル名（src/constants.ts で定義されています）：

【BGM】
- bgm_title.mp3     （タイトル画面）
- bgm_dungeon1.mp3  （地下1階 / B1F）
- bgm_dungeon2.mp3  （地下2階 / B2F）
- bgm_battle.mp3    （通常戦闘）
- bgm_boss.mp3      （ボス戦）
- bgm_victory.mp3   （勝利）
- bgm_town.mp3      （街 / キャラクター作成）

【SE】
- se_cursor.mp3     （メニュー移動）
- se_decide.mp3     （メニュー決定）
- se_cancel.mp3     （メニューキャンセル）
- se_step.mp3       （足音）
- se_bump.mp3       （壁にぶつかる）
- se_door.mp3       （ドアを開く / ワープ）
- se_attack.mp3     （攻撃の振り）
- se_hit.mp3        （ヒット音）
- se_damage.mp3     （プレイヤーのダメージ / トラップ）
- se_magic.mp3      （魔法詠唱 / 回復）
- se_levelup.mp3    （レベルアップ）
- se_run.mp3        （逃走）
- se_chest.mp3      （宝箱を開ける）

※ 注意：
ファイルが存在しない場合でも、ゲームはクラッシュしません。
その音は再生されないだけ（またはコンソールに警告が表示されるだけ）です。
