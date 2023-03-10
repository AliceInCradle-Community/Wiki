<h2>アップデート情報</h2>

### バージョン0.22

#### ver0.22q(230308)

初回起動時のSFWモード確認のUIを修正。<br>
売買UIにおけるマウスクリックに関する挙動を修正。<br>
ガチャ入力QTEの縁取りの色が白くなかった問題を修正。<br>
ゲームがスローになっている最中にエフェクトが等速で配置されることがあった問題を修正。<br>
ヌシのトゲ胞子への当たり方によってノエルが意図しない速度で上に吹き飛ばされることがあった問題を修正。<br>
ヌシのトゲ胞子が壁の近くまで飛んでいかないよう修正（脱出に受け身が必須になるような場所に設置されないようにしました）<br>
特定のタイミングでデータをロードした最に例外が発生する問題を修正。<br>
ヌシが走行中に檻を下ろすフェーズに遷移に移行しないよう修正。<br>
トゲに触れた際に左アニメに電気にしびれるモーションが表示されることがあった問題を修正。

#### ver0.22p(230217)

ゲームシーンに移動した際に、ウインドウ画面外の目隠しが消える問題を修正。<br>
クラフトUIに関わる問題を修正。<br>
はにわ等のHP/MP最大値を増やすアイテムの挙動を修正。<br>
左側古駅に軍人がいるときにナイチンゲールが登場しないよう修正。<br>
外出時に昼夜が切り替わらないことがあった問題を修正。<br>
サイクロンの壁蹴り反動と他の攻撃／シールド等を絡めた意図しない横スライド移動を修正。<br>
サイクロンの壁蹴り反動時に意図した距離より上に飛ぶような操作ができないよう修正。<br>
エアスラッシュの前移動速度、およびショットガンヒットの反動を修正。ショットガンをからめながら空中で前進しすぎないようになりました。（長い杖を使用しない場合にショットガン→通常パンチのコンボが通りにくくなります）<br>
昏倒中に下マップに移動した際の挙動を修正。<br>
相打ちになった後に戦闘が終了し、かつ終了後にイベントが再生される（イクシャ救助／爆弾回収）場合、イベント実行に敗北シーケンスをインジェクトできる問題を修正。<br>
ノエルちゃんががめおべらしてぼこぼこ殴られる時に絶頂していてもMPゲージが割れるよう修正。<br>
一部のメモリリーク問題を修正。<br>
シールドバッシュでヌシのトゲ胞子をはじいたときに必ず左に飛ぶ問題を修正。<br>
パズルのバリアを抜けた際にエグめのメモリ確保が走る問題を修正。<br>
「不器用者の底力」使用時に意図しないタイミングで魔力回収できる問題を修正。<br>
イクシャ救出後のエナジーボールチュートリアルでチュートリアルの最中に（イクシャが去るイベントがスタックされた状態で）エリアを退出できる問題を修正。<br>
会話のぽぽぽぽ音が文字表示タイミングからずれることがあった問題を修正。<br>
滝の下で溺れるとがさがさなる問題を修正。<br>
しばらく落下するとカメラを下にフォーカスするようにカメラの挙動を操作を修正。<br>
メニューのマップ画面でドラッグでマップを移動できるよう修正。<br>
Fatalのカーソル問題を修正。<br>
タイトル画面でセーブデータUIをがちゃがちゃやったときの問題を修正。<br>
愚者がまれに詠唱中でないにも関わらず魔法陣を抱えたままになることがあった問題を修正。<br>
描画間隔を遅くするとカメラの挙動が大きく異なる問題を修正。<br>
蛇がボムを食べるシーケンスに入っているにも関わらずボムでスタンしなかった問題を修正。<br>
走行時カメラが正しく中央に寄らない問題を修正。<br>
イベントメッセージの読みやすさを多少修正。<br>
プリムラのスキルチュートリアルの際に不用意にマウスを操作した際の挙動修正。<br>
UIに関するメモリが増大する問題を低減。<br>
高所恐怖症装備時の空中浮遊バグを修正。<br>
「ビンを空にする」の実行時に選択しているグレードを考慮するよう修正。<br>
森のヌシ戦に入って表示される前にデータロードするとエラーが発生した問題を修正。<br>
戦闘に入ってからはにわを装備したときに正しくはにわ装備状態の処理に移行しなかった問題を修正。<br>
ヌシ戦で行動予告のパーティクルがオプションによって表示されないことがあった問題を修正。<br>
チャージャースロットに関するバグ修正。<br>
空中でイバラに接触しない問題を修正。<br>
メニュー画面での危険度メーターの表示ほか、一部の表示に関わる問題を修正。

#### ver0.22o(230206)

UIに関するメモリが増大する問題を低減。<br>
高所恐怖症装備時の空中浮遊バグを修正。<br>
「ビンを空にする」の実行時に選択しているグレードを考慮するよう修正。<br>
森のヌシ戦に入って表示される前にデータロードするとエラーが発生した問題を修正。<br>
戦闘に入ってからはにわを装備したときに正しくはにわ装備状態の処理に移行しなかった問題を修正。<br>
ヌシ戦で行動予告のパーティクルがオプションによって表示されないことがあった問題を修正。<br>
チャージャースロットに関するバグ修正。<br>
空中でイバラに接触しない問題を修正。<br>
メニュー画面での危険度メーターの表示ほか、一部の表示に関わる問題を修正。

#### ver0.22n(230202)

ノエルジュースが爆発しない問題を修正。<br>
マップ移動時に特定条件下でサウンド再生エラーが発生する問題を修正。<br>
抱卵時に金色のマナ以外でもオーバーチャージャースロットが溜まりやすくなるよう修正。<br>
オーバーチャージャースロットを中途半端にためたときに、これまではすぐにたまったMPが揮発していたが戦闘中は保持するよう修正。
#### ver0.22m(230202)

