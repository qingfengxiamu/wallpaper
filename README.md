<h1>设置</h1>
<script type="text/javascript">
    $.backstretch([
    '壁纸链接 01',
    '壁纸链接 02'
    ], {
        fade: 1000, //动画时长
        duration: 2000 //切换延时
        });
</script>

<!--网易云音乐-->
<meting-js
        id="1941265990"  //歌曲ID song id/播放列表ID playlist id/专辑ID album id/搜索关键字 search keyword
        lrc-type="0" // lyric type 默认 0
        server="netease" //音乐平台：netease, tencent, kugou
        order="list" // 播放器播放顺序，值：'list'，'random'
        type="song"  // 要求 song, playlist, album, search, artist
        fixed="true" // 启用固定模式 默认 false
        list-olded="true" 
        autoplay="true" // 音频自动播放 默认 false
        mutex="true" // 防止同时播放多个播放器，当该播放器开始播放时暂停其他播放器 默认 true
        >
</meting-js>
