store
    const sotre = object.assign({},EventEmitter.prototype,{
        store 存储数据

count 计数

todos  是一个数组 用来挂载数据

//得到数据
getAll（）{
    return this.todos
}
//改变tudo
addNew(title){


}

//addnew执行后应该执行的事件
addChangeListener(){

}
    })



actioncreator  也是一个对象 里面有很多的方法供view调用。异步操作可以写在这里，例如：view点击按钮后出发actions里面的某一个方法来动态获取数据，然后再去更改store

引入dispatcher  并调用 dispatcher.dispatch()方法


dispatcher  const Dispatcher = require("flux").Dispatcher

            const dispatcher = new Dispatcher()

