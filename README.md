# scripts

#### 使用说明

##### 仅限于iOS系统的surge，Loon,Quantumult X等软件使用 

box使用请查看chavy频道https://t.me/chavyscripts

##### 京东薅羊毛工具（京东app->我的->游戏与互动->查看更多）

1.  京东水果([jd_fruit.js](https://gitee.com/lxk0301/scripts/raw/master/jd_fruit.js))
2.  东东萌宠([jd_fruit.js](https://gitee.com/lxk0301/scripts/raw/master/jd_pet.js))
3.  宠汪汪([jd_joy.js](https://gitee.com/lxk0301/scripts/raw/master/jd_joy.js))
4.  种豆得豆([jd_plantBean.js](https://gitee.com/lxk0301/scripts/raw/master/jd_plantBean.js))
5.  天天加速([jd_speed.js](https://gitee.com/lxk0301/scripts/raw/master/.js))
6.  摇钱树([jd_moneyTree.js](https://gitee.com/lxk0301/scripts/raw/master/jd_moneyTree.js))
```
//四个京东账号的Qumutumult X corn设置
[task_local]
#切换会话
18,36,46,58 1-23 * * * https://raw.githubusercontent.com/chavyleung/scripts/master/box/switcher/box.switcher.js, tag=切换会话, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/BOXJS.png, enabled=true
#京东摇钱树
15,33 */2 * * * https://gitee.com/lxk0301/scripts/raw/master/jd_moneyTree.js, tag=京东摇钱树, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/moneyTree.png, enabled=true
#京东宠汪汪
12,30 */3 * * * https://gitee.com/lxk0301/scripts/raw/master/jd_joy.js, tag=京东宠汪汪, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/jdww.png, enabled=true
#京东天天加速
10,28,48,56 */3 * * * https://gitee.com/lxk0301/scripts/raw/master/jd_speed.js, tag=京东天天加速, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/jdttjs.png, enabled=true
#东东农场
7,25,43,53 6-18/6 * * * https://gitee.com/lxk0301/scripts/raw/master/jd_fruit.js, tag=东东农场, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/jdsg.png, enabled=true
#京东萌宠
4,22,40,50 6-18/6 * * * https://gitee.com/lxk0301/scripts/raw/master/jd_pet.js, tag=京东萌宠, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/jdmc.png, enabled=true
#种豆得豆
1,19,37,47 6-23/2 * * * https://gitee.com/lxk0301/scripts/raw/master/jd_plantBean.js, tag=种豆得豆, img-url=https://raw.githubusercontent.com/znz1992/Gallery/master/jdzd.png, enabled=true

```