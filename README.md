# python cheat sheet
オレオレPythonチートシート  
TODO:jupyter notebookの項目をREADMEに移植する  

## Python
[Python](python_cheet_sheet.ipynb)  
- 他のpythonファイルのimportの挙動  
例えばimport yobidashi.pyとすると、import した時点で、呼びだし先のpython ファイルを実行することになる。  
他のファイルからimportされたときに、処理が実行されないようにするのに、if __name__ == '__main__':の恩恵が得られる。  
from yobidashi import shori のように、特定の関数のみを呼び出した場合でも、yobidashi.pyを実行じた挙動になる。  
pythonはオブジェクト指向型の言語なので、処理を実行する関数と、機能を実行する関数は分離する流儀。  
注) 複数のファイルに跨がるloggerを作成する場合は、呼び出し順に気をつける必要がある。  
[参考](https://www.mutable.work/entry/import-other-scripts#f-e3158b10)

- 関数の値渡しと参照渡し  
ミュータブルな変数を引数に入れて、関数内で値を変更すると、渡した変数の内容が関数外でも変わってしまうので注意  
[参考](https://www.javadrive.jp/python/userfunc/index3.html)


Udemyのコース  
現役シリコンバレーエンジニアが教えるPython 3 入門 + 応用 +アメリカのシリコンバレー流コードスタイル  


## Numpy  
 
 
[Numpy](numpy_cheet_sheet.ipynb)  

## Pandas
[Pandas](pandas_cheat_sheet.ipynb)  

## Scikit-Learn
[Scikit-Learn](scikit-learn_cheat_sheet.ipynb)

## PyTorch
[PyTorch](pytorch_cheet_sheet.ipynb)  

## Keras
[Keras](keras_cheet_sheet.ipynb)  
  
## Visualize
[Visualize](visualize_cheat_cheet.ipynb)  
