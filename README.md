# Gradients via the Adjoint Method: From Theory to Practice

アジョイント法は、微分方程式に従う変数を引数に持つスカラー関数に対して、微分方程式の初期値に関する微分（勾配）を得る方法である。
特に多自由度の場合に効率的に勾配を得ることができ、変分データ同化、ニューラルネットワークなど、適用・応用範囲は広い。
本ノートブックでは、簡単なモデルへの適用を通じてアジョイント法の基礎的な実行・実装の方法を学ぶことを目的としている。

The adjoint method is a numerical technique to obtain the derivative (gradient) of a scalar function whose argument is constrained by a differential equation.
It is particularly efficient in obtaining the gradient in the case of multiple degrees of freedom, and has a wide range of applications, including variational data assimilation and neural networks.
The purpose of this notebook is to learn how to perform and implement the basic adjoint method through application to a simple model.
