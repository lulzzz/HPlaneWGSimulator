﻿# H面導波管シミュレーター(HPlaneWGSimulator)  
  
**News**

***2012-10-15 version1.2.0.9 Release***
線形方程式の求解処理でメモリの確保方法を効率化しました。計算速度は上がっていると思います。よろしければお試しください。  

**Summary**  
2次元有限要素法を使用してH面導波管回路の反射、透過特性を計算するアプリケーションです。  
30×30のマス目からなる方眼紙上でマス目を選択して回路形状を指定できます。  
電界分布及び散乱係数の周波数特性を図示できます。  
誘電体を充填した導波管を入出力に指定できます。一部充填もできます。  

なお、本アプリケーションでは行列の固有値計算及び線形方程式計算にKrdLab氏のLisysを用いています。  
また、有限要素法行列の計算に関して一部梅谷信行氏のDelFEMを参考にしています。ここに記し深謝致します。  
  
**About License**  
HPlaneWGSimulatorのアセンブリ、ソースコード（下記注釈を除く）の著作権は、りゅうじみやにありますが、それらの利用になんら制限はありません。ただし、動作の保証はできませんので予め御了承願います。  
※DelFEMソースコードの著作権は、梅谷信行氏にあります。  
※同梱されているLisysの著作権は、KrdLab氏にあります。  
　　DelFEM　[有限要素法(FEM)のページ](http://ums.futene.net/)  
　　Lisys　 [KrdLabの不定期日記 2009-05-07](http://d.hatena.ne.jp/KrdLab/20090507)  
  
**Contact To Human**  
何かございましたら下記までご連絡ください。  
りゅうじみや ryujimiya(あっと)mail.goo.ne.jp  
  
