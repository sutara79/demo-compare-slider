# スライドショーのプラグインの比較

## Demo
https://sutara79.github.io/demo-compare-slider/

## 条件
- jQuery1.xで動作。
- あらかじめ、スライド用画像の縦横比は揃えている。
- スライドショーを画面幅いっぱいに表示したい。
- 画面幅に応じてレスポンシブにサイズが変わってほしい。
- 特定のスライドにリンクを設置したい。
- 前後のスライドへ移るためのコントローラがほしい。
- 一定時間(今回は1秒)ごとに自動でスライドしてほしい。
- マウスオーバーで自動再生を一時停止してほしい。
- ページネーションはスライドの領域内に表示してほしい。

## 試したもの
### bxSlider 4.2.5
- GitHub: https://github.com/stevenwanderski/bxslider-4

### FlexSlider 2.6.3
- GitHub: https://github.com/woocommerce/FlexSlider  
  (`pauseOnHover`と`slideshowSpeed`のオプションは解説に載っておらず、ソースコードから探し出した)

### Swiper 3.3.1
- GitHub: https://github.com/nolimits4web/swiper/
- オプションの解説: http://idangero.us/swiper/api/

### Bootstrap 3.3.7 Carousel
- GitHub: https://github.com/twbs/bootstrap
- オプションの解説: http://getbootstrap.com/javascript/#carousel