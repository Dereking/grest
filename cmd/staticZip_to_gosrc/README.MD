This applicaition is used to generate a go resouce file which contents the static template files of GREST project. 
这个程序用来把grest cmd用到的静态模板文件打包成go源代码，里面包含base64后的zip资源包。

It will generates writeStatic.go in his parent directory. Then you can build grest command with static files buildin.
它会在上级目录生成 writeStatic.go ，你可以编译cmd 得到grest可执行文件。这样grest就可以释放静态模板文件了。

static.zip is generated by youself. It contains static files from a demo project.
static.zip 需要你自己创建，里面放了grest模板项目的静态文件