TTXShowCommandLine -- コマンドライン文字列を表示する

機能:
  起動時、および接続時のコマンドライン文字列を表示します。
  主にデバッグ用途を想定して作られました。

解説:
  このTTXを入れると、どのようなコマンドラインが指定されたか表示されるように
  なります。
  例えば、TeraTerm MenuやLogMeTTからどのようなコマンドラインで起動されたが
  確認したり、ttsshがコマンドラインを解釈した結果どのように書き換えたかを
  確認したり出来ます。

  どの段階でのコマンドラインを表示するかは、ORDERの値で調整します。
  デフォルトではttsshで解釈された後のコマンドラインを表示しますが、
  ORDERを2500より小さくすると、ttsshで解釈する前のコマンドラインを
  表示します。

バグ:
  今のところ見つかっていません。
