# Queue
標準入力から与えられるキュー操作を実際に行い、最後にキューの内容と getq された文字列 を表示するプログラム。  
  
gcc -std=c99 -o queue queue.c  
./queue  
putq a  
putq b  
putq c  
getq  
putq d  
putq e    
getq  
putq f  ←と入力し改行する。改行したら最後にCtrl-D を押す  
[c, d, e, f] ← 関数printqueue によって表示されたキューの内容    
ab ←キューからgetq された文字列  
