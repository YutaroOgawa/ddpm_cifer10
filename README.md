# ddpm_cifer10
拡散モデルを学びたい初学者向けです。書籍「コンピュータビジョン最前線 Summer 2023」の「イマドキノ拡散モデル」の解説をベースに、CIFER-10で画像生成をします

# 概要

書籍[「コンピュータビジョン最前線 Summer 2023」](https://www.amazon.co.jp/dp/B0C6JW6T6B/)の「イマドキノ拡散モデル（石井雅人様）」の解説をもとに、基本的な拡散モデル（DDPM: Denoising Diffusion Probabilistic Models）を実装します。

訓練データはCIFER-10とし、最後に「船」のクラスだけの画像セットにファインチューニングをして、船の画像を生成します。

ノイズから画像を生成される様子をGifで保存します。

<img width="480" alt="gif" src="./ddpm_ship_230702.gif">
