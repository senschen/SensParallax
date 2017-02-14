# SensParallax
又是个依赖jq的视差滚动插件
##
  var circles1 = new SensParallax({
        ele: $('.circle-block-fast'),
        isbackround: false,
        opposite: false,
        ratio: 1,
        easing: 0.3
    });
    circles1.init();

    ##
    关键是IE下抖动的问题暂时还没解决