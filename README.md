# BASTET <img src="source/BASTET.png" width=50>
clon**A**l haema**T**opoiesis varian**T** pr**E**diction **B**ased on liquid **S**equencing for C-CAT database.   
Copyright (c) 2025 Masachika Ikegami, Released under the [MIT license](https://opensource.org/license/mit).  

### C-CAT CALICO データベースを用いたClonal haematopoiesisの解析Webアプリ
国立がん研究センターに設置されている[がんゲノム情報管理センター(C-CAT)](https://www.ncc.go.jp/jp/c_cat/use/index.html)には保険診療で行われたがん遺伝子パネル検査(Comprehensive Genomic Profiling, CGP検査)の結果と臨床情報が集約されています。この情報を学術研究や医薬品等の開発を目的とした二次利活用する仕組みがあります。現状では所属施設の倫理審査とC-CATでの倫理審査を経た研究でのみ使用可能であり、また病院やアカデミア以外の組織では年間780万円の利用料金が必要と敷居が高いですが、類似した海外のデータベースである[AACR project GENIE](https://www.aacr.org/professionals/research/aacr-project-genie/)と比較して薬剤の情報や臨床情報が詳しい点で優れており、希少がん・希少フラクションの研究においてこれまでになかった切り口での解析が可能になると考えられています。  
  
C-CATのデータを用いるに当たってはビッグデータかつリアルワールドデータの解析には特有の問題があり、また一定程度のデータ処理を行うプログラミングの知識が必要になります。GUIを用いたソフトウェアにより解析の敷居を下げることで、臨床医の日常診療におけるクリニカルクエスチョンに基づいた探索的研究を容易とし、C-CAT利活用データの活用を促進するために本ソフトウェアを作成しました。本ソフトウェアは特にliquid sequencingの結果を基にしてclonal haematopoiesisの詳細を明らかにする目的で開発を進めています。  
  
C-CATのデータベースは検査会社でキュレーション後の患者さんに返却されたレポートの情報を公開する利活用検索ポータルと、検査会社でのシーケンスデータ（CRAMファイル）を公開する利活用クラウド C-CAT CALICO (CALculation ＆ Investigation ClOud)の2種類から構成されており、CALICOは公開範囲が極めて制限されているのが現状です。非常にもったいないと思います。  
  
現状はC-CAT CALICOからデータを入手可能な方のみが本ソフトウェアを使用可能となる現状はご理解ください。論文としての公開後は自由に使用可能にできる見込みです。  

