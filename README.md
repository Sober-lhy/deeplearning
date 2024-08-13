# soberlhysport
这是我的深度学习神经网络（小土堆）课程学习的笔记。附上边学习边写成的学习笔记。
目前的进度
1.transforms transform=transforms.compose([transforms.Totensor()])   
2.tensorboard    writer.add_image("题目"，img，step)
3.Mydataset     dataset的__getietm__()里面可以写transform的转变，即是在构建自己的数据集的时候可以自己在dataset里面将PIL图片格式转化成问tensor   
4.dataloader（一个数据集（应该有三个部分构造函数、获得函数、长度），batch_size(把多少张图片进行组合压缩)，shuffle=True（不同轮次取图片方式是否相同）,num_workers=0（处理线程数）,drop_last=True（最后一次舍去否））
5.nn.cov2d()  用法是创建一个神经节点（moudle）
