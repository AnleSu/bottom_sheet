# bottom_sheet
自定义底部弹出框,

- 可设置标题

- 每一行的文字

- 点击事件自定义

- 点击取消弹框消失

  

![image-20190708174320314](http://ww2.sinaimg.cn/large/006tNc79ly1g4skmiz9q9j30h40xotcr.jpg)

test code:

BottomActionSheet.show(context, ['微信','支付宝','生成收款二维码','线下转账'],title: '请选择支付方式',callBack:(i) {

​      print('click $i');

​      return;

​    });