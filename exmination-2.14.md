# 某程序员给媳妇定制的情人节考卷(后附答案解析)
每题 _5分_ ，满分 _100分_ ，及格 _60分_

* 题目1 下面哪个不属于编程语言类型()
A. C
B. C++
C. C--
D. C#

* 题目2 请问下列哪天是一年一度的"程序员日"？
A. 02.14
B. 07.05
C. 10.24
D. 11.11

* 题目3 华为公司的logo有多少个花瓣
A. 6
B. 7
C. 8
D. 9

* 题目4 下列哪种排序算法更快()
A. 插入排序
B. 快速排序
C. 冒泡排序
D. 选择排序

* 题目5 下列组件中有别于其他三项的是()
A. ![](%E6%9F%90%E7%A8%8B%E5%BA%8F%E5%91%98%E7%BB%99%E5%AA%B3%E5%A6%87%E5%AE%9A%E5%88%B6%E7%9A%84%E6%83%85%E4%BA%BA%E8%8A%82%E8%80%83%E5%8D%B7(%E5%90%8E%E9%99%84%E7%AD%94%E6%A1%88%E8%A7%A3%E6%9E%90)/%E7%85%A7%E7%89%87%202020%E5%B9%B42%E6%9C%8811%E6%97%A5%20202316.jpg)

B.![](%E6%9F%90%E7%A8%8B%E5%BA%8F%E5%91%98%E7%BB%99%E5%AA%B3%E5%A6%87%E5%AE%9A%E5%88%B6%E7%9A%84%E6%83%85%E4%BA%BA%E8%8A%82%E8%80%83%E5%8D%B7(%E5%90%8E%E9%99%84%E7%AD%94%E6%A1%88%E8%A7%A3%E6%9E%90)/%E7%85%A7%E7%89%87%202020%E5%B9%B42%E6%9C%8811%E6%97%A5%20202325.jpg)

C. ![](%E6%9F%90%E7%A8%8B%E5%BA%8F%E5%91%98%E7%BB%99%E5%AA%B3%E5%A6%87%E5%AE%9A%E5%88%B6%E7%9A%84%E6%83%85%E4%BA%BA%E8%8A%82%E8%80%83%E5%8D%B7(%E5%90%8E%E9%99%84%E7%AD%94%E6%A1%88%E8%A7%A3%E6%9E%90)/%E7%85%A7%E7%89%87%202020%E5%B9%B42%E6%9C%8811%E6%97%A5%20202333.jpg)

D. ![](%E6%9F%90%E7%A8%8B%E5%BA%8F%E5%91%98%E7%BB%99%E5%AA%B3%E5%A6%87%E5%AE%9A%E5%88%B6%E7%9A%84%E6%83%85%E4%BA%BA%E8%8A%82%E8%80%83%E5%8D%B7(%E5%90%8E%E9%99%84%E7%AD%94%E6%A1%88%E8%A7%A3%E6%9E%90)/%E7%85%A7%E7%89%87%202020%E5%B9%B42%E6%9C%8811%E6%97%A5%20202803.jpg)

* 题目6 请问类GuoGuo的聪明()，好看()与类GuoTao、类Myj有何种关系？
```cpp
class GuoTao {
public:
    virtual void 聪明()；
···
}

class Myj {
private:
    virtual void 好看() {
        cout << "我怎么这么好看。。。"
    }
...
}

class GuoGuo : public GuoTao, Myj {
public:
    void 聪明();
    void 好看();
}
```
A. 只继承GuoTao的聪明()
B. 继承GuoTao的聪明()，继承Myj的好看()
C. 只重载GuoTao的聪明()
D. 重载GuoGuo的聪明()，重载Myj的好看()

* 题目7 请将下列程序补充完整
```cpp
class GuoTao {
public:
    const string WIFE_NAME = "_____";

    GuoTao() : _wifeName(WIFE_NAME)
private:
    string _wifeName;
}
```
A. MYJ
B. my  j
C. mYJ
D. myj

* 题目8 请选择下列程序执行后的结果()
```cpp
void GuoTao::sayLoveMyj() {
    switch (loveLevel) 
    case -1:
        cout << "my j,我爱你" << endl;
    case 1:
        cout << "爱你一生一世" << endl;
    default:
        cout << "说不出有多爱了" << endl;
}
```
A. "my j,我爱你"
B. "爱你一生一世"
C. "说不出有多爱"
D. 以上所有

* 题目9 请问以下变量定义合法的是()
A. GuoGuo 宝贝;
B. GuoGuo 牛牛娃;
C. GuoGuo 果果;
D. GuoGuo 娟儿;

* 题目10 下列程序的时间复杂度是多少()
```cpp
void Myj::哄娃(Baby &baby) {
    if (!baby.isCrying()) {
        if (!GuoTao::哔哔ing()) {
            playCellphone();
        else {
            readBooks();
        }
        return;
    }

    sendMessage(message : "妈在呢", to : baby, repeat : random(5));
} 
```
A. O(1)
B. O(N)
C. O(log(N))
D. O(N log(N))


