# UIButton-WYCategory
UIButton的一些扩展
目的是为了设置button不同状态下的的title image backgroundImage backgroundColor的简便写法
例如：
 UIButton *item = [UIButton buttonWithType:UIButtonTypeCustom];
    [self.view addSubview:item];
    /**圆形Normal下背景颜色**/
    item.backgroundColor_Normal_CircularItem = [UIColor whiteColor];
    /**圆形选中时背景颜色**/
    item.backgroundColor_Selected_CircularItem = [UIColor lightGrayColor];
    item.title_Normal = @"new";
    item.titleColor_Normal = [UIColor lightGrayColor];
    item.titleColor_Selected = [UIColor whiteColor];
    /**边框宽度**/
    item.borderWidth = 1;
    /**边框颜色**/
    item.borderColor = [UIColor lightGrayColor];
    /**圆角**/
    item.cornerRadius = 30;
    item.clipsToBounds = NO;
    /**阴影颜色**/
    item.shadowColor = [UIColor blackColor];
    item.shadowOffset = CGSizeMake(0, 0);
    item.shadowOpacity = 0.8;
    
