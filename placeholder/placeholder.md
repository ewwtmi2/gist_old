プレースホルダー用のspanとフォーム本体を重ねて配置  
フォーカス基準で表示を切り替えているだけで、特になにか判定はさせていない  
spanはabsoluteさせているので、z-indexなしでも優先して上に重ねられる  
http://codepen.io/ewwtmi/pen/ygGxxj

XHTMLだとvalueを送信してしまうので、初期値は空にしておくこと

ちなみに、if文の内部にaddClass等を追加すれば、プレースホルダー部分だけでなく  
「フォーカス時にフォームの色を変える」  
「フォーカスが外れたらフォームの色を戻す」  
とかも可能