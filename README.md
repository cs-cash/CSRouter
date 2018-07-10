# CSRouter
控制器解耦工具/
//不带参数传递
    [[CSRouter share]push:@"PushViewController" Params:nil hideBar:YES];
    //带参数传递
//    [[CSRouter share]push:@"PushViewController" Params:@{@"pushModel":@"test"} hideBar:YES];

       //不带参数传递
    [[CSRouter share] present:@"PresentViewController" Params:nil];
    
    //带参数传递
// [[CSRouter share]目前：@“PresentViewController”参数：@ {@“presentModel”：@“test”}];
这是一个控制器解耦。用于项目的控制器之间跳转。避免了繁琐的impory各个控制器的一个过程。
