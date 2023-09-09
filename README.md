<html lang="en">
    
<head>
    <script type="text/javascript" src="./asz01.js">
        // 这里写的代码不会执行，执行的是js01文件
        // window.alert("Test");
    </script>
    <meta charset="UTF-8">
    <title>天帆网络科技工作室官网</title>
    <link rel="icon" href="logo.ico" type="image/x-icon">
    
    <font color="red">
     
    <marquee bgcolor="#006699">公告:本站系统正在进行全面升级...</marquee>
    
    </font>
     
    <style>
        
        @font-face {
            font-family: "1";
            src: url("VICTORIAN.ttf");
        }
        .tit{
            font-family: "1";
            font-size: 3em;
        }
        .logo{
            height: 120px;
            text-align: center;
            margin-right: 20px;
        }
        body {
            background: url("popc.png");
            font-family: sans-serif;
                    }
        .header {
            height: 200px;
            text-align: center;
            padding-top: 50px;
            margin-bottom: 5em;
        }
        .intro {
            width: 1000px;
            margin: 20px auto;
            text-align: center;
        }
        .members {
            width: 800px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
        }
        .member {
            width: 370px;
            text-align: center;
            margin: 20px;
            align-self: center;
            text-shadow: 0 0 20px #fff;
            <!--padding: 0 10px 0 10px;-->

        }
        .member:hover {
            text-shadow: 0 0 30px #fff;
        }
        .zdy {
            
            text-align: center;
         }
        .btn {
            text-decoration: none;
            border: 1px solid rgb(202, 190, 18);
            position: relative;
            overflow: hidden;
                }

        .btn:hover {
            box-shadow: 1px 1px 25px 10px rgba(146, 148, 248, 0.4);
                }

        .btn:before {
            content: "";
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(
            120deg,
            ransparent,
            rgba(146, 148, 248, 0.4),
            transparent
              
            transition: all 650ms;
                 }

        .btn:hover:before {
             left: 100%;
        
                 }
        .container {
                 display: flex;
                 justify-content: center;
                 align-items: center;
                 height: 100%;
                 width: 100%;
                         }
        .bgimgt {
                 background-image: url('./op.png');
                 background-repeat: no-repeat;
                         }      

     </style>

</div>


</head>
<body>
<div class="header">
    <h1 class="tit" style="text-shadow: 0 0 20px #2abac2;">天帆网络工作室</h1>
    <img src="logo.png" class="logo" alt="">
<div>
    
<div class="intro">

    <p style="font-family: 方正仿宋简体;font-size: 20px;text-shadow: 0 0 10px rgb(0, 115, 255);">欢迎大家共同讨论学术技术研究方面的问题和投放及共享各类【IT资源】，以及欢迎各路萌新和大神加入我们安防团队为我们打造强悍的技术，且此工作室也提供多样各式的网络攻防零基础学习环境与软件工程资源，致力于网络安全和技术研究。组织成立于2020年,现有7名核心成员。</p>
</div>
<h3>QQ网络研究工作室：984116706</h3>
<div class="members">
    <div class="member">
        <h3>软件破解-冰风</h3>
    </div>
    <div class="member">
        <h3>绫先生</h3>
    </div>
    <div class="member">
        <h3>AdminHack</h3>
    </div>
    <div class="member">
        <h3>Cloud</h3>
    </div>
    <div class="member">
        <h3>小钟</h3>
    </div>
    <div class="member">
        <h3>xiao陈</h3>
    </div>
    <div class="member">
        <h3>罗峰老师</h3>
    </div>

<style>
.center {
  text-align: center;
  border: 3px solid rgb(35, 224, 35);
}
</style>

</div>

<p style="font-family: 方正仿宋简体;font-size: 19px;text-align: center;text-shadow: 0 0 20px #00d5ff;">

◆宗旨: [  贡献  ] [  创新  ] [  坚持  ] [  进取  ] [  诚信  ] [  和谐  ] [  探索  ] [  求知  ] [  追求  ]

</p>

<div class="container">
    <!--<a href="#" class="btn"  id="btn">直接生成</a>-->
    <!--<a href="#" class="btn" target="_blank">个人主页</a>-->
</div>



<div class="zdy">
 © Powered by <a href="tfcloudsys/index.html" target="_blank">天帆云</a>
</div>
<br></br>

</body>
<!--<script async="" type="text/javascript">
    (function (name, factory) {
        if (typeof window === "object") {
            window[name] = factory();
        }
    })("Ribbons", function () {
        var _w = window, _b = document.body, _d = document.documentElement;
        var random = function () {
            if (arguments.length === 1) {
                if (Array.isArray(arguments[0])) {
                    var index = Math.round(random(0, arguments[0].length - 1));
                    return arguments[0][index];
                }
                return random(0, arguments[0]);
            } else if (arguments.length === 2) {
                return Math.random() * (arguments[1] - arguments[0]) + arguments[0];
            }
            return 0;
        };
        var screenInfo = function (e) {
            var width = Math.max(0, _w.innerWidth || _d.clientWidth || _b.clientWidth || 0),
                height = Math.max(0, _w.innerHeight || _d.clientHeight || _b.clientHeight || 0),
                scrollx = Math.max(0, _w.pageXOffset || _d.scrollLeft || _b.scrollLeft || 0) - (_d.clientLeft || 0),
                scrolly = Math.max(0, _w.pageYOffset || _d.scrollTop || _b.scrollTop || 0) - (_d.clientTop || 0);
            return {
                width: width,
                height: height,
                ratio: width / height,
                centerx: width / 2,
                centery: height / 2,
                scrollx: scrollx,
                scrolly: scrolly
            };
        };
        var mouseInfo = function (e) {
            var screen = screenInfo(e), mousex = e ? Math.max(0, e.pageX || e.clientX || 0) : 0,
                mousey = e ? Math.max(0, e.pageY || e.clientY || 0) : 0;
            return {
                mousex: mousex,
                mousey: mousey,
                centerx: mousex - screen.width / 2,
                centery: mousey - screen.height / 2
            };
        };
        var Point = function (x, y) {
            this.x = 0;
            this.y = 0;
            this.set(x, y);
        };
        Point.prototype = {
            constructor: Point, set: function (x, y) {
                this.x = x || 0;
                this.y = y || 0;
            }, copy: function (point) {
                this.x = point.x || 0;
                this.y = point.y || 0;
                return this;
            }, multiply: function (x, y) {
                this.x *= x || 1;
                this.y *= y || 1;
                return this;
            }, divide: function (x, y) {
                this.x /= x || 1;
                this.y /= y || 1;
                return this;
            }, add: function (x, y) {
                this.x += x || 0;
                this.y += y || 0;
                return this;
            }, subtract: function (x, y) {
                this.x -= x || 0;
                this.y -= y || 0;
                return this;
            }, clampX: function (min, max) {
                this.x = Math.max(min, Math.min(this.x, max));
                return this;
            }, clampY: function (min, max) {
                this.y = Math.max(min, Math.min(this.y, max));
                return this;
            }, flipX: function () {
                this.x *= -1;
                return this;
            }, flipY: function () {
                this.y *= -1;
                return this;
            }
        };
        var Factory = function (options) {
            this._canvas = null;
            this._context = null;
            this._sto = null;
            this._width = 0;
            this._height = 0;
            this._scroll = 0;
            this._ribbons = [];
            this._options = {
                colorSaturation: "80%",
                colorBrightness: "60%",
                colorAlpha: 0.65,
                colorCycleSpeed: 6,
                verticalPosition: "center",
                horizontalSpeed: 200,
                ribbonCount: 4,
                strokeSize: 0,
                parallaxAmount: -0.5,
                animateSections: true
            };
            this._onDraw = this._onDraw.bind(this);
            this._onResize = this._onResize.bind(this);
            this._onScroll = this._onScroll.bind(this);
            this.setOptions(options);
            this.init();
        };
        Factory.prototype = {
            constructor: Factory, setOptions: function (options) {
                if (typeof options === "object") {
                    for (var key in options) {
                        if (options.hasOwnProperty(key)) {
                            this._options[key] = options[key];
                        }
                    }
                }
            }, init: function () {
                try {
                    this._canvas = document.createElement("canvas");
                    this._canvas.style["display"] = "block";
                    this._canvas.style["position"] = "fixed";
                    this._canvas.style["margin"] = "0";
                    this._canvas.style["padding"] = "0";
                    this._canvas.style["border"] = "0";
                    this._canvas.style["outline"] = "0";
                    this._canvas.style["left"] = "0";
                    this._canvas.style["top"] = "0";
                    this._canvas.style["width"] = "100%";
                    this._canvas.style["height"] = "100%";
                    this._canvas.style["z-index"] = "-1";
                    this._canvas.style["background-color"] = "#1f1f1f";
                    this._canvas.id = "bgCanvas";
                    this._onResize();
                    this._context = this._canvas.getContext("2d");
                    this._context.clearRect(0, 0, this._width, this._height);
                    this._context.globalAlpha = this._options.colorAlpha;
                    // 这里可以设置是否随着窗口的滚动而滚动
                    window.addEventListener("resize", this._onResize);
                    window.addEventListener("scroll", this._onScroll);
                    // 这里设置添加的位置
                    var body_ = document.getElementsByTagName('body')[0];
                    body_.appendChild(this._canvas);
                } catch (e) {
                    console.warn("Canvas Context Error: " + e.toString());
                    return;
                }
                this._onDraw();
            }, addRibbon: function () {
                var dir = Math.round(random(1, 9)) > 5 ? "right" : "left", stop = 1000, hide = 200, min = 0 - hide,
                    max = this._width + hide, movex = 0, movey = 0, startx = dir === "right" ? min : max,
                    starty = Math.round(random(0, this._height));
                if (/^(top|min)$/i.test(this._options.verticalPosition)) {
                    starty = 0 + hide;
                } else if (/^(middle|center)$/i.test(this._options.verticalPosition)) {
                    starty = this._height / 2;
                } else if (/^(bottom|max)$/i.test(this._options.verticalPosition)) {
                    starty = this._height - hide;
                }
                var ribbon = [], point1 = new Point(startx, starty), point2 = new Point(startx, starty), point3 = null,
                    color = Math.round(random(0, 360)), delay = 0;
                while (true) {
                    if (stop <= 0) break;
                    stop--;
                    movex = Math.round((Math.random() * 1 - 0.2) * this._options.horizontalSpeed);
                    movey = Math.round((Math.random() * 1 - 0.5) * (this._height * 0.25));
                    point3 = new Point();
                    point3.copy(point2);
                    if (dir === "right") {
                        point3.add(movex, movey);
                        if (point2.x >= max) break;
                    } else if (dir === "left") {
                        point3.subtract(movex, movey);
                        if (point2.x <= min) break;
                    }
                    ribbon.push({
                        point1: new Point(point1.x, point1.y),
                        point2: new Point(point2.x, point2.y),
                        point3: point3,
                        color: color,
                        delay: delay,
                        dir: dir,
                        alpha: 0,
                        phase: 0
                    });
                    point1.copy(point2);
                    point2.copy(point3);
                    delay += 4;
                    color += this._options.colorCycleSpeed;
                }
                this._ribbons.push(ribbon);
            }, _drawRibbonSection: function (section) {
                if (section) {
                    if (section.phase >= 1 && section.alpha <= 0) {
                        return true;
                    }
                    if (section.delay <= 0) {
                        section.phase += 0.02;
                        section.alpha = Math.sin(section.phase) * 1;
                        section.alpha = section.alpha <= 0 ? 0 : section.alpha;
                        section.alpha = section.alpha >= 1 ? 1 : section.alpha;
                        if (this._options.animateSections) {
                            var mod = Math.sin(1 + section.phase * Math.PI / 2) * 0.1;
                            if (section.dir === "right") {
                                section.point1.add(mod, 0);
                                section.point2.add(mod, 0);
                                section.point3.add(mod, 0);
                            } else {
                                section.point1.subtract(mod, 0);
                                section.point2.subtract(mod, 0);
                                section.point3.subtract(mod, 0);
                            }
                            section.point1.add(0, mod);
                            section.point2.add(0, mod);
                            section.point3.add(0, mod);
                        }
                    } else {
                        section.delay -= 0.5;
                    }
                    var s = this._options.colorSaturation, l = this._options.colorBrightness,
                        c = "hsla(" + section.color + ", " + s + ", " + l + ", " + section.alpha + " )";
                    this._context.save();
                    if (this._options.parallaxAmount !== 0) {
                        this._context.translate(0, this._scroll * this._options.parallaxAmount);
                    }
                    this._context.beginPath();
                    this._context.moveTo(section.point1.x, section.point1.y);
                    this._context.lineTo(section.point2.x, section.point2.y);
                    this._context.lineTo(section.point3.x, section.point3.y);
                    this._context.fillStyle = c;
                    this._context.fill();
                    if (this._options.strokeSize > 0) {
                        this._context.lineWidth = this._options.strokeSize;
                        this._context.strokeStyle = c;
                        this._context.lineCap = "round";
                        this._context.stroke();
                    }
                    this._context.restore();
                }
                return false;
            }, _onDraw: function () {
                for (var i = 0, t = this._ribbons.length; i < t; ++i) {
                    if (!this._ribbons[i]) {
                        this._ribbons.splice(i, 1);
                    }
                }
                this._context.clearRect(0, 0, this._width, this._height);
                for (var a = 0; a < this._ribbons.length; ++a) {
                    var ribbon = this._ribbons[a], numSections = ribbon.length, numDone = 0;
                    for (var b = 0; b < numSections; ++b) {
                        if (this._drawRibbonSection(ribbon[b])) {
                            numDone++;
                        }
                    }
                    if (numDone >= numSections) {
                        this._ribbons[a] = null;
                    }
                }
                if (this._ribbons.length < this._options.ribbonCount) {
                    this.addRibbon();
                }
                requestAnimationFrame(this._onDraw);
            }, _onResize: function (e) {
                var screen = screenInfo(e);
                this._width = screen.width;
                this._height = screen.height;
                if (this._canvas) {
                    this._canvas.width = this._width;
                    this._canvas.height = this._height;
                    if (this._context) {
                        this._context.globalAlpha = this._options.colorAlpha;
                    }
                }
            }, _onScroll: function (e) {
                var screen = screenInfo(e);
                this._scroll = screen.scrolly;
            }
        };
        return Factory;
    });
    new Ribbons();
</script>-->
