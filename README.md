# test
#启动命令 supervisor --harmony index


#config-lite 配置管理的工具 也可以这么配置
#var config = require('config-lite')({
#    filename: 'default',
#    config_basedir: __dirname, //__dirname 代表当前文件所在目录
#    config_dir: 'config'
#});


#关于路由 可能是第一遍初始化的时候已经将路由关系记录了下来，所以会先执行验证的内容
#例如 router.get('/', checkNotLogin, function(req, res, next) {}会先走验证方法