ヌシ戦でシコりながらイクシャを救出した場合にメーファさんの前で喘ぎまくる問題を修正。<br><br>
2戦目以降ヌシ戦でシコりながら倒した場合にソフト・ロックする問題を修正。<br>
ノエルジュースで稼げる危険度の上限を45に設定。また、ノエルジュースで危険度を爆増させた際にいっぺんにリールを大量に得ることができないように修正。<br>
魔術詠唱・アイテム使用のスローの際に水に浸かっていた際に息を整えることができた問題を修正。<br>
風のアトリウム右側マップに左から無理やり突っ切って蟲沼に入るとスタックする問題を修正。<br>
一部のマップでマップに入った直後に蟲沼に飛び込むと奇妙な場所でリスポーンした問題を修正。<br>
蟲沼に入った直後にメニューを開くとリスポーンできなかった問題を修正。<br>
マップの下方向出口付近でサイクロンを出すと正しくマップ移動できなかった問題を修正。<br>
弁当箱を取り出す動作でアイテム行を本来の最大行数を超えることができた問題など、アイテムUIに関わる問題を修正。<br>
スキルの付け替えで意図しない回復が可能だった問題を修正。<br>
ベンチ上でスキルの付け替えした際にHPを回復（拠点ならMPも）をできるよう修正。<br>
アイテムメニューを閉じながらマップ上の木／鉱石リールを回し始めるとアイテムの種類名が見えなかった問題を修正。<br>
チルダの料理チュートリアルで特定操作によってソフトロックする問題を修正。<br>
おあずけ状態でシコり始めた際に水中に落ちた場合は中断するよう修正。<br>
キーコンフィグ画面で重複入力を設定できないよう修正。<br>
アイテムセレクトで左右移動で10行スクロールできるよう修正。<br>
沼や水没などのアイリスアウトで想定されていないような位置にジャンプすることがあった問題を修正。<br>
最大HP, MP上昇料理を食べた直後はHP,MPも増えるよう修正。

#### ver0.22(lは欠番)&s(){&color(#F54738){またお前か欠番しだな}}

#### ver0.22k(230122)
アイテムをソートした際などに虚無の行が現れることがあった問題を修正。<br>
アイテム整理時にグレードボタンをクリックできないことがあった問題を修正。<br>
タイトルにTwitterボタンを追加

#### ver0.22j (230121)
zh-cnBテキスト更新。<br>
フェイタルシーンの左右入力が逆だったのを修正。<br>
アイテム選択中にマウスでグレードを切り替えた際に説明が切り替わらなかった問題を修正。<br>
店画面のソート時にリストに表示された額面通りの順になるように修正。<br>
チルダの料理チュートリアルの際に特定動作をした際にソフトロックする問題を修正。<br>
階段に置かれたアイテムを拾えなかった問題を修正。

#### ver0.22h / i (230120)
mac版にGateKeeperを通過させるための .command ファイルを追加。<br>
店からの買い戻しの際にボトルがない状態で水を買い戻す動作ができた（水がどこにも入らずに水が消失した）問題を修正。<br>
坂道でデスした際にノエルちゃんが打ち出される問題を修正。<br>
針鼠左側パズル、および大量のアイテムを拾った際のメモリリーク問題を修正。<br>
ベンチに座った際に治療された状態異常がメニュー内に残っていた問題を修正。<br>
ハシゴで下側の床に降りることができなかった問題を修正。<br>
拘束中に杖を落とさなかった問題を修正。<br>
ゲームオーバー時に勝手に開かれる宝箱の速度をデフォルトで高速化。<br>
ゲームオーバー後特定のベンチに復帰した際に地形を下に突き抜けることがあった問題を修正。<br>
動く床に乗ったまま蟲の沼に入った場合に動く床の接触判定が消滅した問題を修正。<br>
ベンチでシコることでジュース／ゲージの回復を無限にできた問題を修正。( ﾟДﾟ)<br>
ノエルの部屋で棚を調べてアイテム整理画面を出したあとにアイテム画面内でショートカット登録ができなかった問題を修正。<br>
アイテム整理画面で1行移動したあとにいちいちフォーカスがスクロール調整されていた問題を修正、ほかアイテム画面の処理高速化。<br>
アイテム整理画面で他画面をクリックできることによる問題を修正。<br>
料理のスクロールが長すぎた場合の表示を修正。その他いくつかのUIの問題を修正。<br>
帰宅したリールを開けた直後にメニューを開くと取得したアイテムが倉庫内に反映されていなかった問題を修正。<br>
アイテム選択中・魔法選択中にはしごの昇降が可能だった問題を修正。<br>
個数0の行が残ることがあった問題を修正。<br>
リールの図柄が空欄になることがあった問題を修正。<br>
棒立ちで電撃トラップを回避できる問題を修正。<br>
(ver i)アイテム整理中にマウス操作した際の動作を修正。

#### ver0.22g(230115)
蟲沼に囚われた際にバーストを撃てた問題を修正。<br>
蟲沼に飛び込んで復帰した後に魔力植物が忽然と消失する問題を修正。<br>
英語版でテキストの抜けがあった部分を修正。<br>
拠点に帰ると抱卵Lv1が回復した問題を修正。<br>
高さ2マスの空間でバーストを使ったあとうまく着地できない問題を修正。<br>
コントローラーでアイテムを拾おうとすると拾いながらジャンプしてしまっていた問題を修正。<br>
メニューから宝箱を開かずにアイテムリールの取捨選択を行ったあとの諸問題を修正。<br>
スキル取得直後にメニューを開くと画面にスキルのアイコンが残ったままだった問題を修正。<br>
蛙に地面に埋められたまま戦闘不能になると蛙がそれを引き抜くことができなかった問題を修正。<br>
壊せる壁にサイクロンが当たらないことがあった問題を修正。

