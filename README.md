# Fortnite-LobbyBot
[![Python Versions](https://img.shields.io/badge/3.7%20%7C%203.8-blue)](https://www.python.org/downloads/)  
<a href="https://discord.gg/NEnka5N"><img src="https://discordapp.com/api/guilds/718709023427526697/widget.png?style=banner2" /></a>  
English is [Here](https://github.com/gomashio1596/Fortnite-LobbyBot/blob/master/README_EN.md "README_EN.md")  
El español está [aquí](https://github.com/gomashio1596/Fortnite-LobbyBot/blob/master/README_ES.md "README_ES.md")  
Fortnitepyを使用したFortniteのボット  
コマンドを送ることで操作ができる  

# 導入
# PC
https://github.com/gomashio1596/Fortnite-LobbyBot  
[Python 3.7](https://www.python.org/downloads "Pythonダウンロード")以上が必要  

INSTALL.batを実行する  
RUN.batを実行する  
開いたサイトでconfigを設定する  
タブを再読み込みすることで他の設定もできます  

#Repl.it
https://repl.it  
の右上の"sign up"を押してログインする  
右上の"+ new repl"を押して、"Import From GitHub"タブを開く  
https://github.com/gomashio1596/Fortnite-LobbyBot  
をコピーして"Paste any repository URL"に貼り付ける  
Import from Githubを押す  
開いたページ(replページと呼びます)の上の"run▶"を押す  

# Glitch
Glitchは24時間起動をすることができなくなったので推奨されません!

https://glitch.com  
の右上のSign inを押してGlitchアカウントを作る  
https://fortnite-lobbybot.glitch.me  
Remixを押してRemixする  
左上の四角いマークを押して、Make This Project Privateにチェックを入れてプロジェクトに鍵を掛ける  
上のShowを押してIn a New Windowを押す  
開いたサイトでconfigを設定する  
タブを再読み込みすることで他の設定もできます  

# Web
初回起動ではconfigの設定が出る  
次回以降は設定したパスワードを入力することで、config等の設定、パーティーの状態の確認等ができる  

# config
```
Fortnite
email                     : ボット用アカウントのメールアドレス。 , で区切ることで複数設定可
password                  : ボット用アカウントのパスワード。 , で区切ることで複数設定可
owner                     : 所有者として設定したいユーザーの名前またはID
platform                  : ボットのプラットフォーム。 後述
cid                       : ボットの初期コスチュームID
bid                       : ボットの初期バックアクセサリーのID
pickaxe_id                : ボットの初期収集ツールのID
eid                       : ボットの初期エモートのID
playlist                  : ボットの初期プレイリストのID
banner                    : ボットの初期バナーのID
banner_color              : ボットの初期バナーの色ID
level                     : ボットの初期レベル
tier                      : ボットの初期ティア
xpboost                   : ボットの初期XPブースト
friendxpboost             : ボットの初期フレンドXPブースト
status                    : ボットの初期ステータス
privacy                   : ボットの初期のプライバシー。 後述
whisper                   : ボットが囁きからコマンドを受け付けるかどうかの設定。 true か false
partychat                 : ボットがパーティーチャットからコマンドを受け付けるかどうかの設定。 true か false
disablewhisperperfectly   : 囁きが無効の場合、所有者も使えなくするかどうかの設定
disablepartychatperfectly : パーティーチャットが無効の場合、所有者も使えなくするかどうかの設定
ignorebot                 : ボットからのコマンドを無視するかどうかの設定。 true か false
joinmessage               : ボットのパーティーに誰かが参加した時のメッセージ。 \n で改行
randommessage             : ボットのパーティーに誰かが参加した時のランダムメッセージ。 , で区切る \n で改行
joinmessageenable         : ボットのパーティーに誰かが参加した時にメッセージを出すかどうかの設定。 true か false
randommessageenable       : ボットのパーティーに誰かが参加した時にランダムメッセージを出すかどうかの設定。 true か false
outfitmimic               : 他人のコスチュームを真似るかどうかの設定。 true か false
backpackmimic             : 他人のバックアクセサリーを真似るかどうかの設定。 true か false
pickaxemimic              : 他人の収集ツールを真似るかどうかの設定。 true か false
emotemimic                : 他人のエモートを真似るかどうかの設定。 true か false
acceptinvite              : ボットが招待を承諾するかどうかの設定。 所有者からの招待は常に承諾 true か false
acceptfriend              : ボットがフレンド申請を承諾するかどうかの設定。 true か false か null
addfriend                 : ボットがパーティーメンバーにフレンド申請を送るかどうかの設定。 true か false
invite-ownerdecline       : ボットの所有者がパーティーにいるときに招待を拒否するかどうかの設定。 true か false
inviteinterval            : 招待を承諾した後intervalの秒数だけ招待を拒否するようにするかどうかの設定。 true か false
interval                  : 招待を承諾した後招待を拒否する秒数
waitinterval              : waitコマンドで招待を拒否する秒数
blacklist                 : ブラックリストに指定するユーザーのリスト。 ユーザー名かユーザーID
blacklist-declineinvite   : ブラックリストのユーザーからの招待を拒否するかどうかの設定。 true か false
blacklist-autoblock       : ブラックリストのユーザーをブロックするかの設定。 true か false
blacklist-autokick        : ブラックリストのユーザーを自動的にパーティーからキックするかの設定。 true か false
blacklist-autochatban     : ブラックリストのユーザーを自動的にチャットバンするかどうかの設定。 true か false
blacklist-ignorecommand   : ブラックリストのユーザーからのコマンドを無視するかどうかの設定。 true か false
whitelist                 : ホワイトリストに指定するユーザーのリスト。 ユーザー名かユーザーID
whitelist-allowinvite     : ホワイトリストのユーザーがボットをいつでも招待できるようにするかの設定。 true か false
whitelist-declineinvite   : ホワイトリストのユーザーがパーティーにいるとき、招待を拒否するかどうかの設定。 true か false
whitelist-ignorelock      : ホワイトリストのユーザーがスキンロック等を無視できるかどうかの設定。 true か false
whitelist-ownercommand    : ホワイトリストのユーザーが所有者コマンドを使えるかどうかの設定。 true か false
invitelist                : inviteallコマンドで招待するユーザーのリスト
otherbotlist              : ignorebotで無視する他のボット

Discord
enabled                   : Discord Botを起動するかどうかの設定 true か false
token                     : Discord Botのトークン
owner                     : 所有者のユーザーID
channelname               : ボットのコマンドチャンネルとして使用するチャンネルのチャンネル名 後述
status                    : Discord Botのステータス
discord                   : ボットがDiscordからコマンドを受け付けるかどうかの設定 true か false
disablediscordperfectly   : Discordが無効の場合、所有者も使えなくするかどうかの設定
blacklist                 : ブラックリストに指定するユーザーのリスト ユーザーID
blacklist-ignorecommand   : ブラックリストのユーザーからのコマンドを無視するかどうかの設定 true か false
whitelist                 : ホワイトリストに指定するユーザーのリスト ユーザーID
whitelist-ignorelock      : ホワイトリストのユーザーがスキンロック等を無視できるかどうかの設定 true か false
whitelist-ownercommand    : ホワイトリストのユーザーが所有者コマンドを使えるかどうかの設定 true か false

Web
enabled                   : ウェブサーバーを起動するかどうかの設定 true か false
ip                        : ウェブサーバーのIPアドレス 後述
port                      : ウェブサーバーのポート番号
password                  : ウェブサーバーのパスワード
login_required            : ウェブサーバーにアクアスするのにパスワードが必要かどうかの設定 true か false
web                       : ウェブからのコマンドを受け付けるかどうかの設定 true か false
log                       : ウェブサーバーのアクセスログを出すかどうかの設定 true か false

lang                      : ボットの言語
search-lang               : アイテム検索に使う言語
restart_in                : ボットが再起動するまでの時間
no-logs                   : コンソールにログを出すかどうかの設定 true か false
ingame-error              : プレイヤーにエラーを送信するかどうかの設定 true か false
discord-log               : Discordにログを送信するかどうかの設定 true か false
hide-email                : Discordのログでメールアドレスを隠すかどうかの設定 true か false
hide-password             : Discordのログでパスワードを隠すかどうかの設定 true か false
hide-token                : Discordのログでトークンを隠すかどうかの設定 true か false
hide-webhook              : Discordのログでwebhookのurlを隠すかどうかの設定 true か false
webhook                   : Discordのwebhookのurl
caseinsensitive           : コマンドを大文字小文字、平仮名片仮名を区別しないかどうかの設定 true か false
loglevel                  : ログにどのくらいの情報を流すか normal か info か debug
debug                     : Fortnitepyのデバッグモードをオンにするかどうかの設定 true か false
```

# コマンド一覧
コマンド名はcommands.json内の表記  
全て , で区切ることで複数設定可  
アイテム名を打つことでそのアイテムにすることもできる  

```
ownercommands                             : 所有者しか使えないコマンドを指定する
true                                      : コマンドの true として扱う文字列
false                                     : コマンドの false として扱う文字列
me                                        : コマンドの送り主として扱う文字列
prev                                      : 一つ前のコマンドを繰り返す
eval                                      : eval [プログラム] 内容を式として評価し、その内容を返す
exec                                      : exec [プログラム] 内容を文として評価し、その内容を返す
restart                                   : プログラムを再起動する
relogin                                   : アカウントに再ログインする
reload                                    : configとcommandsを再読み込みする
addblacklist                              : addblacklist [ユーザー名/ユーザーID] ユーザーをFortniteのブラックリストに追加する
removeblacklist                           : removeblacklist [ユーザー名/ユーザーID] ユーザーをFortniteのブラックリストから削除する
addwhitelist                              : addwhitelist [ユーザー名/ユーザーID] ユーザーをFortniteのホワイトリストに追加する
removewhitelist                           : removewhitelist [ユーザー名/ユーザーID] ユーザーをFortniteのホワイトリストから削除する
addblacklist_discord                      : addblacklist_discord [ユーザーID] ユーザーをDiscordのブラックリストに追加する
removeblacklist_discord                   : removeblacklist_discord [ユーザーID] ユーザーをDiscordのブラックリストから削除する
addwhitelist_discord                      : addwhitelist_discord [ユーザーID] ユーザーをDiscordのホワイトリストに追加する
removewhitelist_discord                   : removewhitelist_discord [ユーザーID] ユーザーをDiscordのホワイトリストから削除する
addinvitelist                             : addinvitelist [ユーザー名/ユーザーID] ユーザーを招待リストに追加する
removeinvitelist                          : removeinvitelist [ユーザー名/ユーザーID] ユーザーを招待リストから削除する
get                                       : get [ユーザー名/ユーザーID] パーティーにいるユーザーの情報を取得する
friendcount                               : 現在のフレンド数を表示する
pendingcount                              : 現在のフレンド申請数を表示する(方向関係なし)
blockcount                                : 現在のブロック数を表示する
friendlist                                : 現在のフレンドリストを表示する
pendinglist                               : 現在のフレンド申請リストを表示する
blocklist                                 : 現在のブロックリストを表示する
outfitmimic                               : outfitmimic [true / false] 他人のスキンを真似るかどうかの設定
backpackmimic                             : backpackmimic [true / false] 他人のバッグを真似るかどうかの設定
pickaxemimic                              : pickaxemimic [true / false] 他人のツルハシを真似るかどうかの設定
emotemimic                                : emotemimic [true / false] 他人のエモートを真似るかどうかの設定
whisper                                   : whisper [true / false] 囁きからのコマンドを受け付けるかどうかの設定
partychat                                 : partychat [true / false] パーティーチャットからのコマンドを受け付けるかどうかの設定
discord                                   : discord [true / false] Discordからのコマンドを受け付けるかどうかの設定
web                                       : web [true / false] ウェブからのコマンドを受け付けるかどうかの設定
disablewhisperperfectly                   : whisperperfect [true / false] 囁きが無効の時、所有者も使えなくするかどうかの設定
disablepartychatperfectly                 : partychatperfect [true / false] パーティーチャットが無効の時、所有者も使えなくするかどうかの設定
disablediscordperfectly                   : discordperfect [true / false] Discordが無効の時、所有者も使えなくするかどうかの設定
acceptinvite                              : acceptinvite [true / false] パーティー招待を承諾するかどうかの設定
acceptfriend                              : acceptfriend [true / false] フレンド申請を承諾するかどうかの設定
joinmessageenable                         : joinmessageenable [true / false] パーティーに誰かが参加した時のメッセージを出すかどうかの設定
randommessageenable                       : randommessageenable [true / false] パーティーに誰かが参加したときのランダムメッセージを出すかどうかの設定
wait                                      : configのwaitintervalの秒数だけ招待を拒否する
join                                      : join [ユーザー名/ユーザーID] ユーザーのパーティーに参加する
joinid                                    : joinid [パーティーID] パーティーに参加する
leave                                     : パーティーを離脱する
invite                                    : invite [ユーザー名 / ユーザーID] ユーザーをパーティーに招待する
inviteall                                 : configのinvitelistのユーザーを招待する
message                                   : message [ユーザー名 / ユーザーID] : [内容] ユーザーにメッセージを送信する
partymessage                              : partymessage [内容] パーティーチャットにメッセージを送信する
sendall                                   : sendall [内容] 全てのボットに同じコマンドを実行する
status                                    : status [内容] ステータスを設定する
banner                                    : banner [バナーID] [バナーの色] バナーを設定する
level                                     : level [レベル] レベルを設定する
bp                                        : bp [ティア] [XPブースト] [フレンドXPブースト] バトルパス情報を設定する
privacy                                   : privacy [privacy_public / privacy_friends_allow_friends_of_friends / privacy_friends / privacy_private_allow_friends_of_friends / privacy_private] パーティーのプライバシーを変更する
privacy_public                            : privacy コマンドで使う privacy_public
privacy_friends_allow_friends_of_friends  : privacy コマンドで使う privacy_friends_allow_friends_of_friends
privacy_friends                           : privacy コマンドで使う privacy_friends
privacy_private_allow_friends_of_friends  : privacy コマンドで使う privacy_private_allow_friends_of_friends
privacy_private                           : privacy コマンドで使う privacy_private
getuser                                   : getuser [ユーザー名 / ユーザーID] ユーザーの名前とIDを表示する
getfriend                                 : getefriend [ユーザー名 / ユーザーID] ユーザーの名前とIDを表示する
getpending                                : getpending [ユーザー名 / ユーザーID] ユーザーの名前とIDを表示する
getblock                                  : getblock [ユーザー名 / ユーザーID] ユーザーの名前とIDを表示する
info                                      : info [info_party / info_item / id / skin / bag / pickaxe / emote] パーティー/アイテムの情報を表示する
info_party                                : info コマンドで使う info_party
pending                                   : pending [true / false] 保留しているフレンド申請を全て承諾/拒否する
removepending                             : 自分が送ったフレンド申請を全て解除する
addfriend                                 : addfriend [ユーザー名 / ユーザーID] ユーザーにフレンド申請を送信する
removefriend                              : removefriend [ユーザー名 / ユーザーID] ユーザーをフレンドから削除する
removeallfriend                           : removeallfriend 全てのフレンドを削除する
acceptpending                             : acceptpending [ユーザー名 / ユーザーID] ユーザーからのフレンド申請を承諾する
declinepending                            : declinepending [ユーザー名 / ユーザーID] ユーザーからのフレンド申請を拒否する
blockfriend                               : blockfriend[ユーザー名 / ユーザーID] ユーザーをブロックする
unblockfriend                             : unblockfriend [ユーザー名 / ユーザーID] ユーザーをブロック解除する
chatban                                   : chatban [ユーザー名 / ユーザーID] : [理由(任意)] ユーザーをチャットバンする
promote                                   : promote [ユーザー名 / ユーザーID] ユーザーにパーティーリーダーを譲渡する
kick                                      : kick [ユーザー名 / ユーザーID] ユーザーをキックする
ready                                     : 準備OK 状態にする
unready                                   : 準備中 状態にする
sitout                                    : 欠場中 状態にする
match                                     : match [人数(任意)] マッチ状態を設定する
unmatch                                   : マッチ状態を解除する
swap                                      : swap [ユーザー名 / ユーザーID] ユーザーと位置を交換する
outfitlock                                : outfitlock [true / false] スキンの変更をするかどうかの設定
backpacklock                              : backpacklock [true / false] バッグの変更をするかどうかの設定
pickaxelock                               : pickaxelock [true / false] ツルハシの変更をするかどうかの設定
emotelock                                 : emotelock [true / false] エモートの変更をするかどうかの設定
stop                                      : エモート/all系コマンドの表示を停止する
alloutfit                                 : 全てのコスチュームを表示する
allbackpack                               : 全てのバックアクセサリーを表示する
allpet                                    : 全てのペットを表示する
allpickaxe                                : 全ての収集ツールを表示する
allemote                                  : 全てのエモートを表示する
cid                                       : cid [CID] CIDでアイテムを検索し、見つかったアイテムに設定する
bid                                       : bid [BID] BIDでアイテムを検索し、見つかったアイテムに設定する
petcarrier                                : petcarrier [Petcarrier] Petcarrierでアイテムを検索し、見つかったアイテムに設定する
pickaxe_id                                : pickaxe_id [Pickaxe_ID] Pickaxe_IDでアイテムを検索し、見つかったアイテムに設定する
eid                                       : eid [EID] EIDでアイテムを検索し、見つかったアイテムに設定する
emoji_id                                  : emoji_id [Emoji] Emojiでアイテムを検索し、見つかったアイテムに設定する
toy_id                                    : toy_id [Toy] Toyでアイテムを検索し、見つかったアイテムに設定する
id                                        : id [ID] IDでアイテムを検索し、見つかったアイテムに設定する
outfit                                    : outfit [コスチューム名] コスチューム名でコスチュームを検索し、見つかったアイテムに設定する
backpack                                  : backpack [バックアクセサリー名] バックアクセサリー名でバックアクセサリーを検索し、見つかったアイテムに設定する
pet                                       : pet [ペット名] ペット名でペットを検索し、見つかったアイテムに設定する
pickaxe                                   : pickaxe [収集ツール名] 収集ツール名で収集ツールを検索し、見つかったアイテムに設定する
emote                                     : emote [エモート名] エモート名でエモートを検索し、見つかったアイテムに設定する
emoji                                     : emoji [エモートアイコン名] エモートアイコン名でエモートアイコンを検索し、見つかったアイテムに設定する
toy                                       : toy [おもちゃ名] おもちゃ名でおもちゃを検索し、見つかったアイテムに設定する
item                                      : item [アイテム名] アイテム名でアイテムを検索し、見つかったアイテムに設定する
set                                       : set [セット名] セット名でアイテムを検索し、見つかったアイテムに設定する
setvariant                                : setvariant [skin / bag / pickaxe] [variant] [数値] variant/数値は無限に設定可 数が合わない場合は無視される。スタイル情報を設定する。後述
addvariant                                : addvariant [skin / bag / pickaxe] [variant] [数値] variant/数値は無限に設定可 数が合わない場合は無視される。現在のスタイル情報にスタイル情報を追加する。後述
setstyle                                  : setstyle [skin / bag / pickaxe] 現在付けているアイテムのスタイルを検索し、そのスタイルに設定する
addstyle                                  : addstyle [skin / bag / pickaxe] 現在付けているアイテムのスタイルを検索し、そのスタイルに現在のスタイルを追加する
setenlightenment                          : setenlightenment [数値] [数値] enlightenment情報を設定する 後述
outfitasset                               : outfitasset [アセットパス] スキンをアセットパスから設定する
backpackasset                             : backpackasset [アセットパス] バッグをアセットパスから設定する
pickasset                                 : pickasset [アセットパス] ツルハシをアセットパスから設定する
emoteasset                                : emoteasset [アセットパス] エモートをアセットパスから設定する
```

# replies
"反応するメッセージ": "返す文字列"  
のように設定する  
複数ある場合は下のように , をつける  
```
{
    "hello": "こんにちは",
    "goodbye": "さようなら"
}
```

# その他
プラットフォーム  
```
Windows     : WIN
Mac         : MAC
PlayStation : PSN
XBox        : XBL
Switch      : SWT
IOS         : IOS
Android     : AND
```

プライバシー  
```
public                           : パブリック
friends_allow_friends_of_friends : フレンド(フレンドのフレンドを許可)
friends                          : フレンド
private_allow_friends_of_friends : プライベート(フレンドのフレンドを許可)
private                          : プライベート
```

チャンネル名  
使用可能な変数  
```
{name}                           : ボットのディスプレイネーム
{id}                             : ボットのID
```

デフォルトの  
{name}-command-channel  
でボットの名前が  
Test Bot1  
Test Bot2  
の場合  
Test-Bot1-command-channel  
Test-Bot2-command-channel  
がそれぞれコマンドチャンネルとして使える  

IP  
使用可能な変数  
```
{ip}                           : デフォルトのIP
```

variant  
```
pattern/numeric/clothing_color/jersey_color/parts/progressive/particle/material/emissive
基本的にはmaterialやprogressive,partsなどか多く使われている
紫スカルトルーパーの場合は clothing_color 1
jersey_color はサッカースキンで使われます
```

enlightenment  
```
8ボールvsスクラッチのグリッチなどの情報
シーズン(チャプター2内) / 数値 の組み合わせ
```