* 题目11 下列程序的时间复杂度是多少()
```cpp
void GuoTao::哄娃(Baby &baby) {
    while (!baby.isCrying()) {
        play(baby);
    }

    call("my j").哄娃();
}
```
A. O(1)
B. O(N)
C. O(log(N))
D. O(N²)

* 题目12 选择现阶段不属于GuoGuo类的方法()
A. sayLoveMama()
B. sayMianGanGan()
C. sayGouGouMing()
D. sayLoveGuoGuo()

* 题目13 ping-pong 通常作为客户端和服务端的握手机制，请补全下列代码
```cpp
int GuoTao::ping()｛
    sendRequest("娟儿");
｝

it Myj::pong() {
    sendResponse("_____");
}
```

A. "cua腻那"
B. "小弟"
C. "公"
D. "\0"

* 题目14 某程序员写出如下代码，想表达什么意思()
```c++
void GuoGuo::PlayWithSomebody(Somebody &小朋友) {
    static bool isPlaying = false;

    if (isPlaying) {
        return;
    }

    if (小朋友.isBoy()) {
        return;
    }

    if (小朋友.getName() != "禾禾") {
        return;
    }
    
    isPlaying = true;
    while(1) {
        playWith(小朋友);
    }
}
```

A. 想给果果找1个叫禾禾的玩伴
B. 想让果果找1个叫禾禾的女朋友
C. 想让果果变成禾禾本人
D. 想让果果有1个妹妹叫禾禾

* 题目15 在GuoGuo2岁生日之前，如下方法不可能为真的是()
A. canWearShoes()
B. canStandingLongJump()
C. haveASisterNameHehe()
D. canSing()

* 题目16 请下列程序补充完整
```cpp
void GuoTao::吵架() {
    try {
        // 吵前
        see("my j").不顺眼();

        // 吵中
        for (auto i : 攒着的不敢说的话) {
            loudlySpeak(i);
        }

        // 吵后
        doSomething(________);
    } catch (...) {
        whisper("宝贝，我错了");
    }

    doEverythingWithState("提心吊胆");
}
```
A. 喝汉斯小木屋
B. 看书
C. 低头认错
D. 爱啥啥（不重要，反正没到这里来过）

* 题目17 下图为有向无环图，请思考，GuoTao与Myj之间的最短距离()
![](%E6%9F%90%E7%A8%8B%E5%BA%8F%E5%91%98%E7%BB%99%E5%AA%B3%E5%A6%87%E5%AE%9A%E5%88%B6%E7%9A%84%E6%83%85%E4%BA%BA%E8%8A%82%E8%80%83%E5%8D%B7(%E5%90%8E%E9%99%84%E7%AD%94%E6%A1%88%E8%A7%A3%E6%9E%90)/%E7%85%A7%E7%89%87%202020%E5%B9%B42%E6%9C%8811%E6%97%A5%20222609.jpg)
A. -1
B. 1
C. 2
D. 3

* 题目18 请将下列程序补充完成
```c++
bool GuoGuo::isHungry() {
    if (Time::IsNight()) {
        return false;
    }

    if (!isSaying("________")) {
        return false;
    }

    return true;
}
```
A. "喝奶奶"
B. "哇哇哇"
C. "爸爸，快那，快那"
D. "我饿了"

* 题目19 已知二叉树的中序(o,l,v,i,u,e)和后序(o,v,l,u,e,i)，那么先序遍历为____________

* 题目20 数列0,1,1,2,3,5,8,13,...,n,m,n+m,被称为菲波那契数列，猜测一下直接用定义以递归的方式求解第100项要多久()
A. 一秒不到
B. 分分钟
C. 十年吧
D. 三生三世

**参考答案(部分)**
1~5 CCCBD
6 这道题真的程序员还真不一定都会，看你的了
9 哎呀妈呀，好的称呼全叫你身上了，啥时候给我果果匀一两个叫腻味的，行不？
12 没看懂的解释一下这里面有两种动物的叫声，绵羊和公鸡
14 我的心声你应该不会不清楚吧，好吧"不要鼠宝宝"，小牛也挺可爱，再不行就小老虎，不能再拖了啊
15 学学这里面的英文啊
16 try  catch是c++中的异常处理关键字，就是说"先试试"，出问题了"hold住即可"
17 认真看图
18 果果小朋友的小日常
19 最想说的最老土的一句话
20 再单调的两个人，在一起，也能不断延展出跨越世纪的爱恋

**写在最后**
感谢你的关注，每道题都是一个故事(段子)，答案是什么并不重要。
待到春暖花开，若还能有这份儿闲情雅趣，继续写写画画、弄墨逗乐，不失为我的"免死金牌"。
当爱情变成婚姻之后，多得是鸡毛蒜皮，多得是各种无奈，多得是侮辱妥协，感谢我的爱人长久的陪伴和付出，希望我们能够一直这样闹腾下去。这里的题目你要是考不到满分，等着被收拾，爱你哟！
最后，愿有情人白头偕老，愿瘟神打盹休息。。。
