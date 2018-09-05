;;;[What is Windows?]
;;;
;;;	  You can divide  the screen of GNU Emacs  as many as you  like.
;;;	Since efficiency of implementation or so  depends  much  on  the
;;;	style  of  window division,  you  may have  your  own  style  of
;;;	partitioning.   But  if you  switch the  mode to  e-mail mode or
;;;	NetNews mode, they break your favorite style.
;;;	  Windows.el  enables  you  to  have  multiple  favorite  window
;;;	configurations at the  same time, and switch them.  Furthermore,
;;;	it can save all window  configurations into a  file and  restore
;;;	them correctly.
;;;
;;;  **For Emacs 19**
;;;
;;;	 This package provides  the `named(numbered) frame'  that can be
;;;	selected directly with their name.   With revive.el, all frames'
;;;	displaying buffers,  window configurations and size can be saved
;;;	and restored.
;;;
;;;【できる事】
;;;
;;;	  GNU Emacs では縦横任意の数だけウィンドウを分割して作業をする事
;;;	ができます。プログラムを開発する時などのウィンドウ分割は効率に大
;;;	きく影響するので、人によって好みの分割形態を持っている事でしょう。
;;;	しかしその途中で、メイルやニュースを読むとその分割形態を壊されて
;;;	しまいます。正しい手順でメイルリーダモードを終われば良いのですが、
;;;	それだとまたメイルが来た時に再びメイルリーダモードを起動しなけれ
;;;	ばなりません。
;;;	  windows.el をロードすると、好みのウィンドウ分割形態を複数持ち、
;;;	それらを切替えながら Emacs を使う事ができます。さらに、その分割
;;;	形態の全てをファイルにセーブし、いつでもそれらを復元することがで
;;;	きます。
;;;
;;;	  Emacs 19(Mule2) では、同様の操作体系で frame を単位としてウィ
;;;	ンドウ切替え操作を行います。さらに分割形態復元時にはフレームのサ
;;;	イズと位置も忠実に再現します。
