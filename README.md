注：所有的类在没有子类之后就不会被记录在这里面了

# 首页（index.html）

## header

header被划分为左右两个，他们的class分别为personal（左边的圆圈+一个椭圆）和listContainer（右边的导航栏，也就是那四个椭圆）

### personal

personal分为两个，他们的class分别为avatar（左边的圆圈）和userName（右边的椭圆）

### listContrainer

list分为4个，这4个的class均为list

## main

main里面只有一个东西，它的class为mainContainer

### mainContainer

mainContainer分为两个，一个是上面的灰色部分，它的class为mainTitle；另一个部分是下面的部分（两个白色的部分之和），它的class为mainContain

#### mainContain

mainContain分为两个，一个是上面那条长的，另一个是下面那条短的。由于他们在我的理解中应该分为一类，又各有特色，所以他们有一个同样的class为mainText，上面的还有一个class为longText，下面的为shortText

## footer

footer子类只有一个，它的class为footerContainer

### footerContainer

footerContainer分两个，左边的圆形为footerLogo，右边的文字为footerText

# 工作室整体介绍（overall.html）

## header

header里只有一个菜单，它的class为menu

## main

main里分两个类，一个是上面的灰色区域，它的class为mainTitle；另一个是由下面的三个白色组合成的区域，它的class为mainText

### mainText

mainText里面有三个白色的文字内容，它们三个有共同的特点，所以有同一个class为mainTextContain，另外，为了区分它们，他们三个还有另一个类名，分别为mainTextContain1，mainTextContain2，mainTextContain3

# 愿景宗旨等（wannaDo.html）

## header

header里只有一个菜单，它的class为menu

(这里抄了前面那个 工作室整体介绍 overall.html 的代码 因为这个区域这一块是一样的 等到时候交互出来了应该能融起来趴)

## main

main里是愿景宗旨的集合。由于我识别出来这是明日方舟的某一页惹，所以这里顺带把动画也做出来惹w

回到正题，main里只有一个子类，名字叫做mainContainer

### mainContainer

mainContainer的子类有五个方块，他们的class全是mainContain。它们的区分通过选择器来分别，毕竟是奇数偶数分开的嘛。

# 活动（activities.html）

## header

header里只有一个菜单，它的class为menu

(这里抄了前面那个 工作室整体介绍 overall.html 的代码 因为这个区域这一块是一样的 等到时候交互出来了应该能融起来趴)(这个括号是抄的前面那个愿景宗旨 wannaDo.html里的w)

## main

main里有六个活动，这些活动都有相似的特性，因此他们应该有同一个类名，这个类名class为active。为了保证不同的active有区别，因此每个active还有另一个类名，分别为active1，active2，active3，active4，active5，active6

### active

每个active里面都有两个部分，这大的那个方形的类名class为activeImg，小的矩形class为activeName。当然，为了保证六个的区别，这俩都会有一个额外的类名为activeImg1,2,3,4,5,6；以及activeName1,2,3,4,5,6

注：1-6是从左往右的顺序

# 活动2（activities2.html）

## header

哇 还是和上面的一样诶（废话

## main

main里有左右两边，所以尚且先这样分：左边的类名class为mainLeft，右边的类名class为mainRight（求别打我）

### mainLeft

左边的这个里面就只有一个图片哇 所以这个类里面就一个类class为mainLeftImg

### mainRight

右边的这个里面细看有三大块。为了辨别，我还是想把这个类再分两小类，上面的那个类名class为mainRightTitle，下面的那一坨类名class为mainRightText

#### mainRightTitle

这一块里面有两小块，左边应该是标题的内容，右边应该是一张图片，所以左边的类名class为mainRightTitleContain，右边的类名class为mainRightTitleImg

#### mainRightText

这一块里面有五条横线，这五个同类名，class为mainRightTextContain

# 工作环境（environment.html）

## header

...........

## main

main里面的东西分为两块，一块为上面的那个标题，另一块是下面的内容。所以上下分两个div，上面的类名class为mainTitle，下面的类名class为mainContainer

### mainTitle

里面只有一个灰色区域，它的类名class为mainTitleContain。

### mainContainer

mainContainer里面的两个部件类名class都为mainContain

#### mainContain

这里面分两个，假设（）左边是图片，右边是文字，所以左边的那个白色的类名class为mainContainImg，右边那个灰色的类名class为mainContainText



