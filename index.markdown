---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---										  

<div class="scrollArea">
  ～スクロールさせるコンテンツ～
</div>
<!--//scrollArea--> 

.scrollArea{
	height: 200px;
	overflow: auto;
	padding-right: 20px;
}
/*スクロールバーの横幅指定*/
.scrollArea.deco::-webkit-scrollbar {
    width: 15px;
}
/*スクロールバーの背景色・角丸指定*/
.scrollArea.deco::-webkit-scrollbar-track {
  border-radius: 10px;
	background: #f2f2f2;
}
/*スクロールバーの色・角丸指定*/
.scrollArea.deco::-webkit-scrollbar-thumb {
  border-radius: 10px;
	background:#09C9D9;
}


<iframe src="https://www.google.com/maps/d/u/0/embed?mid=1rMVt1bc2Xd8mjDe3hJpEtVabljleHwMF" width="640" height="480"></iframe>
