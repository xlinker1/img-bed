# img-bed
图床

用的是这个项目 https://github.com/Molunerfinn/PicGo

## 设置方式

在github中这样设置 settings/developer_settings/personal_access_tokens

在personal_access_tokens下面有两个选项，查到的教程基本都是用Tokens(classic)。但它要的权限太多了。

我们可以选择上面的Fine-grained tokens，限定token只能控制当前repo，并且限制权限只能commit。具体来说是将Repository permissions/Contents设置为可读写。然后其它设置正常来，将token复制到PicGo对应位置就好了。
