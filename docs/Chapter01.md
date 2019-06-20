# Chapter01 基本文法
## 基本演習01
double型の配列にランダム値を設定し、その最大値、最小値を表示しなさい。<br>
配列の要素数はコマンドラインから取得しなさい。<br>
要素数が指定されない場合はデフォルトで5の要素としなさい

クラス名：MinMax


## 基本演習02
半角アスタリスクを下記のように表示しなさい。
コマンドラインから数値を1つ読み込み、その数が三角形の高さにするようにしなさい。
<pre>
表示例：
*
**
***
****
*****
</pre>

クラス名：Triangle

## 基本演習03
上記「基本演習02」で出力した三角形を右回転90度に変換しなさい
<pre>
表示例：
*****
****
***
**
*
</pre>

クラス名：TriangleRoundR90

## 基本演習04
実行時の引数をドットで区切って表示するプログラムを作成しなさい。文字をドット区切りとして分割し、ArrayListに設定しなさい。
設定後、各トークンをコンソールに出力しなさい

クラス名：StringTok
<pre>
実行例：
java StringTok Hello.This.is.test
element : Hello
element : This
element : is
element : test
</pre>

## 基本演習05
ファイルをコピーするプログラムを作成しなさい。コピー元、コピー先のファイルはコマンドラインで指定します。

クラス名：FileCopy
<pre>
実行例：
java FileCopy a.txt b.txt
</pre>

## 基本演習06
下記のようなCalcクラスを使用するプログラムを作成しなさい。コマンドラインより被除算数、除算数を指定して、指定された割り算の結果を表示しなさい。例外を正しく処理しなさい。例外が発生した場合にメッセージ(getMessage())とスタックトレースを表示しなさい。
<pre>
//Calcクラス
public class Calc{
    private int num1;
    private int num2;
    
    public Calc(int num1, int num2){
        this.num1 = num1;
        this.num2 = num2;
    }
    
    public int devide(){
        return num1/num2;
    }
    
    public vod display(){
        System.out.println("num1 : " + num1);
        System.out.println("num2 : " + num2);
    }
}
</pre>

クラス名：ZeroDiv
<pre>
実行例：
java ZeroDiv 被除算数 除算数
</pre>


## 基本演習07
## 基本演習08
## 基本演習09
## 基本演習10
## 基本演習11
## 基本演習12
## 基本演習13
## 基本演習14
## 基本演習15
## 基本演習16
## 基本演習17
## 基本演習18
## 基本演習19
## 基本演習20
## 基本演習21
## 基本演習22
## 基本演習23
## 基本演習24
## 基本演習25
## 基本演習26
## 基本演習27
## 基本演習28
## 基本演習29
## 基本演習30