#### ver0.22f (230113)
&color(#F54738){メーファ・グリッドヤードとの会話シーンはこっそり回想シーンに実装、あと立ち絵の実装された}<br>
ベンチでシコシコしながらバーストを撃てた問題を修正。<br>
パズルでの稼働ハコを落とし戸のすぐ隣に配置した際の諸問題を修正。<br>
雑貨店内の移動（ノエル部屋窓→キッチンなど）のメニューを「キャンセル」で解除後即イベントを開始した際にソフトロックした問題を修正。<br>
インベントリから宝箱を開ける際、宝箱のUIを開く→キャンセル→すぐに宝箱を開けようとする、と選択したときに宝箱が表示されない問題を修正。

#### ver0.22e (230110)
手動でベンチで衣服修復した際に立ち絵に反映されない問題を修正。<br>
拘束中にボムを踏んだ敵にダメージを与えられるよう修正。<br>
攻撃または魔法ボタンと左タブ／右タブを同一の入力にアサインした時にQTEが正しく動作しなかった問題を修正。<br>
英語版でクラフト／宝箱オープンの際のいくつかの操作説明に誤りがあった問題を修正。<br>
雑貨店洞窟内の水たまりが2分ほど放置すると消滅した問題を修正。<br>
特定の地形で溺れるとソフトロックする問題を修正。<br>
マップ移動シーケンスと同時にメニューを開くことができた問題を修正。<br>
ESCで高速でイベントを回した際に非表示になるはずのレイヤーが表示されたまま残って画面が暗いまま残ることがあった問題を修正。<br>
ゲーム終了時の処理を修正。特に、スロー演出中にタイトルに戻った場合に再開時にゲーム速度が初期化されていないことがあった問題に対処しました。<br>
木馬に揺られているときにスライムなど他の敵に組み付かれると木馬の上で曲芸飛行する問題を修正。<br>
沼蛙の地面埋め攻撃がうまく成功しなかった問題を修正。<br>
ベンチメニューをよろしくない位置から起動してエラーが発生する問題を修正。<br>
ベンチで抱卵を治療できた問題を修正。<br>
ベンチ上でセーブしたファイルを2回ロードするとベンチがマップから消える問題を修正。<br>
ゲームオーバー演出中にカメラ移動のためフレームを停止させるとタイミングによってゲームが再開しない問題を修正。

#### ver 0.22d (230107)
雑貨店と森をつなぐマップの行き先表示がずれていた問題を修正。<br>
電流トラップが床に配置されている場合に連続でダメージを受けにくくなるよう修正。<br>
戦闘中にデータロードを繰り返した際にメモリリークすることがあった問題を修正。<br>
ゲームオーバー時のカメラ移動中にタイトルに戻るとカメラのズーム演出が切り替わらなくなっていた問題を修正。<br>
しっぽり犯されてベンチに帰ったあと、ベンチ前でノエルちゃんがシコって興奮率を0にした場合でもベンチに座るとシコり始めようとする問題を修正。<br>
水の中やガスの中でシコり始めないように修正。<br>
デスアクメビームをバーストで中断した際に無敵時間が反映されなかった問題を修正。<br>
メニューのマップを開いた位置によってマップ右側までスクロールできなかった問題を修正。<br>
パズルを復元したときに箱が正しい位置でないところへワープしていた問題を修正。<br>
意図しない箱の押し出しが可能だった問題を修正。<br>
ショットガンなどバックステップのある攻撃で全ての敵を撃破した場合、受け身行動で部屋の外に出ないように修正。<br>
グラップルシューズ使用時に通常床→通過可能床に侵入できなかった問題を修正。<br>
詠唱時に右方向に詠唱した魔術を左側に撃とうとしたときにアイコンが左側に出るよう修正。<br>
片方のインベントリが空の状態でアイテムの整理を始めたとき、空のインベントリにフォーカスした状態で決定ボタンを押すと不正なウインドウが出ることがあった問題を修正。<br>

攻撃+魔法ボタン押し込みで中バーストを出す際にアイコンを出すように修正。また、被弾または拘束中かそうでないかバーストを出すために必要な押し込み時間が違う仕様があったが、押し込み中にスローモーション演出を追加してどちらの場合でもゲーム進行時間が同じになるようにしました。<br>
tx3に追加, tx_magic, tx_skill に修正があります

#### ver 0.22c (230103)
木偶ミサイルのパッドが開いている最中に攻撃を加えると、残っているミサイル本数分自爆するように修正。<br>
戦闘不能などによって一部ポーズから杖が消える問題を修正。<br>
ボスの召喚した雑魚がボス撃破後にも残存したり、いっぺんに召喚される問題を修正。<br>
ボスの行動ルーチンを修正。危険度が低い状態の第二形態の攻撃を易化、危険度が高い状態の第一形態の攻撃を激しくしました。<br>
ヌシ戦で上部にあった触手の当たり判定を縮小し、ホールドなしサイクロンでも移動しやすく修正。<br>
シールドバッシュや魔法使用後など一部の状態で、ジャンプ・しゃがみ入力でキャンセルできるよう修正。<br>
風が吹く場所でボムなどの配置物がスローモーション演出中にBTBできる問題を修正。<br>
風が吹く場所でボムなどの配置物が壁を突き抜けることがあった問題を修正。<br>
酸木のオードブル下部のベンチにゲームオーバー後に復帰すると床を突き抜けて茨に刺さって二度死ぬ問題を修正。<br>
&color(#60EE3C){&s(){「2回死ね!」}}

#### ver 0.22b (230101)
詠唱中の被ダメージでほとんど魔力を失わない設定になっていた問題を修正。<br>
拘束中にノエルちゃんの色がふしぎなことになることがあった問題を修正。<br>
ボスの上下からの突き刺し攻撃を拘束攻撃に変更。<br>
意図しない当たり判定の接触が起こる問題を修正。<br>
ボスを倒した報酬として一時的にエンハンサースロットx2を街の手前に設置しました。<br>
英語で「WalrossWalross」と表示されていた問題を修正。<br>
ボスのドリル攻撃を受ける際にノエルちゃんがイクって言わなかったので修正。<br>
ボスの茨が複数重なっている際に連続ヒットしないよう修正。<br>
特定条件で本来当たらない敵への攻撃判定に自分が接触することがあった問題を修正。<br>
パズルマップで詰むことがあった問題を修正。<br>
汚染体を倒したときのドロップで名前のない宝箱が出現する問題を修正。<br>
※本来出現しないはずの宝箱が出現することがあったので、出ないように修正しました。<br>
あなたがすでに無名の宝箱を持っている場合、通常通り自由に開けてアイテムを取得して下さい。

以前バージョンのデータは折り畳みます

### バージョン0.21

<details>
  <summary>Click to expand</summary>

#### ver 0.21r (221025)
形の細い動く地形をすりぬけることができた問題を修正。<br>
蛇のAIを調整。地面に潜り続けて出てこない問題、ノエルに当たらない位置で近接攻撃をし続けることがある問題を修正。<br>
家から冒険に出てすぐに「拠点に帰る」を選択するとノエルの部屋に帰ることができなかった問題を修正。<br>
蛇が潜ったときに蛇のシールドエフェクトが出たままになる問題を修正。<br>
電流トラップに敵がひっかかると敵が即死する問題を修正。

#### ver 0.21q (221024)
英語版をWyrd氏監修原稿に差し替え。<br>
タイトルで「はじめから」を選んだときにサウンドが鳴らなかった問題を修正。<br>
ノエルがベンチに座ったときに無に座ることがあった問題を修正。

#### ver 0.21p (221023)
天井が低い2マスの高さの空間で回避できた問題を修正。<br>
セーブデータを選んでいる間に、サムネイルの読み込み中にキャンセルするとエラーが出ていた問題を修正。<br>
落とし穴状になっている蟲沼の端で蟲に捕らわれずに歩くことができた問題を修正。<br>
戦闘エリアの上方で蛇にグラウンドボムを食べさせるとボムがワープする問題を修正。<br>
クラフト中、作ることができる上限量より多い量をカウンターで指定することができ、上限数を超えた量を指定するとエラーが吐かれる問題を修正。<br>
汚染体剣山の挙動を修正。<br>
剣山のドリル攻撃をシールドバッシュで受けたときにふきとばされる問題を修正。<br>
バースト中にダメージを受けることがあった問題を修正。<br>
時おりキャラクターが振動する問題を修正。

#### ver 0.21o (221020)
ベンチに座った際に本の文章が表示されないことがあった問題を修正。<br>
売店のUIで、テキストボックスの表示順の問題を修正。<br>
汚染体スライムが突然大ジャンプする問題を修正。<br>
戦闘中、画面端でふきとばされた時に画面外に吹き飛んでしまう問題を修正。<br>
魔法使用中／被ダメージ中に、アイテムのコマンド一覧から「ショートカット登録」できなかった問題を修正。<br>
狭いマップでカメラが振動することがあった問題を修正。<br>
パーティクルの表示時間を短縮しているとマーカーをセットしたときに一時的に見えなくなっていた問題を修正。

#### ver 0.21n (221007)
ゲームを起動して初めてゲームパッドを使用する際、DirectInput/XInputを自動的に変更するよう修正。<br>
魔女の雑貨店の踏破率が100%にならなかった問題を修正。

#### ver 0.21m (221004) (lは欠番)
道具欄の詳細画面で料理材料としての能力表示に誤りがあった問題修正。<br>
料理材料としての能力表示を x 1xx% と表示していたものを +xx% で統一。<br>
電流線にシールドバッシュをするとバッシュエフェクトが連続で発生する問題を修正。<br>
戦闘エリアの外から魔力植物を摘むと赤い魔力が出てくるが、この仕様が戦闘クリア後も起こっていた問題を修正。<br>
高い位置にいるとスライムが追ってこなくなる問題を修正。<br>
狐戦の後に地面に残った炎の当たり判定が消失する問題を修正。また、地面の炎をシールドでガードできないように変更。<br>
敵を倒した際のフリーズ問題を修正。<br>
V-Sync (垂直同期) オプションを追加。ただFPS60でないモニタだと正常に動作しないかも……<br>
おあずけ状態での自慰行為中にメニューが開けなかった問題を修正。<br>
リールを開ける際にC（ターゲット切り替え）を長押しすると早送りできるよう修正。<br>
XInput/ DirectInput の入力切り替えを実装。<br>
一部のレシピ効果の文章が表示されていなかった問題を修正。<br>
一部レシピ効果の文章を修正（effect_ser_fast）。<br>
きのこを複数料理に使用した際に効果がバラバラに適用されるよう修正。<br>
混乱がわかりやすくなるよう修正。

#### ver 0.21k (221001)
MPを多く持っていて大きめの木偶の歩行音がうるさい問題修正。<br>
時計塔での戦闘時、汚染体木偶がノエルの場所次第で突然止まることがあった問題修正。<br>
狐のエリアから酸の地帯を抜けて肉のなる木の左側でスタックする問題を修正。<br>
ベンチで再生される自慰イベントが予定されている状態でベンチに座らずにセーブした場合、次回起動時に問答無用で自慰イベントが始まる問題修正。<br>
状態異常の残り時間にフチ取りを追加。また残り時間の表示位置がアイコンとズレる問題を修正。<br>
いくつかのフリーズバグを修正。<br>
汚染体スライム戦でいくつかの演出を修正。<br>
愚者との戦闘時、プレイヤーの魔法であるにも関わらずドギャン！という敵魔法の音が鳴ることがあった問題を修正。<br>
localization の英語／日本語以外のデフォルト言語を英語に修正。<br>
料理の効果で拘束からの抜けやすさが0%になっている状態でもほんの僅かに拘束に対応できるよう修正。

#### ver 0.21j (220916) (iは欠番)
的あてエリア等、一部のフリーズ原因となるバグの修正。<br>
右方向にしゃがみながら回避するとカーリングノエルちゃんが可能だった問題を修正。<br>
ベンチからゲームを開始して一度も着地せず蟲沼に飛び込むことを2回行うとステージ外にワープする問題を修正。<br>
ノエルちゃんがシコった後に立ち絵が切り替わっていて余韻ゼロだった問題を修正。<br>
一部マップで敵の壁埋まりが発生することがあった問題修正。

#### ver 0.21h (220914)
一部のフリーズバグを修正。<br>
ヒビの入った壊れる壁（特定の位置から攻撃することを想定したもの）を意図しない位置から破壊することができた問題を修正。

#### ver 0.21g (220913)
最初の戦闘が始まらない問題修正。大変失礼いたしました…

#### ver 0.21f (220912-2)
はぐれ者の戦闘中にスタックすることがあった問題を修正。

#### ver 0.21e (220912)
韓国語、簡体中文B、繁体中文を更新。<br>
同じ種類の宝箱を複数持ち帰ってリールを回す際、それらのうちの1つ分しか開けられなかった問題を修正。

#### ver 0.21d (220911)
バースト使用後に魔力の吸収がロックされるインターバルを設定。(4秒)<br>
アイテムショートカットによる使用方法で、決定ボタンを押してアイテムを使うオプションを追加。<br>
アイテムショートカットでナナメ方向に入力したあと、ニュートラルに戻してもカーソルが戻らなかった問題修正。<br>
戦闘中に敵が画面内から消えたにも関わらず戦闘が終わらないことがあった問題を（たぶん）修正。

#### ver 0.21c (220910)
宝箱リールを複数開けるとUIに白い四角が表示されることがあった問題を修正。<br>
「1行捨てる」の挙動を修正(ストック可能 8 のものを10個持っている時に実行したときに今までは8捨てていたが、これを2捨てるようにしました）<br>
溺れてしまったあと外部のギミックで排水された場合にチェックポイントに戻れなくなることがあった問題を修正。<br>
韓国語のフェイタルシーン文章の行間を調整。<br>
フェイタルシーン時の移動カーソルが残り続ける問題を修正。<br>
妖狐戦の左側のベンチのナイチンゲールの位置を調整。<br>
蛇戦（イクシャ救助ポイント）右上のパズルがボムで無理やり解けた問題を修正。<br>
オートセーブオフの状態でベンチに座った場合、ゲームオーバー時のリスポーン地点として登録されていなかった問題を修正。

#### ver 0.21b (220909)
全体軽量化。<br>
フェイタルシーンの English / Korea / 繁体中文 / 簡体中文A,B 対応。<br>
健全モードONでフェイタルシーンを再生したときにCensoreくんがでかすぎる問題を修正。<br>
健全モードONでフェイタルシーンをスキップしたときに乳首が見える問題を修正。<br>
フェイタルシーン中で言語を変更しても反映されていなかった問題を修正。

#### ver 0.21a (220908)
&color(#2a67ff){フェイタルシーンを1つ実装。}<br>
敵が敵をキルすると攻撃力がアップするよう修正。<br>
汚染体剣山が坂道のあるマップで予想もつかない動きをする問題を修正。<br>
ベンチに座っても状態異常が残ることがあった問題を修正。<br>
拠点に返ったときは状態異常をすぐに治すよう修正。<br>
エフェクト制限で狐が床に落とした炎が見えない問題を修正。<br>
コメットダイブ＋ダブルイベイドによる意図しない位置エネルギーの獲得を修正。<br>
wind の際に流鏑馬など動く足場上の敵の動きがずれる問題を修正。<br>
冒険に出てからのプレイ時間の表示するように修正。<br>
状態異常の残り時間がわかるようにゲージを表示。<br>
ナイチンゲール／レヴィの店でアイテムを全て購入した際に売却が行えなくなる問題を修正。<br>
バースト中に麻痺ダメージが入らないよう修正。<br>
1280x720以外のサイズでキーコンフィグ編集中に、入力フィールドが表示されない問題修正。<br>
電気を浴びることでノエルジュースを永久に回収できる問題を修正。
</details>

### バージョン0.20

<details>
  <summary>Click to expand</summary>
  
#### ver 0.20s (220528-2)
韓国語、繁体中文更新。<br>
ver0.20rのタイトル画面でver0.20qと表示されていたので修正。
  
#### ver 0.20r (220528)
狐と海綿が同時に登場した場合にフリーズすることがあった問題を修正。<br>
狐の火球をバッシュした際に演出が重なることがあった問題を修正。<br>
Apple silicon で動作するmacOSでゲームを起動できなかった問題を修正。<br>
コメットダイブが得られるマップで緑スイッチの押し方で詰むことがあった問題を修正[[ノエルはバカ]]。<br>
剣山のドリル攻撃をシールドバッシュで防げるよう修正。<br>
mpが尽きたヘビが動作停止することがあった問題を修正。
  
#### ver 0.20q (220525)
簡体中文B修正。<br>
INBE（ノエルちゃんべとべとEngine）の初期化時の処理を修正。<br>
ノエルちゃんが汚れた状態でデータをセーブし、再度ロードすると塗り直しの内容に血液描写低減が反映されない問題を修正。
  
#### ver 0.20p (220524)
ver0.09からロードしたデータにレシピやエンハンサースロット等が店の在庫に載らなかった問題を修正。<br>
繁体中文、韓国語更新。<br>
ホワイトアロー、エナジーボールの魔法がスローモーションエフェクト中も速度が落ちず進行していた問題を修正。<br>
雨天時に雨が落ちる地面の座標がズレていた問題を修正。<br>
素材の木から大量のアイテムが出た場合に処理が重くならないよう修正。<br>
ナイチンゲールのお店利用時も、家の倉庫にあるアイテムの在庫数がわかるよう修正。<br>
天気が風の場合は魔法の移動速度も上昇するよう修正。その代わり、風の際の敵の最大出現数補正を -3 → -2 に変更。<br>
坂道でジャンプしているとだんだんと横に飛ばされる問題を修正。<br>
針鼠の右のパズルで、チェックポイントのある部分まで酸が浸水することがあった問題を修正。<br>
複数の敵にノエルが拘束されているときに、新しい敵の拘束が失敗することがあった問題を修正。<br>
自慰シーンをスキップするとノエルジュースや絶頂カウントが得られない問題を修正。<br>
ナイチンゲールさんが売っている素材が正しくなかったので修正。<br>
抱卵中のUIゲージなど、一部の演出の処理を見直して高速化。<br>
スキルの付け替えでHP,MPを回復できていた問題を修正。<br>
レバガチャの表示位置が重なることがあった問題修正。
  
#### ver 0.20o (220523)
ver0.09簡体中国語制作メンバーより簡体中国語版が届きました！！！<br>
Thanks to:[[@rolling_badger>https://twitter.com/rolling_badger]] ,[[@szsrkirby>https://twitter.com/szsrkirby]] ,[[@kokonoekyu>https://twitter.com/kokonoekyu]] ,[[@Chiyuki34885962>https://twitter.com/Chiyuki34885962]], , Phenix02,
繁体中国語更新。<br>
シールド展開中に回避入力を受け付けるオプションを追加。<br>
小攻撃／弱攻撃の表記ゆれを 小攻撃 に統一。<br>
シナリオの誤字を修正。<br>
海綿の竜巻攻撃時のSEのボリュームを下げました。<br>
はぐれ者戦闘中に右側のマップに押しやられることがあった問題修正。<br>
剣山の汚染体の落下攻撃中に杖振りのパリィやシールドバッシュを成功させると反射演出が連続で発生する問題を修正。<br>
マップ上にマーカーを配置できない領域があった問題を修正。<br>
汚染体撃破時はMPが少なくても金色のマナを撒き散らすよう修正。<br>
はにわのお守り使用時の金色のマナの回復量を倍増。<br>
ボムの設置にかかるスピードを高速化。<br>
チャージャースロット使用中はダメージを受けても詠唱分の魔力を失わないよう修正。<br>
普通に魔術詠唱中にチャージャースロットがチャージされる→ホールド→詠唱再開　としたときにチャージャースロットが消費されてしまう問題を修正。<br>
受け身が出にくかった問題を修正。<br>
大量のアイテムが壁に近い素材の木から得られた場合に素材が壁に埋まることがある問題を修正。<br>
混乱Lv.2がかかった状態でロードするとフリーズする問題を修正。<br>
睡眠中でもバーストを撃てるよう修正。<br>
昏倒の状態異常中に拘束を受けた場合に昏倒が解除されないよう修正。<br>
シールドブレイク時の拘束の抜けやすさを改善。<br>
ホワイトアローを鬼連打した場合に魔力の回収効率が落ちるよう修正。<br>
ライフボトルの売価を修正。
  
#### ver 0.20n (220521)
簡体中文B Fansub 収録。 Thanks to: [[哥哥我欧尼酱>https://space.bilibili.com/53443948]]
韓国語アップデート。<br>
ver0.09のデータでアイテムがいっぱいだった場合にロードできなかった問題を修正。<br>
ver0.09から引き継いだデータに、現マップに存在しないベンチや宝箱が記載されていた問題を修正。<br>
「飛瀑の虚」に足場を追加して易化。<br>
敵のオーラの不透明度を強めて夜でも見やすくなるよう修正。
  
#### ver 0.20m (220520)
韓国語, 繁体中国語文章未訳部分修正。<br>
3日目まで、昼／夕方／夜を選択して出発することができるようになりました。<br>
出発してからどこかで戦闘開始する前であれば、夜でもファストトラベル可能です。<br>
2日目に出発するためには3日目まで生き残ってから拠点に帰る必要があります。<br>
バトルの後に1度セーブを挟まないとナイチンゲール・レヴィの店の在庫の更新が実行されなかった問題を修正。<br>
詠唱を始める入力受付時間を大幅に伸ばしました。（回避中に魔法キーを押した時、回避終わりに魔法を詠唱できます）<br>
チャージャースロットを所持したデータを遊んでいる時にチャージャースロットを所持していないデータをロードすると、スロットがUIに残ったままになっていた問題を修正。<br>
ゲームの途中でタイトルに戻った後ゲームを再開すると、文字のテクスチャが破壊されることがある問題を修正。
  
#### ver 0.20k (220519)
繁体中文版未訳部分一部修正。<br>
9個以上の宝箱用リールを取得できるようになり、代わりに宝箱を開ける際に8個になるまで捨てるシステムに修正しました。<br>
狩り場2箇所を往復することで簡単に危険度を獲得できていた問題を修正。<br>
マップ上で菌糸の王の左側が通行できるような表示になっていた問題を修正。<br>
動く床に挟まれた場合に離脱できるよう修正。<br>
For Translaters:<br>
few sentences are added to ＊_tx2.txt .
  
#### ver 0.20j (220516)
繁体中文版実装完了。 感謝感激: [[@zelda05151>https://twitter.com/zelda05151]]<br>
右の壁に走行ボタンを押して走るとノエルちゃんがスプリントを行う問題を修正。<br>
敵の壁埋まりバグについてさらにしっかり修正。<br>
強制戦闘が夜以外も発生していたので、4日以降に限定しました。<br>
家前ベンチのナイチンゲールさんに話しかけたときに位置によってはノエルが落下する問題を修正。<br>
同じ天気が2連続で発生することがあった問題修正。<br>
ノエルジュースの撒き散らしでは天気を進行できないよう修正。<br>
冒険5日目以降は敵の総数を増やさない代わりに敵が爆速でリスポーンするよう修正。<br>
「闇夜の帳」の2日目以降の敵の量を増やしました。
  
#### ver 0.20h (220515)
韓国語版Fansubに対応しました！ Thanks to: [[@Cilloom>https://twitter.com/Cilloom]]<br>
落雷で発生できる汚染体が同時に登場できる上限を設定しました。<br>
2日夜まで1体、5日夜まで2体、以降3体となります。<br>
3日目以降は、現在の冒険で既に撃破した場所でも夜の強襲判定が発生するよう修正。<br>
盗掘者で落雷が起きると汚染体が床に埋まる問題を修正。<br>
ナイチンゲールがいるマップでセーブするとロード時にでてきてくれない問題を修正。<br>
バースト中にもアイテムを使用できた問題を修正。<br>
昏倒中に受けた拘束攻撃のレバガチャ入力が増えていなかった問題を修正。<br>
たくさん産み付けられても抱卵Lv2が発生しないことがあった問題を修正。<br>
無限に宝箱を開けられることがあった問題を修正。<br>
オプション項目が全ての言語で「Enabled」「Disabled」だった部分を修正。<br>
店での買い物の際、アイテムがいっぱいの時はアラートが出るよう修正。<br>
店での買い物の際にグレードが異なるアイテムでもノエルが既に持っている場合は列右側にアイコンが出るよう修正。<br>
ゲームの途中で中国語などのフォントを変更しての言語に変えたときにイベントメッセージが変化していなかった問題を修正。
  
#### ver 0.20g (220514)
走行ボタンを実装。またデフォルトのキーマップを調整。<br>
ノエルジュース、卵のグレードがノエルの性的感度の成長で質が上がるよう修正。<br>
狐のいるところに上から侵入した場合夜だと帰れない問題があったのでエリアを追加。これにより現状100%だったマップ踏破率が少し下がります。<br>
はにわのお守り使用時は回復アイテムの使用時に効果が倍になるよう修正。<br>
はにわ使用時に大量に抱卵していた状態ではにわを外した時にUI上で卵が突き抜ける問題を修正。<br>
はにわ使用時は回復薬の効果が2倍になるよう修正。<br>
ブロッコリーの特殊効果文章が見ててなかったので修正。<br>
おもらししてしまった時にデータをロードするとノエルちゃんが尿圧でふっとぶ問題を修正。<br>
アイテム整理時のバグを修正。<br>
サイクロンで壁に反射された直後に魔術を使うとBTBノエルちゃんが発生する問題を修正。<br>
落下しながら結界を抜けると結界がオフにならないことがあった問題、結界に入っても結界がオンにならない問題を修正。<br>
ボムでは壊せずスライディングでしか壊せない床を修正。<br>
ボムを多数配置して自動的に爆発するときは上方向に爆風が及ぶよう修正。<br>
坂道に落ちたアイテムを拾いにくい問題を修正。<br>
被虐ログ設定で消せないメッセージがあった問題を修正。<br>
レバガチャの際、シーケンス入力の場合は上下左右のみのQTEが出るよう修正。<br>
HP/MPスキルを付け替えたときはHP/MPが据え置きになるよう修正。<br>
バッドステータスの際もレバガチャが抜けやすくなるよう修正（はにわ使用時はさらに抜けやすく）<br>
魔術師が魔法を放ったあとダメージを与えると予告線が消える問題を修正。<br>
少ないMPでバーストを連打した場合に状態異常「昏倒」が付与するよう修正。<br>
敵が壁内でスタックした時に戦闘エリアに戻ってくるよう修正。<br>
敵がふっとばされのあと復帰しないことがあった問題を修正。<br>
グラウンドボムがちくわブロックに反応してしまう問題修正。<br>
長い杖をつけたときの杖振りがショットガン判定になっておらず茸のガードを貫通しなかった問題を修正。<br>
長い杖が下方向に伸びていたプラセボエンハンサーだった問題を修正。<br>
同じ天気が複数発生することがあった問題を修正。<br>
マウス使用時、料理UIの「～個作成」にフォーカスできなかった問題を修正。<br>
戦闘終了時に抱卵Lv2を抱えていても排卵が始まらなかった問題を修正。<br>
サイクロンスラッシュの出始めに天井等に当たり判定が接触するとエフェクトが消えていた問題を修正。<br>
ナイチンゲールさんの鈴を捨てたら鈴を再度売ってくれるよう修正。<br>
ウインドウサイズを変更できるよう修正。<br>
アイテム欄がいっぱいの状態で水を入手した際に正しく取得できない問題を修正。<br>
セーブやコンフィグを開いたあとにアイテムメニューを開くと説明欄の配置が壊れる問題を修正。<br>
アイテム説明に表示される回復量と実際の回復量が1ずれることがあった問題を修正。<br>
敗北時に即ロードするとロードに失敗することがあった問題を修正。<br>
一定条件でホワイトアローを鬼連打できるようになる問題を修正。<br>
リロードするとレヴィ／ナイチンゲールさんの店の内容が変わることがあった問題を修正。<br>
狩り場とベンチが同マップ内にあるときに、狩り場で敵を倒したあとすぐにセーブすると、リロード時にいなかったはずのナイチンゲールさんが登場することがあった問題を修正。<br>
ログが大量に発行されているときにメニューを開いて閉じるとスタックされたログが重なって表示されていた問題を修正。<br>
バースト発射時に霧を吹き飛ばすよう修正。<br>
混乱が解けたときにエフェクトを追加。また、混乱中に拘束を受けた場合は吹き出しの色を変えるよう修正。<br>
危険度最大値を160まで延長。<br>
同じ場所で天気ガチャができる問題を修正。<br>
巨木内の夜戦闘でタイトルが表示されていない部分があった問題を修正。<br>
For Translater:<br>
tx_enemy Summoner_forest_wood_nightlake => Summoner_forest_nightlake<br>
Summoner__obtainable_dangerousness<br>
tx2 追加: SerTitle_burst_tired/ SerDesc_burst_tired<br>
tx_option 項目を複数追加。<br>
  
#### ver 0.20e (220509)
言語環境バグをさらに修正。<br>
Fixed a bug that could occur in the region environments.<br>
イクシャ救出イベント中におあずけ状態になって戦闘後シコり始めた時にはイクシャちゃんに待っていただくよう修正。<br>
リスポーンした際にカメラが荒ぶる問題を修正。<br>
処理多少を高速化。<br>
一部環境で立ち絵のテクスチャが壊れることがあった問題を修正。
  
#### ver 0.20d (220508 19:00)
起動時にハングアップする問題修正。<br>
ゲームパッドモードで這って歩く動きがでやすくなるよう修正。
  
#### ver 0.20c (220508)
フランス語のOSでノエルちゃんが非常に大きく表示されるなど正しく動作しない問題をおそらく修正。<br>
： (Maybe) fixed problems on a French OS (e.g. portrait of Noel-chan is displayed very large)<br>
： If you still have problems with ver 0.20c, please comment including your detailed language environment and OS!<br>
80.21%で宝箱回収率が打ち止めだった問題を修正。<br>
キーコンフィグのラベル入力GUIがWindows版で表示されていなかった問題を修正。<br>
2日目の最初に家から森に出たときに、一度家に帰らないと「拠点に帰る」がアンロックされない問題を修正。<br>
イクシャ救助後は家の道の大岩が自動的に破壊されるよう修正。<br>
※蟲チュートリアルを通過している、もしくはイクシャを救助後したか杖のSOS受信イベントを見た後なら自動的に破壊されます。<br>
「拠点に帰る」を選択した場合はノエルの部屋に戻るよう修正。<br>
家の左下の湖でセーブすると詰みセーブと化す問題を修正。<br>
現状イクシャを救出して以降のシナリオはありませんが、暫定の目的地を設定。<br>
イクシャ救出地点から右上のマップのパズルのヒントをわかりやすくしました。<br>
ボムの爆破エフェクトの表示位置がずれていたので修正<br>
茸の汚染体（菌糸の王）が壁ハメしてこないよう修正。また、チャージ時にMPを撒き散らすようにし、MP不足時はチャージ時間が伸びるよう修正。<br>
これまで割合ダメージで計算されていた酸／電流／壁挟まれダメージを、スキルによるHPの補正値によって割合が下がるよう修正。<br>
オーバーチャージャーで魔法を使ったときにサイクロン／コメットダイブを打ってもUIが更新されなかった問題を修正。<br>
MPゲージがヒビだらけの時はオーバーチャージャーが溜まりやすくなるよう修正。<br>
ガチャの入力が☓点滅し見えなくなることがある問題を修正。<br>
メニュー表示と決定を同じインプットにした場合にメニューを開く前にイベントに話しかける等が優先されていた問題を修正。<br>
レバガチャで左タブ入力／右タブ入力が出ないよう修正。<br>
キーボード使用時のトラブルを修正。<br>
ガチャガチャ周りのエラーを多少修正。ただレバガチャ表示が消えるかも……。<br>
サイクロン壺おじノエルちゃんはおもしろいので次のメジャーアップデートまで修正されません。
  
#### ver 0.20b (220506)
商人さんのお店で「紡ぐ者の森の地図」が販売されるようになります。<br>
： 一度店在庫の入れ替えが発生しないと売りに出されませんので、今ベンチの近くに商人さんがいるときは一度戦闘を挟む必要があります<br>
2日目最初の回避チュートリアルアスレチックを軟化しました。<br>
macOS版でINBE(ノエルちゃんを汚すエンジン)の彩色が薄かった問題を修正。<br>
： それに伴い、コンフィグの「UI汚れ表現濃度」を一旦初期化しています。<br>
狩り場「ドッグラン」で、敵の数が多い危険度で戦闘を開始する敵が埋まることがあった問題修正。<br>
「胞子の踊り場」左下で蟲沼に落下すると戻って来れないことがあった問題修正。<br>
剣山の突進攻撃がすぐに終了して見掛け倒しだった問題修正。<br>
ベンチに座った際に衣服を修繕しない設定が機能していなかった問題を修正。<br>
ロードした際宝箱やベンチなどのアイコンが左上に寄っていた問題を修正。<br>
マップ上の狩り場がセーブデータに記録されていなかった問題を修正。<br>
剣山の汚染体が針の突出攻撃を出している最中に倒すとフリーズする問題を修正。<br>
狩り場「酸底の針鼠」の上部のマップのパズルで詰みパターンが発生する問題を修正。<br>
茸の汚染体の霧チャージ時間を90Fから130Fに変更（倒しやすくなります）<br>
汚されたノエルちゃんの汚れた箇所がセーブ・ロードを挟むと位置がズレる問題を修正。<br>
狩り場「酸木のオードブル」で地形に挟まれた状態で戦闘が開始することがあった問題を修正。<br>
狩り場「酸木のオードブル」で撃破時にバグが発生し地形判定が残るままになることがあった問題を修正。
</details>
